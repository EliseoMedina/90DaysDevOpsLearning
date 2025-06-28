# � DAY 1 - Introducción a DevOps y Linux
<h1 style="color: #212529;">🚀 DAY 1 - Introducción a DevOps y Linux</h1>

<div style="background: #f8f9fa; padding: 15px; border-radius: 8px; border-left: 4px solid #28a745;">
<h2 style="color: #212529; margin-top: 0;">🧠 Reflexión Personal</h2>

### <span style="color: #212529;">🔍 ¿Qué significa DevOps para vos después de esta lección?</span>
<span style="display: inline-block; background: #d4edda; padding: 8px 12px; border-radius: 4px; margin: 5px 0; color: #155724;">
DevOps es una <strong style="color: #28a745;">cultura de colaboración</strong> que integra equipos de desarrollo (Dev) y operaciones (Ops), automatizando procesos para entregar valor continuo mediante herramientas ágiles y trabajo en equipo.
</span>

### <span style="color: #212529;">🧰 ¿Qué herramientas conocías y cuáles son nuevas?</span>
<div style="display: flex; gap: 20px; margin: 15px 0;">
<div style="flex: 1; background: #d1ecf1; padding: 10px; border-radius: 6px;">
<h4 style="color: #212529; margin: 0 0 8px 0;">🔵 Conocidas</h4>
<ul style="margin: 0; padding-left: 20px; color: #212529;">
<li>GitHub</li>
<li>Docker</li>
</ul>
</div>

<div style="flex: 1; background: #fff3cd; padding: 10px; border-radius: 6px;">
<h4 style="color: #212529; margin: 0 0 8px 0;">🟠 Nuevas</h4>
<ul style="margin: 0; padding-left: 20px; color: #212529;">
<li>(Completar según tu experiencia)</li>
</ul>
</div>
</div>
</div>

---

## <span style="color: #212529;">🐧 Primeros Pasos en Linux</span>

### <span style="color: #212529;">📌 Comandos Esenciales</span>
<div style="overflow-x: auto;">
<table style="width: 100%; border-collapse: collapse; margin: 15px 0;">
<thead style="background: #28a745; color: white;">
<tr>
<th style="padding: 10px; text-align: left;">Comando</th>
<th style="padding: 10px; text-align: left;">Descripción</th>
<th style="padding: 10px; text-align: left;">Ejemplo</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom: 1px solid #ddd;">
<td style="color: #212529;"><code>whoami</code></td>
<td style="color: #212529;">Muestra usuario actual</td>
<td style="color: #212529;"><code>whoami</code></td>
</tr>
<tr style="border-bottom: 1px solid #ddd; background: #f8f9fa;">
<td style="color: #212529;"><code>pwd</code></td>
<td style="color: #212529;">Ruta del directorio actual</td>
<td style="color: #212529;"><code>pwd</code></td>
</tr>
<tr style="border-bottom: 1px solid #ddd;">
<td style="color: #212529;"><code>ls</code></td>
<td style="color: #212529;">Lista archivos/carpetas</td>
<td style="color: #212529;"><code>ls</code></td>
</tr>
<tr style="border-bottom: 1px solid #ddd; background: #f8f9fa;">
<td style="color: #212529;"><code>ls -lah</code></td>
<td style="color: #212529;">Listado detallado</td>
<td style="color: #212529;"><code>ls -lah</code></td>
</tr>
<tr style="border-bottom: 1px solid #ddd;">
<td style="color: #212529;"><code>mkdir</code></td>
<td style="color: #212529;">Crea directorios</td>
<td style="color: #212529;"><code>mkdir proyecto</code></td>
</tr>
<tr style="border-bottom: 1px solid #ddd; background: #f8f9fa;">
<td style="color: #212529;"><code>touch</code></td>
<td style="color: #212529;">Crea archivos</td>
<td style="color: #212529;"><code>touch script.sh</code></td>
</tr>
</tbody>
</table>
</div>

### <span style="color: #212529;">🔐 Permisos en Linux</span>
<div style="display: flex; gap: 20px; margin: 20px 0;">
<div style="flex: 1; background: #f8f9fa; padding: 15px; border-radius: 8px;">
<h4 style="margin-top: 0; color: #212529;">🔢 Permisos Numéricos</h4>
<table style="width: 100%;">
<tr><th style="color: #212529;">Número</th><th style="color: #212529;">Permisos</th><th style="color: #212529;">Significado</th></tr>
<tr><td style="color: #212529;">0</td><td style="color: #212529;"><code>---</code></td><td style="color: #212529;">Sin acceso</td></tr>
<tr><td style="color: #212529;">4</td><td style="color: #212529;"><code>r--</code></td><td style="color: #212529;">Solo lectura</td></tr>
<tr><td style="color: #212529;">6</td><td style="color: #212529;"><code>rw-</code></td><td style="color: #212529;">Lectura+escritura</td></tr>
<tr><td style="color: #212529;">7</td><td style="color: #212529;"><code>rwx</code></td><td style="color: #212529;">Total acceso</td></tr>
</table>
</div>

<div style="flex: 1; background: #d4edda; padding: 15px; border-radius: 8px;">
<h4 style="margin-top: 0; color: #212529;">📝 Ejemplo Práctico</h4>
<pre style="background: #343a40; color: #f8f9fa; padding: 10px; border-radius: 5px;">
chmod 755 archivo.sh
│ │ │
│ │ └→ Otros: 5 (r-x)
│ └── Grupo: 5 (r-x)
└──── Usuario: 7 (rwx)
</pre>
</div>
</div>

---

## <span style="color: #212529;">🔍 Desafío: Linux Detectives</span>
<div style="background: #fff3cd; padding: 15px; border-radius: 8px; border-left: 4px solid #ffc107;">
<table style="width: 100%;">
<tr><th style="color: #212529;">Comando</th><th style="color: #212529;">Descripción</th><th style="color: #212529;">Uso</th></tr>
<tr><td style="color: #212529;"><code>uptime</code></td><td style="color: #212529;">Tiempo de actividad</td><td style="color: #212529;"><code>uptime</code></td></tr>
<tr><td style="color: #212529;"><code>top</code></td><td style="color: #212529;">Procesos activos</td><td style="color: #212529;"><code>top</code></td></tr>
<tr><td style="color: #212529;"><code>free -h</code></td><td style="color: #212529;">Memoria disponible</td><td style="color: #212529;"><code>free -h</code></td></tr>
</table>
</div>

---

## <span style="color: #212529;">💎 Trucos Avanzados</span>
```bash
# Crea carpeta y accede inmediatamente
mkdir proyecto && cd proyecto

# Crea/sobrescribe archivo
echo "# Mi Script" > script.sh

# Añade contenido sin borrar lo existente
echo "date" >> script.sh