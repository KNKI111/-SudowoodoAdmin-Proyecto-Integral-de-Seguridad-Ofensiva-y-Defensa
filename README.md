# -SudowoodoAdmin-Proyecto-Integral-de-Seguridad-Ofensiva-y-Defensa
Complete Offensive &amp; Defensive Cybersecurity Project on Debian/WordPress Infrastructure
# 🔴 SudowoodoAdmin — Proyecto Integral de Seguridad Ofensiva y Defensa

# 📌 Introducción

Este repositorio contiene el desarrollo completo de un proyecto práctico de ciberseguridad realizado sobre una máquina Linux Debian vulnerable con servicios WordPress, Apache, FTP, SSH y MariaDB expuestos en entorno controlado de laboratorio.

El objetivo principal del proyecto fue realizar un ciclo completo de:

* Reconocimiento y enumeración.
* Explotación controlada.
* Escalada de privilegios.
* Análisis forense.
* Hardening y mitigación.
* Diseño de respuesta ante incidentes.
* Desarrollo de documentación profesional.
* Automatización de auditorías.

Todo el contenido fue realizado con fines exclusivamente educativos dentro de un entorno autorizado del bootcamp.

---

# 🧠 Objetivos del Proyecto

Durante este proyecto se trabajó tanto la parte ofensiva como defensiva de la seguridad informática, simulando un escenario real de compromiso de infraestructura.

Entre los principales objetivos desarrollados destacan:

✅ Identificación de vulnerabilidades.

✅ Explotación controlada de WordPress.

✅ Enumeración de servicios inseguros.

✅ Análisis de configuraciones débiles.

✅ Obtención de acceso administrativo.

✅ Evaluación de impacto.

✅ Corrección y hardening del sistema.

✅ Desarrollo de un plan de respuesta ante incidentes.

✅ Diseño de un SGSI basado en ISO 27001.

✅ Automatización de tareas de auditoría.

---

# 📂 Contenido del Repositorio

## 📄 1. Informe de Pentesting

Documentación completa del proceso ofensivo realizado sobre la máquina vulnerable.

Incluye:

* Reconocimiento de servicios.
* Enumeración de WordPress.
* Descubrimiento de usuarios.
* Validación de credenciales débiles.
* Acceso al panel administrativo.
* Subida de plugin personalizado.
* Ejecución de código PHP.
* Reverse shell.
* Enumeración interna.
* Escalada de privilegios.
* Evidencias y capturas.
* Conclusiones técnicas.

---

## 🛡️ 2. Informe de Incidente de Seguridad

Análisis defensivo y forense posterior al compromiso del sistema.

Incluye:

* Identificación de vulnerabilidades críticas.
* Revisión de logs.
* Enumeración de usuarios y servicios.
* Análisis de configuraciones inseguras.
* Detección de FTP anónimo.
* Revisión de permisos inseguros.
* Configuración de firewall UFW.
* Hardening de Apache.
* Eliminación de artefactos sospechosos.
* Escaneo con rkhunter.
* Validación de mitigaciones.

---

## 📘 3. Plan de Respuesta ante Incidentes y SGSI (ISO 27001)

Documento estratégico desarrollado siguiendo las recomendaciones de:

* NIST SP 800-61
* ISO/IEC 27001

Incluye:

* Identificación.
* Contención.
* Erradicación.
* Recuperación.
* Lecciones aprendidas.
* Gestión de riesgos.
* Políticas de seguridad.
* Protección de activos críticos.
* Control de accesos.
* Gestión de backups.
* Planes de continuidad.
* Medidas preventivas.

---

## 🌐 4. Diagrama de Red

Diagrama profesional de la infraestructura analizada.

Representa:

* Topología actual.
* Servicios expuestos.
* Riesgos detectados.
* Segmentación recomendada.
* Firewall.
* VLANs.
* Controles de acceso.
* Mejoras de seguridad implementadas.

---

## 💻 5. Script de Automatización

Script desarrollado para automatizar tareas de auditoría y validación dentro del entorno del laboratorio.

Funciones principales:

* Enumeración básica.
* Detección de WordPress.
* Validación de configuraciones débiles.
* Identificación de servicios inseguros.
* Generación de evidencias.
* Automatización de comprobaciones.

⚠️ El script fue diseñado exclusivamente para el entorno educativo autorizado del proyecto.

---

# 🔍 Vulnerabilidades Detectadas

Durante el análisis se identificaron múltiples debilidades de seguridad:

* FTP anónimo habilitado.
* Credenciales débiles.
* Falta de segmentación.
* WordPress desactualizado.
* Configuraciones inseguras.
* Permisos inseguros en archivos críticos.
* Acceso excesivo de usuarios.
* Falta de hardening.
* Puertos innecesarios expuestos.
* Controles de acceso insuficientes.

---

# 🛠️ Herramientas Utilizadas

## Enumeración y Reconocimiento

* Nmap
* Gobuster
* Curl
* Hydra
* Netcat

## Explotación y Validación

* WordPress Admin Panel
* Plugins personalizados
* Bash
* PHP
* MariaDB

## Hardening y Defensa

* UFW
* RKHunter
* Apache2
* SSH
* Linux auditing

---

# 🧪 Metodología

La metodología seguida durante el proyecto se basó en un enfoque mixto:

### Fase ofensiva

1. Reconocimiento.
2. Enumeración.
3. Validación de vulnerabilidades.
4. Explotación controlada.
5. Escalada de privilegios.
6. Evaluación de impacto.

### Fase defensiva

1. Análisis forense.
2. Identificación de artefactos.
3. Mitigación.
4. Hardening.
5. Monitorización.
6. Respuesta ante incidentes.
7. SGSI.

---

# 📸 Evidencias

El proyecto incluye:

* Capturas reales.
* Evidencias de explotación.
* Evidencias de mitigación.
* Logs.
* Configuraciones.
* Diagramas.
* Resultados de escaneos.
* Validaciones técnicas.

---

# ⚠️ Aviso Legal

Todo el contenido de este repositorio fue realizado exclusivamente con fines educativos dentro de un entorno controlado y autorizado.

No se promueve el uso indebido de técnicas ofensivas contra sistemas no autorizados.

---

# 👨‍💻 Autor

## Christian Bauset Albo

🔴 SudowoodoAdmin

Proyecto realizado para:

🎓 4Geeks Academy

---

# ⭐ Conclusión

Este proyecto representa un ciclo completo de seguridad ofensiva y defensiva aplicado sobre un entorno Linux vulnerable, combinando explotación controlada, análisis técnico, hardening, automatización y gestión de seguridad siguiendo estándares profesionales.

El objetivo no fue únicamente comprometer el sistema, sino comprender el impacto real de las malas configuraciones y desarrollar capacidades prácticas tanto de ataque como de defensa dentro de un entorno profesional de ciberseguridad.
