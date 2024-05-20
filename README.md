# Proyecto RetailOff - Entrega Final

Este proyecto es la entrega final del desarrollo de una aplicación multiplataforma para "Retail Off", una empresa del área de retail que busca alcanzar a los nuevos clientes nativos digitales de manera rápida y eficiente. Esta aplicación está construida sobre el framework Ionic, utilizando Angular y NgModules.

## Etapas

- Realizar diseño de la aplicación móvil.
- Realizar registro de usuario.
- Realizar integración de geolocalización y scanner de códigos QR.
- Registrar clientes.
- Registrar movimientos.
- Disponibilización de APIs con Amazon Web Services.

### Primera etapa del proyecto

**Generar diseño de la aplicación Móvil con los siguientes elementos:**

- Pantalla de bienvenida.
- Inicio de sesión.
- Registro de usuario.
- Pantalla principal de movimientos y saldo de cuenta.

### Segunda parte del proyecto

- Realizar registro de usuario y autenticación con Firebase.
- Realizar scanner de códigos QR que muestren información sobre información de alguna oferta bancaria o comercial (página web, localización, otras).
- Guardar un registro local storage de los elementos escaneados.
- Obtener información sobre localización mediante API MapBox.

### Tercera Parte del proyecto

- Ingresar transacción en una base de datos DynamoDB, los campos quedan a criterio de su elección.
- Crear una función en AWS Lambda que registre y otra función que realice la consulta de los datos de la tabla creada en el punto anterior.
- Disponibilizar APIs con AWS API Gateway.
- Se implementó la conexión con una API AWS para agregar clientes, productos y envíos en la ruta `/aws`.

## Tecnologías Utilizadas

- Ionic
- Angular
- NgModules
- Firebase (para registro y autenticación de usuarios)
- Mapbox (para servicios de localización)

### Criterios de evaluación

- Diseña pantalla de bienvenida
- Diseña pantalla de registro de usuario
- Diseña pantalla de inicio de sesión
- Registra usuario por Firebase
- Consulta APIs de geolocalización
- Realiza scanner de código QR
- Realiza función AWS Lambda
- Realiza BD en DynamoDB
- Realiza API con AWS ApiGateway
- Integra Servicios de Amazon con app

## Configuración

1. Clona este repositorio en tu máquina local.
2. Instala las dependencias utilizando el comando `npm install`.
3. Configura Firebase siguiendo las instrucciones proporcionadas por Firebase para la integración en una aplicación Ionic.
4. Configura Mapbox siguiendo las instrucciones proporcionadas por Mapbox para la integración en una aplicación Ionic.
5. Realiza cualquier otra configuración necesaria según las necesidades específicas del proyecto.

## Ejecución

Una vez configurado el proyecto, puedes ejecutarlo utilizando el comando:

```bash
ionic serve
```

Esto iniciará el servidor de desarrollo y hará que la aplicación sea accesible en un navegador web en [http://localhost:8100/]

## Screenshots

Se agregó una carpeta de screenshots en la carpeta raíz para mostrar el proceso de trabajo en DynamoDB, Lambda, IAM y API Gateway. En dicha carpeta se encuentra todo el proceso de implementación de BD, funciones y API.

Además, se incluyen capturas de pantalla que muestran la interfaz de la aplicación en diferentes etapas de desarrollo, brindando una visión general del progreso y la apariencia de la aplicación.

## Autor

Jose Contreras Stoltze
