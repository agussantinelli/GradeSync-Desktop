<h1 align="center">🎓 GradeSync - Desktop</h1>

<div align="center">
    <a href="https://github.com/agussantinelli/GradeSync-Desktop" target="_blank" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/💻%20Repo%20Principal-CalificAR-512BD4?style=for-the-badge&logo=github&logoColor=white" alt="Repo CalificAR"/>
    </a>
    <a href="#" target="_blank" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/📂%20Carpeta%20del%20Proyecto-Google%20Drive-34a853?style=for-the-badge&logo=googledrive&logoColor=white" alt="Carpeta del proyecto"/>
    </a>
</div>

<p align="center">
    <a href="https://github.com/agussantinelli" target="_blank" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/👤%20Agustín%20Santinelli-agussantinelli-000000?style=for-the-badge&logo=github&logoColor=white" alt="Agus"/>
    </a>
</p>

<p align="center">
    <img src="https://img.shields.io/badge/.NET-8.0-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET Badge"/>
    <img src="https://img.shields.io/badge/Mobile-MAUI-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="MAUI Badge"/>
    <img src="https://img.shields.io/badge/C%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C# Badge"/>
    <img src="https://img.shields.io/badge/DB-SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server Badge"/>
    <img src="https://img.shields.io/badge/Architecture-MVVM-000000?style=for-the-badge" alt="MVVM Badge"/>
    <img src="https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white" alt="Visual Studio Badge"/>
</p>

<div align="center">
  <img src="https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge&logo=gnu&logoColor=white" alt="GPLv3 License"/>
</div>

<hr>

<h2>🎯 Objetivo</h2>

<p>
    <strong>CalificAR</strong> es un sistema de <strong>gestión académica personal</strong> desarrollado en .NET MAUI. 
    Su propósito es permitir a los estudiantes llevar un control riguroso de su trayectoria educativa, administrando notas, calculando promedios de forma automática y visualizando su progreso mediante una interfaz móvil intuitiva y moderna.
</p>

<h2>🚀 Características Principales</h2>

<ul>
    <li><b>📝 Registro de Calificaciones:</b> Formulario con validaciones para materias, tipos de examen (parcial, final, TP) y fechas.</li>
    <li><b>📊 Dashboard de Rendimiento:</b> Visualización instantánea del Promedio General y Promedio Académico (considerando aplazos).</li>
    <li><b>📂 Organización Inteligente:</b> Agrupación de notas mediante <code>CollectionView</code> para una navegación clara.</li>
    <li><b>💾 Persistencia de Datos:</b> Almacenamiento local mediante base de datos SQLite para garantizar que la información no se pierda.</li>
</ul>

<h2>🛠️ Stack Técnico</h2>

<table>
    <thead>
        <tr>
            <th>Componente</th>
            <th>Tecnología</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><b>Framework</b></td>
            <td>.NET MAUI (Multi-platform App UI)</td>
        </tr>
        <tr>
            <td><b>Arquitectura</b></td>
            <td>MVVM (Model-View-ViewModel)</td>
        </tr>
        <tr>
            <td><b>Base de Datos</b></td>
            <td>SQLite con sqlite-net-pcl</td>
        </tr>
        <tr>
            <td><b>Lenguaje</b></td>
            <td>C# 12 / XAML</td>
        </tr>
    </tbody>
</table>

<h2>🏗️ Estructura del Proyecto</h2>
<p>La solución se organiza bajo un esquema de capas proactivo para asegurar escalabilidad:</p>

<ul>
    <li>📂 <b>Models/</b>: Clases de datos (Entidad <code>Grade</code>).</li>
    <li>📂 <b>Data/</b>: Lógica de conexión a base de datos y Repositorios.</li>
    <li>📂 <b>ViewModels/</b>: Cerebro de la aplicación y lógica de cálculo.</li>
    <li>📂 <b>Views/</b>: Definición de la UI en XAML.</li>
    <li>📂 <b>Converters/</b>: Formateo visual dinámico (colores y estados).</li>
</ul>

<hr>

<div align="center">
    <sub>CalificAR - Herramienta de Gestión Universitaria</sub>
</div>
