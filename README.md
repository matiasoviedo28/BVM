# **bomberos.ar®**
[Página web](https://bvm.org.ar) orientada a la administración y centralización de datos de un cuartel de bomberos.

## **Objetivo:**
* Registrar los datos de los usuarios para su uso correcto a lo largo del tiempo, garantizando su almacenamiento y disponibilidad.
* Centralizar las herramientas de los usuarios, desde formularios y capacitación hasta estadísticas, entre otros.
* Modernizar a la institución, reemplazando el papel por una interfaz accesible desde cualquier lugar.

## **Funcionalidades:**
- [Seguridad con usuario y contraseña](#Login)
- [Perfil de usuario](#Perfil)
- [Formularios](#Formularios)
- [Herramientas](#Herramientas)
- [Personal](#Personal)
- [Aula Virtual](#Aula-Virtual)
- [Organigrama](#Organigrama)
- [Contactos de Emergencia](#Contactos-Emergencia)
- [Otros](#Otros)
- [Lector NFC](#Lector-NFC)
- [Stack Tecnológico](#Stack-Tecnológico)

---

## **Login**
    Cada persona cuenta con un nombre de usuario y contraseña, requisito indispensable para acceder al sitio.

![imagen](images/web/login.png) 

* Cuando se crea un perfil se habilita el acceso al login generando una contraseña genérica, que el usuario modifica al ingresar por primera vez.

---

## **Perfil**

    Al iniciar sesión con sus credenciales, cada usuario accede a su perfil, donde encuentra lo siguiente:
* Estadísticas de intervenciones
    - Extraídas directamente de RUBA con actualización semanal
* Estadísticas de presentismo
    - Datos propios del lector NFC
* Datos personales
    - Información editable por el propio usuario o por el personal de Legajos
* Certificados
    - Cualquier certificado que el usuario suba al sistema
* Botones habilitados
    - Según los permisos, dispondrá de distintos accesos, como aulas para bomberos, cadetes o ingresantes

#### Visualización de datos:
    Cada usuario puede consultar todos sus datos en esta sección. También pueden hacerlo los supervisores habilitados, como jefes, oficiales o encargados, según corresponda.

![imagen](images/web/perfil.png)
![imagen](images/web/certificados.png)

---

## **Formularios:**
![imagen](images/web/formularios_btn.png)

    Aquí se concentran todos los formularios disponibles en el sistema. Fueron desarrollados según las necesidades de la institución.

    Si la cantidad de formularios es elevada, pueden filtrarse mediante botones ubicados a la izquierda.

#### Ejemplo:
**Formulario de Licencias:** el usuario puede solicitar licencias o vacaciones. Al enviarlo, los jefes reciben una solicitud para su aprobación.

![imagen](images/web/formularios.png)

---

## **Herramientas:**
![imagen](images/web/herramientas_btn.png)

    El sitio cuenta con diversas herramientas internas habilitadas según los permisos de cada usuario

![imagen](images/web/herramientas.png)

#### Ejemplo:
**Panel de Ropería:** permite al jefe visualizar y gestionar las solicitudes. Todas quedan registradas y pueden filtrarse por **pendientes** (todas las gestiones comparten el mismo formato)

![imagen](images/web/panel_roperia.png)

---

## **Personal:**
![imagen](images/web/personal_btn.png)

    Desde esta función, los supervisores pueden visualizar todos los perfiles, filtrando por tipo de usuario y su condición.

![imagen](images/web/menu_perfiles.png)

---

## **Aula:**
![imagen](images/web/aula_btn.png)

    El sistema cuenta con un aula virtual que separa el contenido según los distintos niveles, como Cadetes, Bomberos o Ingresantes.

    Se pueden subir PDF, videos y cualquier material útil para visualizar directamente desde la página web.

![imagen](images/web/aula.png)

---

## **Organigrama:**
![imagen](images/web/organigrama_btn.png)

    En base a los datos registrados en el formulario "actualizar brigadas y departamentos" se genera un organigrama visual para observar la distribución interna de la institución, facilitando una fácil interpretación del personal.
* Gráfico interactivo:
![imagen](images/web/organigrama.png)

---

## **Contactos de emergencia:**
![imagen](images/web/contactos_btn.png)

    Cada usuario actualiza sus contactos de emergencia para cualquier situación. Esta información puede ser consultada por cualquier usuario.

![imagen](images/web/contactos_emergencia.png)

---

## **Otros:**
    Existen otras funciones para visualizar datos personales o redirigir a sitios de interés.

![imagen](images/web/otros_btn.png)

---

## **Lector NFC:**

    Recientemente hemos reemplazado el libro de ingreso y salida del personal por un lector digital desarrollado específicamente para la página. Esto ha ahorrado aproximadamente 30 horas mensuales de carga manual en RUBA.

    Se instaló en el ingreso a la institución un lector donde se registra el ingreso y la salida.

![imagen](images/web/lector_nfc.jpg)

* Cada usuario dispone de una tarjeta, llavero o celular con NFC y registra su presencia rápidamente.
* Los registros pueden ser auditados por quienes estén autorizados y posteriormente se cargan automáticamente a RUBA, ahorrando muchas horas de carga manual.
* Visualización de la guardia en tiempo real con las siguientes ventajas:
    * Visualización rápida de nombres con foto de perfil
    * Contador de choferes tipo liviana y pesada
    * Contador de las brigadas presentes.

![imagen](images/web/guardia.png)

---

## 📦 **Stack Tecnológico**

![Ubuntu](https://img.shields.io/badge/Ubuntu-Server+-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

![Python](https://img.shields.io/badge/Python-3.12+-3776AB?style=for-the-badge&logo=python&logoColor=white)

![DNS](https://img.shields.io/badge/DNS-BIND9-5E81AC?style=for-the-badge&logo=gnu-bash&logoColor=white)

![FastAPI](https://img.shields.io/badge/FastAPI-async-009688?style=for-the-badge&logo=fastapi&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13+-336791?style=for-the-badge&logo=postgresql&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-containers-2496ED?style=for-the-badge&logo=docker&logoColor=white)

![Arduino](https://img.shields.io/badge/Arduino-integration-00979D?style=for-the-badge&logo=arduino&logoColor=white)

![HTML](https://img.shields.io/badge/HTML5-semantic-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS](https://img.shields.io/badge/CSS3-styling-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

![Servidor Dedicado](https://img.shields.io/badge/Servidor-Dedicado%20RAID-6C757D?style=for-the-badge&logo=serverfault&logoColor=white)

## **Contacto:**
### Consultá por una versión personalizada para tu institución
![Gmail](https://img.shields.io/badge/-Gmail-D14836?style=flat\&logo=gmail\&logoColor=white): [matiasalbertooviedogonzalez@gmail.com](mailto:matiasalbertooviedogonzalez@gmail.com)

![🇦🇷](https://img.shields.io/badge/-Ubicación-1E90FF?style=flat\&logo=google-maps\&logoColor=white): Merlo, San Luis, Argentina

---

**bvm.org.ar** es el dominio correspondiente a Bomberos Voluntarios Merlo, a quienes se les brinda este servicio de forma gratuita. El proyecto para otras instituciones se encuentra en [bomberos.ar](https://bomberos.ar)®.
