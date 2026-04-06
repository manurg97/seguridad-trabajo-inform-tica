---
layout: default
title: Riesgos Ambientales en Informática
---

<section class="riesgos-ambientales">

<p style="font-size: 1.2rem; color: var(--accent-sergio); font-weight: 500;">
Los riesgos ambientales en informática se refieren a las condiciones físicas del entorno que pueden afectar la operación de los sistemas, la integridad de los equipos y la salud de los trabajadores.
</p>

<hr style="border: 0; border-top: 1px solid rgba(255,255,255,0.1); margin: 30px 0;">

<h2 style="color: var(--accent-sergio);">1. Temperatura y Humedad</h2>
<p>
Un control inadecuado de <strong>temperatura</strong> y <strong>humedad</strong> puede afectar tanto al hardware como al rendimiento del personal.  
Mantener los servidores en <strong>18°C a 24°C</strong> y la humedad relativa entre <strong>45% y 60%</strong> es lo ideal.
</p>

<div style="text-align: center; margin: 40px 0;">
    <img src="rambientales.jpg"
         alt="Sala de servidores climatizada"
         style="width: 100%; border-radius: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.5);">
    <p style="font-size: 0.9rem; color: #64748b; margin-top: 10px;">
        Sala de servidores con climatización adecuada para proteger los equipos y garantizar su rendimiento.
    </p>
</div>

<h2 style="color: var(--accent-sergio);">2. Iluminación y Ventilación</h2>
<ul>
    <li>Iluminación suficiente y sin reflejos que provoquen fatiga visual.</li>
    <li>Ventilación constante para evitar sobrecalentamiento y acumulación de polvo.</li>
</ul>

<h2 style="color: var(--accent-sergio);">3. Ruido y Vibraciones</h2>
<p>
El ruido excesivo de equipos o vibraciones pueden afectar la concentración del personal y el correcto funcionamiento de algunos dispositivos sensibles.
</p>

<h2 style="color: var(--accent-sergio);">4. Contaminación y Polvo</h2>
<p>
El polvo, humo o partículas en el aire pueden provocar fallos eléctricos y degradación de componentes. Se recomienda:
</p>
<ul>
    <li>Filtros de aire y limpieza periódica de salas.</li>
    <li>Protección de equipos con carcasas cerradas.</li>
</ul>

<h2 style="color: var(--accent-sergio);">5. Métodos de Prevención</h2>

<div style="overflow-x: auto; margin: 30px 0;">
<table style="width: 100%; border-collapse: collapse; background: rgba(30, 41, 59, 0.3); border-radius: 12px; overflow: hidden;">
    <thead>
        <tr style="background-color: rgba(251, 146, 60, 0.2); color: var(--accent-sergio);">
            <th style="padding: 15px;">Riesgo Ambiental</th>
            <th style="padding: 15px;">Prevención / Solución</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="padding: 15px;">Temperatura y Humedad</td>
            <td style="padding: 15px;">Control climático mediante aire acondicionado, humidificadores y deshumidificadores.</td>
        </tr>
        <tr style="background: rgba(255,255,255,0.02);">
            <td style="padding: 15px;">Polvo y partículas</td>
            <td style="padding: 15px;">Filtros HEPA, limpieza periódica y sellado de gabinetes.</td>
        </tr>
        <tr>
            <td style="padding: 15px;">Ruido y Vibraciones</td>
            <td style="padding: 15px;">Aislamiento acústico, colocación de equipos sobre bases antivibración.</td>
        </tr>
        <tr style="background: rgba(255,255,255,0.02);">
            <td style="padding: 15px;">Iluminación</td>
            <td style="padding: 15px;">Luz natural o LED regulable y sin reflejos directos sobre pantallas.</td>
        </tr>
    </tbody>
</table>
</div>

<div style="background: rgba(56, 189, 248, 0.1); border: 1px dashed var(--accent-sergio); padding: 20px; border-radius: 10px; margin: 20px 0;">
    <p>
        <strong>Nota:</strong> Un entorno controlado no solo protege los equipos, también mejora la productividad y reduce riesgos para los trabajadores.
    </p>
</div>

<!-- BOTONES -->
<div class="bottom-nav">
    <a href="seguridad-fisica.html" class="nav-btn prev">◀ Seguridad Física</a>
    <a href="referencias.html" class="nav-btn next">Referencias ➜</a>
</div>

</section>

<style>
.riesgos-ambientales {
    font-size: 1.05rem;
    color: #cbd5e1;
}

.riesgos-ambientales h2 {
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

/* Botón volver a página anterior */
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
