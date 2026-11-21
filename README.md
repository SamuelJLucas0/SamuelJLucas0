<p align="center">
  <img src="assets/banner-qro.svg" alt="Samuel Juárez Lucas · Full stack + ciberseguridad · Querétaro, México" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/samuel-juarez-lucas-8804a438b"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.credly.com/users/samuel-juarez.f38478c9"><img src="https://img.shields.io/badge/Credly-FF6B00?style=for-the-badge&logo=credly&logoColor=white" alt="Credly"></a>
</p>

<p align="center">
  <img src="assets/terminal-samm.svg" alt="Samuel Juárez Lucas, estudiante de Ingeniería de Software en la UAQ. Intereses: desarrollo full stack, ciberseguridad y Linux (administra un servidor con Arch Linux)." width="100%">
</p>

## Proyectos destacados

### DatHua · Líder del proyecto y programador
**Plataforma SaaS de monitoreo de redes para PyMEs.** Detecta fallas antes de que el negocio se detenga y las explica.

- Dirijo el proyecto y programo de punta a punta: requerimientos, arquitectura, desarrollo y documentación técnica.
- **Backend:** API REST en Node.js/Express 5 con 62 endpoints, MySQL + MongoDB, eventos en tiempo real con Socket.IO, tareas programadas y arquitectura multiempresa con autenticación JWT.
- **Agentes de sistema:** servicio de Windows y servicio de Linux con systemd que monitorean los equipos de la red mediante ICMP, SNMP y LLDP. El agente de Linux cuenta con 29 pruebas automatizadas en pytest.
- **Análisis de datos:** motor en Python que detecta anomalías con EWMA, CUSUM y percentiles.
- **Frontend:** dashboard en Vue 3 + Tailwind + Pinia con reportes en PDF/CSV.

<p align="center">
  <img src="assets/dathua-landing.jpg" width="49%" alt="Landing de DatHua">
  <img src="assets/dathua-planes.jpg" width="49%" alt="Planes y modelo de negocio de DatHua">
</p>

<details>
<summary><b>Ver arquitectura y modelo de datos</b></summary>
<br>
<p align="center"><img src="assets/dathua-arquitectura.jpg" width="90%" alt="Arquitectura del sistema DatHua: clientes, API, datos y servicios"></p>
<p align="center"><img src="assets/dathua-datos.jpg" width="90%" alt="Diagrama entidad-relación de DatHua"></p>
</details>

### SIMEI · Responsable de backend y nube
**Sistema de gestión de incidencias y mantenimiento para una facultad de la UAQ.** Proyecto en equipo; desarrollé la mayor parte del backend y la integración con la nube.

- **Base de datos en Supabase (PostgreSQL):** 9 migraciones versionadas; cambios de estado solo mediante funciones RPC; tablas de historial y auditoría inmutables; sin borrados en cascada.
- **API en Node.js/Express 5** con 47 endpoints y validación de esquemas. El frontend se comunica únicamente con la API y la base aplica los permisos de cada rol.
- **Nube:** Supabase Auth, Storage (fotos comprimidas a WebP con URL firmadas de 5 minutos), Realtime para notificaciones y pg_cron para procesos automáticos.
- **Calidad:** 24 suites de pruebas de SQL y de API, validadas contra Supabase real.
- **Trabajo en equipo:** administro el repositorio con forks y pull requests que reviso y apruebo. Hice una publicación de prueba con un túnel de Cloudflare; el despliegue en los servidores de la universidad está en camino.

<p align="center">
  <img src="assets/simei-arquitectura.jpg" width="49%" alt="Arquitectura de SIMEI: app web, API en Express y servicios de Supabase">
  <img src="assets/simei-reportar.jpg" width="49%" alt="Pantalla para reportar una incidencia en SIMEI">
</p>

<details>
<summary><b>Ver modelo de datos, sistema de diseño y versión móvil</b></summary>
<br>
<p align="center"><img src="assets/simei-datos.jpg" width="90%" alt="Diagrama de tablas y relaciones de SIMEI en PostgreSQL"></p>
<p align="center">
  <img src="assets/simei-diseno.jpg" width="60%" alt="Sistema de diseño de SIMEI con contrastes WCAG 2.2 AA">
  <img src="assets/simei-movil.jpg" width="36%" alt="SIMEI en celular">
</p>
<p align="center"><img src="assets/simei-login.jpg" width="90%" alt="Inicio de sesión de SIMEI"></p>
</details>

## Ciberseguridad

- Principio de mínimo privilegio en la base de datos: permisos por rol aplicados en PostgreSQL, funciones `security definer` con `search_path` fijo.
- Ningún secreto en el código: variables de entorno y solo archivos `.env.example` en los repositorios.
- Límite de intentos en el inicio de sesión, tokens JWT y auditoría inmutable de cambios.
- Formación en redes y seguridad con Cisco Networking Academy.

## Linux e infraestructura

- Administro un servidor con **Arch Linux** de forma remota: SSH, VPN con Tailscale y servicios con systemd.
- Experiencia con AWS (Cloud Foundations), Azure Functions, Supabase y Cloudflare.

## Tecnologías

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,py,nodejs,express,vue,react,tailwind&perline=8" alt="JavaScript, TypeScript, Python, Node.js, Express, Vue, React, Tailwind"><br>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,supabase,arch,linux,aws,azure,cloudflare,docker,git&perline=11" alt="PostgreSQL, MySQL, MongoDB, Supabase, Arch Linux, Linux, AWS, Azure, Cloudflare, Docker, Git">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude Code">
</p>

## Certificaciones

| Insignia | Emisor |
|---|---|
| Introduction to Cybersecurity | Cisco |
| Networking Basics | Cisco |
| Networking Devices and Initial Configuration | Cisco |
| English for IT 1 | Cisco |
| Cloud Foundations | AWS Academy |

[Verificar en Credly](https://www.credly.com/users/samuel-juarez.f38478c9)

## Actividad en GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=SamuelJLucas0&show_icons=true&count_private=true&include_all_commits=true&bg_color=0d1117&title_color=f0f6fc&icon_color=3fb6e8&text_color=9fb3c8&border_color=30363d&locale=es" alt="Estadísticas de GitHub">
  <img height="165" src="https://streak-stats.demolab.com?user=SamuelJLucas0&locale=es&background=0d1117&border=30363d&stroke=30363d&ring=3fb6e8&fire=3fb6e8&currStreakNum=f0f6fc&sideNums=f0f6fc&currStreakLabel=3fb6e8&sideLabels=9fb3c8&dates=6e7681" alt="Racha de contribuciones">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/SamuelJLucas0/SamuelJLucas0/output/pacman-contribution-graph-dark.svg" alt="Pac-Man recorriendo la gráfica de contribuciones" width="100%">
</p>

<p align="center"><sub>Próximamente: página con mis actividades y proyectos.</sub></p>
