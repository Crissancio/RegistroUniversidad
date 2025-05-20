# RegistroUniversidad

### Descripción del Proyecto

**RegistroUniversidad** permite realizar operaciones básicas relacionadas con la gestión de estudiantes, tales como:

* Agregar nuevos estudiantes al sistema.
* Listar todos los estudiantes registrados.
* Buscar estudiantes por criterios específicos.
* Actualizar la información de un estudiante existente.
* Eliminar estudiantes del registro.

El proyecto está organizado en paquetes que separan las diferentes capas de la aplicación, como la lógica de negocio y la interfaz de usuario. Esto facilita el mantenimiento y la escalabilidad del sistema.

### Estructura del Proyecto

La estructura del proyecto es la siguiente:

```

RegistroUniversidad/
├── src/
│   └── main/
│       └── java/
│           └── [paquetes del proyecto]
├── pom.xml
├── README.md
└── ...
```



* `src/main/java/` contiene el código fuente de la aplicación.
* `pom.xml` es el archivo de configuración de Maven que gestiona las dependencias y la compilación del proyecto.
* `README.md` proporciona información general sobre el proyecto.

### Cómo Ejecutar la Aplicación

Para compilar y ejecutar la aplicación, sigue estos pasos:

1. Asegúrate de tener Java y Maven instalados en tu sistema.
2. Clona el repositorio:

   ```
   git clone https://github.com/Crissancio/RegistroUniversidad.git
   ```


3\. Navega al directorio del proyecto:

```
cd RegistroUniversidad
```


4\. Compila el proyecto usando Maven:

```
mvn compile
```


5\. Ejecuta la aplicación:

```
mvn exec:java -Dexec.mainClass="com.universidad.Main"
```



*Nota:* Asegúrate de reemplazar `"com.universidad.Main"` con el nombre completo de la clase principal si es diferente.

### Requisitos del Sistema

* Java 8 o superior
* Maven 3.6 o superior

### Autor

Este proyecto fue desarrollado por **Cristhian Pablo Álvarez Guarachi** como parte de la práctica 2 del curso de programación.
