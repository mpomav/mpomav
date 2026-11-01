### Hola 👋

Soy Marco Antonio Poma Valdivia. Convierto BIM en la capa de datos que necesitan los robots de campo.

CTO de [RADS by SCIO DC](https://rads.sciodc.com) y cofundador de [SCIO DC](https://www.scio.pe). Docente en USMP y ECIC Training Center.

### En qué trabajo

- **BIM + IA:** servidores MCP para Revit y Civil 3D. Un LLM lee el modelo, audita y saca metrados. Los scripts procesan los datos dentro del software; el LLM recibe solo el resultado.
- **Robótica de captura:** teleoperación de cuadrúpedos (Unitree Go2) con LiDAR. SLAM con MOLA-LO. Entregables E57/LAZ.
- **BIM como modelo del mundo:** IFC → mapa navegable para ROS2 Nav2. Cada celda del mapa enlaza a un GUID del modelo.
- **Operación:** ERP propio y automatizaciones para la empresa.

### Contacto

<a href="https://www.linkedin.com/in/mpoma/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://www.scio.pe">
    <img src="https://img.shields.io/badge/SCIO%20DC-E06400.svg?style=for-the-badge&logo=Google%20Chrome&logoColor=white" alt="SCIO DC" />
</a>
<a href="https://rads.sciodc.com">
    <img src="https://img.shields.io/badge/RADS-333333.svg?style=for-the-badge&logo=Google%20Chrome&logoColor=white" alt="RADS" />
</a>

### Tecnología que uso

###### Mucho

![Python](https://img.shields.io/badge/PYTHON-3776AB.svg?&style=for-the-badge&logo=python&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E.svg?&style=for-the-badge&logo=ros&logoColor=white)
![Docker](https://img.shields.io/badge/DOCKER-2496ED.svg?&style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/LINUX-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/GIT-%23F05033.svg?&style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GITHUB-121011.svg?&style=for-the-badge&logo=github&logoColor=white)
![Revit](https://img.shields.io/badge/REVIT-0696D7.svg?&style=for-the-badge&logoColor=white)
![pyRevit](https://img.shields.io/badge/PYREVIT-E06400.svg?&style=for-the-badge&logoColor=white)
![Navisworks](https://img.shields.io/badge/NAVISWORKS-0696D7.svg?&style=for-the-badge&logoColor=white)
![IFC](https://img.shields.io/badge/IFC-4285F4.svg?&style=for-the-badge&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-D97757.svg?&style=for-the-badge&logoColor=white)

###### Algo

![CSharp](https://img.shields.io/badge/C%23%20.NET-512BD4.svg?&style=for-the-badge&logo=dotnet&logoColor=white)
![Civil 3D](https://img.shields.io/badge/CIVIL%203D-0696D7.svg?&style=for-the-badge&logoColor=white)
![LiDAR](https://img.shields.io/badge/LIDAR%20E57%2FLAZ-666666.svg?&style=for-the-badge&logoColor=white)
![WebRTC](https://img.shields.io/badge/WEBRTC-333333.svg?&style=for-the-badge&logo=webrtc&logoColor=white)
![React](https://img.shields.io/badge/REACT%20%2B%20THREE.JS-20232A.svg?&style=for-the-badge&logo=react&logoColor=61DAFB)
![PHP](https://img.shields.io/badge/PHP-777BB4.svg?&style=for-the-badge&logo=php&logoColor=white)

----

### Proyectos

#### BIM + IA

<table>
 <tr><th>Nombre</th><th>Estado</th><th>Tipo</th><th>Qué hace</th><th>Enlace</th></tr>
 <tr>
  <td>SCIO Revit MCP</td><td>🟠</td><td>MCP · Python</td>
  <td>Conecta un LLM con Revit. Lee el modelo, audita, saca metrados y QA/QC. Lo uso en clase: los alumnos lo instalan en su laptop. Fork de horizun-revit-mcp (Apache-2.0).</td>
  <td><!-- TODO: URL del repo --><a href="https://github.com/mpomav"><img src="https://img.shields.io/badge/repo-ver-333333?style=flat-square&logo=github" alt="Repo" /></a></td>
 </tr>
 <tr>
  <td>Civil 3D MCP</td><td>🟠</td><td>MCP · Python COM</td>
  <td>Conecta un LLM con Civil 3D por COM. Fork de Civil3D-mcp-python-COM.</td>
  <td><!-- TODO: URL del repo --><a href="https://github.com/mpomav"><img src="https://img.shields.io/badge/repo-ver-333333?style=flat-square&logo=github" alt="Repo" /></a></td>
 </tr>
 <tr>
  <td>ModVial</td><td>🟠</td><td>Plugin pyRevit</td>
  <td>Modela en Revit 2025 elementos viales y alcantarillas con parámetros. En validación técnica.</td>
  <td><img src="https://img.shields.io/badge/c%C3%B3digo-privado-666666?style=flat-square" alt="Privado" /></td>
 </tr>
 <tr>
  <td>SCIO QA</td><td>🟠</td><td>Extensión pyRevit</td>
  <td>Inventario y control de calidad de modelos Revit. Marca si un modelo es BIM paramétrico o solo copia de visualización.</td>
  <td><img src="https://img.shields.io/badge/c%C3%B3digo-privado-666666?style=flat-square" alt="Privado" /></td>
 </tr>
 <tr>
  <td>Clash Grouper</td><td>🟠</td><td>Plugin Navisworks · C#</td>
  <td>Agrupa interferencias por origen: capa de Civil 3D, tipo de Revit o entidad IFC.</td>
  <td><img src="https://img.shields.io/badge/c%C3%B3digo-privado-666666?style=flat-square" alt="Privado" /></td>
 </tr>
</table>

#### Robótica

<table>
 <tr><th>Nombre</th><th>Estado</th><th>Tipo</th><th>Qué hace</th><th>Enlace</th></tr>
 <tr>
  <td>USUY-001</td><td>🟠</td><td>ROS2 · Docker · WebRTC</td>
  <td>Plataforma de teleoperación para Unitree Go2 con LiDAR. Video, telemetría y escaneo SLAM desde el navegador.</td>
  <td><img src="https://img.shields.io/badge/c%C3%B3digo-privado-666666?style=flat-square" alt="Privado" /></td>
 </tr>
 <tr>
  <td>bim2ros</td><td>🔵</td><td>Python · IfcOpenShell</td>
  <td>Convierte IFC en mapa de ocupación para Nav2. Tabla GUID ↔ celda para anotar hallazgos del robot en el modelo BIM.</td>
  <td><img src="https://img.shields.io/badge/c%C3%B3digo-privado-666666?style=flat-square" alt="Privado" /></td>
 </tr>
 <tr>
  <td>cartilla-vuelo-dron</td><td>🟢</td><td>Web</td>
  <td>Página para control y verificación de vuelo de dron.</td>
  <td><a href="https://github.com/mpomav/cartilla-vuelo-dron"><img src="https://img.shields.io/github/stars/mpomav/cartilla-vuelo-dron?style=flat-square" alt="Stars" /></a></td>
 </tr>
</table>

#### Operación y otros

<table>
 <tr><th>Nombre</th><th>Estado</th><th>Tipo</th><th>Qué hace</th><th>Enlace</th></tr>
 <tr>
  <td>Kuber</td><td>🟢</td><td>ERP · PHP</td>
  <td>ERP/CRM de SCIO DC: cotizaciones, facturación, proyectos y planilla. Multiempresa.</td>
  <td><img src="https://img.shields.io/badge/c%C3%B3digo-privado-666666?style=flat-square" alt="Privado" /></td>
 </tr>
 <tr>
  <td>ALGAS</td><td>🟢</td><td>PWA</td>
  <td>Predicción de olas y mareas para surf. Usa datos de NOAA WaveWatch III.</td>
  <td><img src="https://img.shields.io/badge/c%C3%B3digo-privado-666666?style=flat-square" alt="Privado" /></td>
 </tr>
 <tr>
  <td>python-training-jpmorgan</td><td>⚪️</td><td>Aprendizaje</td>
  <td>Fork del curso de Python para analistas de negocio.</td>
  <td><a href="https://github.com/mpomav/python-training-jpmorgan"><img src="https://img.shields.io/badge/repo-ver-333333?style=flat-square&logo=github" alt="Repo" /></a></td>
 </tr>
</table>

Leyenda: 🟢 activo · 🟠 en desarrollo · 🔵 en diseño · 🔴 pausado · ⚪️ aprendizaje

----

### Estadísticas de GitHub

![Github Stats](https://github-readme-stats.vercel.app/api?username=mpomav&show_icons=true&theme=default&hide_border=false&locale=es)

---

![Contador](https://komarev.com/ghpvc/?username=mpomav&style=flat-square&label=Vistas%20del%20perfil)
