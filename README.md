# 🍳 Recetas Estrella

> Sistema inteligente y organizado para la administración y consulta de recetas de cocina, ingredientes y categorías gastronómicas desarrollado en Visual Studio y conectado a una base de datos MySQL. El sistema permite gestionar usuarios, categorías, ingredientes y recetas de manera sencilla y organizada, brindando una herramienta útil para almacenar y consultar información gastronómica de forma eficiente.

![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)

---

## 👥 Integrantes del Equipo

| Nombre Completo | Número de Control |
| :--- | :---: |
| 🧑‍💻 CHAVIRA RUÍZ JAZMIN | `24580007` |
| 👩‍💻 DURAN TOLENTINO AMANDA NOHEMI | `24580009` |
| 👩‍💻 GARCIA ESPINOZA ANDREA | `24580011` |
| 🧑‍💻 ROMERO RAMIREZ ALEXANDER | `24580028` |
| 👩‍💻 VILLAREAL VILLALOBOS NAIBY ADRIANA | `24580914` |

---

## 🚀 Instrucciones de Instalación

### Requisitos Previos

**Hardware Mínimo:**
* Procesador Intel Core i3 o superior.
* Memoria RAM de 4 GB o superior.
* Espacio libre en disco de al menos 500 MB.

**Software Requerido:**
* Sistema Operativo Windows 10 o superior.
* Visual Studio instalado.
* MySQL Server y MySQL Workbench.
* .NET Framework correspondiente al proyecto.

### Pasos para Importar la BD y Configurar la Cadena de Conexión

Esta aplicación es un recetario interactivo. Se puede descargar por medio del código de `.sln` para que solo necesites abrirlo en Visual Studio para poder ejecutarse. Sigue estos pasos:

1. **Descargar el proyecto:** Obtén la carpeta del proyecto *Recetas Estrella* y el archivo de la base de datos proporcionado.
2. **Importar la Base de Datos:**
   * Abre **MySQL Workbench** y conéctate a tu servidor local.
   * Ejecuta el script SQL proporcionado para crear la base de datos, las tablas y los registros iniciales del programa.
3. **Configurar la Cadena de Conexión:**
   * Abre la solución del proyecto en **Visual Studio** (abre el tercer archivo de la carpeta principal para ver el código).
   * Verifica y actualiza la cadena de conexión a la base de datos con tus credenciales de acceso.
   * *Recomendación:* Puedes agregar el usuario administrador directamente a tu base de datos local para no tener que cambiar el código de MySQL, o puedes cambiar y poner tu liga y contraseña del `root` para poder usarlo. Se recomienda usar la primera opción.
4. **Ejecución:** Una vez que ambas partes estén configuradas, compila y ejecuta la aplicación. Podrás iniciar sesión con una cuenta registrada o con la cuenta de administrador. Desde el explorador de soluciones podrás ver los códigos de cada sección por si requieres realizar modificaciones.

---

## 📺 Liga al Video de Demostración

Puedes ver el sistema en funcionamiento haciendo clic en la imagen de abajo o a través del enlace directo:

[![Ver Video de Demostración](https://img.youtube.com/vi/O4_nyyX341k/0.jpg)](https://youtu.be/O4_nyyX341k)

🔗 **Enlace directo al video:** [https://youtu.be/O4_nyyX341k](https://youtu.be/O4_nyyX341k)

---

## 📸 Capturas de Pantalla Principales de la Aplicación

### Interfaces de Control y Gestión Principal
<p align="center">
  <img width="941" height="494" alt="image" src="https://github.com/user-attachments/assets/18f025cf-6500-4fcf-970a-f8b267d18909" />
  <img width="941" height="452" alt="image" src="https://github.com/user-attachments/assets/cfd05f8a-e61d-4cb1-9530-440584e69c2d" />
</p>

### Formularios de Consulta y Herramientas
<p align="center">
  <img width="508" height="378" alt="image" src="https://github.com/user-attachments/assets/83f729e4-ae48-4d64-9228-075d0c8fb922" />
  <img width="941" height="100" alt="image" src="https://github.com/user-attachments/assets/19831634-e7db-4f78-80ca-7a70-01d7156" />
</p>

### Vistas Detalladas del Sistema
<p align="center">
  <img width="405" height="733" alt="image" src="https://github.com/user-attachments/assets/41aff4dd-b30e-4cf5-b409-a0fd6ebe575a" />
  <img width="427" height="588" alt="image" src="https://github.com/user-attachments/assets/335598a7-428a-4091-993a-f03f66fec9d8" />
  <img width="428" height="633" alt="image" src="https://github.com/user-attachments/assets/4979a2be-76dc-421d-a0c2-df6d90773eec" />
</p>

### Ventanas Emergentes, Alertas e Iconografía
<p align="center">
  <img width="387" height="400" alt="image" src="https://github.com/user-attachments/assets/e0754851-cdb8-4546-a06b-ffba9efb7ccb" />
  <img width="505" height="475" alt="image" src="https://github.com/user-attachments/assets/674e9f7e-8ae7-472c-87c9-d05cae3c472a" />
</p>

<p align="center">
  <img width="186" height="206" alt="image" src="https://github.com/user-attachments/assets/b84c102d-f28c-4c70-89f2-3bba5a9cda55" />
  <img width="186" height="206" alt="image" src="https://github.com/user-attachments/assets/071f83ec-e2ea-44a4-95e9-7a74ad5279c0" />
  <img width="180" height="241" alt="image" src="https://github.com/user-attachments/assets/f26f2247-65f0-4233-b24d-a7773a72f9c7" />
</p>

---

## 📊 Diagrama ER de la Base de Datos

A continuación se presenta el modelo Entidad-Relación que estructura la base de datos en MySQL:

<p align="center">
  <img width="451" height="551" alt="Diagrama entidad-relacion" src="https://github.com/user-attachments/assets/3df74716-88bb-4290-a7a9-cd89bc4f4d9d" />
</p>
