# **bvm.org.ar**
[Pagina Web](https://bvm.org.ar) para administración centralización de datos, orientado a un cuartel de bomberos.

## **Objetivo:**
* Registrar datos de usuarios para su correcto uso en el tiempo, garantizando el almacenamiento y disponibilización de los datos.
* Centralizar todo para los usuarios, desde formularios, capacitación, estadisticas entre otros.
* Modernizar a los usuarios, remplazando el papel por una interfaz accesible desde cualquier lado.

## **Funcionalidades:**
- [Seguridad con usuario y contraseña](#Login)
- [Perfil de usuario](#Perfil)
- [Formularios](#Formularios)
- [Herramientas](#Herramientas)
- [Personal](#Personal)
- [Aula Virtual](#Aula-Virtual)
- [Organigrama](#Organigrama)
- [Contactos Emergencia](#Contactos-Emergencia)
- [Aula Virtual](#Aula-Virtual)
- [Otros](#Otros)
- [Lector NFC](#Lector-NFC)
- [Stack Tecnológico](#Stack-Tecnológico)

---

## **Login**
    Todo usuario tiene su usuario y contraseña. el cual es requisito para poder acceder a la pagina.

![imagen](images/web/login.png) 

* Cuando se crea un perfil, se habilita el acceso en el login, creando una contraseña generica y el usuario la cambia cuando accede por primera vez.

---

## **Perfil**

    Todo usuario al ingresar con sus credenciales, llega a su perfil, donde tiene lo siguiente: 
* Estadisticas de intervenciones
    - Extraidas directamente de ruba, con actualización semanal
* Estadisticas de presentismo
    - Datos propios del lector NFC
* Datos Personales
    - Datos actualizables por el usuario o personal de Legajos
* Certificados
    - Cualquier certificado subido por el usuario
* Botones habilitados
    - Según los permisos tendrá distintos accesos, como ver aulas de bomberos, cadetes, ingreso.

#### Disponibilización de datos:
    Cada usuario puede ver todos sus datos mostrados en esta sección, y también supervisores habilitados, como Jefes, Oficiales, Encargados o quién sea necesario.

![imagen](images/web/perfil.png)
![imagen](images/web/certificados.png)

---

## **Formularios:**
![imagen](images/web/formularios_btn.png)

    Aquí se concentran todos los formularios creados en el sistema. Están hechos en base a la necesitad de la institución.

    En caso de ser muchos formularios, hay filtros en forma de botones a la izquierda.

#### Ejemplo:
**Formulario de Licencias:** Aquí el usuario se puede pedir licencias o vacaciones. Al enviarse, le llega una solicitud a los jefes para que dispongan de la misma.

![imagen](images/web/formularios.png)

---

## **Herramientas:**
![imagen](images/web/herramientas_btn.png)

    Hay distintas herramientas internas en la pagina, habilitadas según permisos de usuario

![imagen](images/web/herramientas.png)

#### Ejemplo:
**Panel de Ropería:** Aquí el jefe, puede ver las solicitudes y gestionarlas. Además quedan registradas y puede filtrar por **pendientes** (tienen formatos iguales todas las gestiones de solicitudes)

![imagen](images/web/panel_roperia.png)

---

## **Personal:**
![imagen](images/web/personal_btn.png)

    Desde esta función, los Supervisores pueden visualizar todos los perfiles, filtrando por tipos de usuarios, y su condición.

![imagen](images/web/menu_perfiles.png)

---

## **Aula:**
![imagen](images/web/aula_btn.png)

    Existe la función de aula virtual, separando contenido entre los distintos niveles, como Cadetes, Bomberos o Ingresantes.

    Se puede subir PDF, videos y cualquier material util para visualizar directamente desde la pagina web.

![imagen](images/web/aula.png)

---

## **Organigrama:**
![imagen](images/web/organigrama_btn.png)

    En base a los datos registrados en el formulario de "actualizar brigadas y departamentos" se crea un organigrama visual para ver la distribución interna de la institución, Facilitando una facil interpretación de la distribución del personal.
* Grafico interactivo:
![imagen](images/web/organigrama.png)

---

## **Contactos de emergencia:**
![imagen](images/web/contactos_btn.png)

    Cada usuario actualiza sus contactos de emergencia por x situación. esto lo puede consultar cualquier usuario.

![imagen](images/web/contactos_emergencia.png)

---

## **Otros:**
    Hay más funciones para visualizar datos personales o redirigir a sitios importantes.

![imagen](images/web/otros_btn.png)

---

## **Lector NFC:**

    Recientemente hemos remplazado el libro de ingreso y salida del personal por un lector digital desarrollado especificamente para la página. Esto ha solucionado aprox. 30hs mensuales de carga manual a RUBA.

    Se instaló en el ingreso a la institución un lector donde se ficha Ingreso y Salida.

![imagen](images/web/lector_nfc.jpg)

* Cada usuario tiene su tarjeta, llavero o celular con nfc. y lo registra rapidamente
* Los registros pueden ser auditados por quién esté autorizado, y posteriormente se cargan automaticamente a ruba, ahorrando muchas horas de carga manual.
* Visualización de guardia en tiempo real con las siguientes ventajas:
    * Visualización rapida de nombres con foto de perfil
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
### Puedes tener una versión personalizada para tu institución
![Gmail](https://img.shields.io/badge/-Gmail-D14836?style=flat\&logo=gmail\&logoColor=white): [matiasalbertooviedogonzalez@gmail.com](mailto:matiasalbertooviedogonzalez@gmail.com)

![🇦🇷](https://img.shields.io/badge/-Ubicación-1E90FF?style=flat\&logo=google-maps\&logoColor=white): Merlo, San Luis, Argentina
