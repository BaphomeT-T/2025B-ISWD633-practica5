# Ejercicio
Configurar SonarQube utilizando Docker Compose, para esto necesitas dos servicios:
- Servicio: SonarQube
- Desde el host es necesario acceder a SonarQube por lo que necesitas mapear el puerto correspondiente.
- Servicio: PostgreSQL (existen otras opciones: Microsoft SQL Server, Oracle)
- Coloca un healtcheck para cada uno de los servicios.
- Los dos servicios deben pertenecer a una red de tipo bridge
- Investiga cuáles son los volúmenes necesarios para cada servicio
- Investiga cuáles son las variables de entorno para que los servicios funcionen de manera adecuada.
  
# Una vez creado tu archivo .yaml realiza la respectiva prueba 
# COMPLETAR CON UNA CAPTURA DE PANTALLA LUEGO DE EJECUTAR EL ARCHIVO
<img width="1467" height="226" alt="image" src="https://github.com/user-attachments/assets/3729c3d9-c454-4352-8a53-89d6033855a5" />

# ACCEDER A LOCALHOST:puertoDefinido para ingresar a SonarQube
después de ingresar las credenciales:
<img width="1289" height="708" alt="image" src="https://github.com/user-attachments/assets/d539de05-06f3-47d3-a05b-8c0336bb1b77" />
