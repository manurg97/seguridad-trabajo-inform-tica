---
layout: default
title: Seguridad Física
---

<section class="seguridad-fisica">

<p style="font-size: 1.2rem; color: var(--accent-sergio); font-weight: 500;">
La seguridad física en informática se encarga de proteger los equipos, infraestructuras y personas frente a accesos no autorizados, robos o daños, garantizando la continuidad del servicio.
</p>

<hr style="border: 0; border-top: 1px solid rgba(255,255,255,0.1); margin: 30px 0;">

<h2 style="color: var(--accent-sergio);">1. ¿Qué es la Seguridad Física?</h2>
<p>
La <strong>seguridad física</strong> consiste en la protección de los activos físicos de un sistema informático, incluyendo instalaciones, hardware y personas.
</p>

<div style="text-align: center; margin: 40px 0;">
    <img src="seguridad-fisica.jpeg"
         alt="Centro de datos seguro"
         style="width: 100%; border-radius: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.5);">
    <p style="font-size: 0.9rem; color: #64748b; margin-top: 10px;">
        Centro de datos protegido mediante sistemas de seguridad física.
    </p>
</div>

<h2 style="color: var(--accent-sergio);">2. Objetivos Principales</h2>
<ul>
    <li>Proteger a las personas.</li>
    <li>Evitar daños o robos de equipos.</li>
    <li>Garantizar la continuidad del servicio.</li>
    <li>Prevenir y responder ante incidentes.</li>
</ul>

<h2 style="color: var(--accent-sergio);">3. Infraestructura y Equipos</h2>

<div style="display: flex; gap: 20px; flex-wrap: wrap; margin: 30px 0;">
    <div style="flex: 1; min-width: 250px; background: rgba(255,255,255,0.03); padding: 20px; border-radius: 10px;">
        <h3>Equipos críticos</h3>
        <ul>
            <li>Servidores</li>
            <li>Ordenadores</li>
            <li>Dispositivos de red</li>
        </ul>
    </div>

    <div style="flex: 1; min-width: 250px; background: rgba(255,255,255,0.03); padding: 20px; border-radius: 10px;">
        <h3>Elementos físicos</h3>
        <ul>
            <li>Cableado</li>
            <li>Racks</li>
            <li>Sistemas eléctricos</li>
        </ul>
    </div>
</div>

<h2 style="color: var(--accent-sergio);">4. Equipos Móviles</h2>
<ul>
    <li>Pérdida de dispositivos</li>
    <li>Robo</li>
    <li>Acceso no autorizado</li>
</ul>

<h2 style="color: var(--accent-sergio);">5. Métodos de Protección</h2>

<div style="overflow-x: auto; margin: 30px 0;">
<table style="width: 100%; border-collapse: collapse; background: rgba(30, 41, 59, 0.3); border-radius: 12px; overflow: hidden;">
    <thead>
        <tr style="background-color: rgba(251, 146, 60, 0.2); color: var(--accent-sergio);">
            <th style="padding: 15px;">Medida</th>
            <th style="padding: 15px;">Descripción</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="padding: 15px;">Control de acceso</td>
            <td style="padding: 15px;">Tarjetas, biometría o vigilancia.</td>
        </tr>
        <tr style="background: rgba(255,255,255,0.02);">
            <td style="padding: 15px;">CCTV</td>
            <td style="padding: 15px;">Cámaras y sensores.</td>
        </tr>
        <tr>
            <td style="padding: 15px;">Protección hardware</td>
            <td style="padding: 15px;">Cerraduras y anclajes.</td>
        </tr>
        <tr style="background: rgba(255,255,255,0.02);">
            <td style="padding: 15px;">Desastres</td>
            <td style="padding: 15px;">Incendios, UPS, climatización.</td>
        </tr>
    </tbody>
</table>
</div>

<h2 style="color: var(--accent-sergio);">6. Protección de Datos</h2>
<ul>
    <li>🔐 Cifrado</li>
    <li>💾 Copias de seguridad</li>
    <li>🔑 Control de accesos</li>
</ul>

<h2 style="color: var(--accent-sergio);">7. Factor Humano</h2>
<ul>
    <li>No dejar equipos solos</li>
    <li>Bloquear sesión</li>
    <li>No compartir credenciales</li>
</ul>

<div style="background: rgba(56, 189, 248, 0.1); border: 1px dashed var(--accent-sergio); padding: 20px; border-radius: 10px; margin: 20px 0;">
    <p>
        <strong>Conclusión:</strong> La seguridad física es esencial para proteger sistemas informáticos y evitar vulnerabilidades críticas.
    </p>
</div>

<!-- BOTONES -->
<div class="bottom-nav">
    <a href="index.html" class="nav-btn home">🏠 Volver al inicio</a>
    <a href="rambientales.html" class="nav-btn next">Siguiente ➜</a>
</div>

</section>

<style>
.seguridad-fisica {
    font-size: 1.05rem;
    color: #cbd5e1;
}

.seguridad-fisica h2 {
    margin-top: 2rem;
    border-bottom: 1px solid rgba(251, 146, 60, 0.2);
    padding-bottom: 10px;
}

/* BOTONES */
.bottom-nav {
    display: flex;
    justify-content: space-between;
    margin-top: 50px;
}

.nav-btn {
    padding: 12px 20px;
    border-radius: 10px;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

/* Botón inicio */
.home {
    background: #334155;
    color: white;
}

.home:hover {
    background: #475569;
}

/* Botón siguiente (destacado) */
.next {
    background: linear-gradient(90deg, #38bdf8, #4ade80);
    color: #0f172a;
}

.next:hover {
    transform: scale(1.05);
}
</style>
