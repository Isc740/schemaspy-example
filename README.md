# 📊 Documentación de Base de Datos con SchemaSpy (MySQL)

Este es un repositorio que usa [SchemaSpy](http://schemaspy.org/) para generar documentación visual de una base de datos MySQL a partir de su estructura.


## ✅ Requisitos

- Java 8 o superior
- SchemaSpy [SchemaSpy](https://github.com/schemaspy/schemaspy/releases)
- Driver JDBC para [MySQL](https://dev.mysql.com/get/Downloads/Connector-J/mysql-connector-j-9.3.0.zip)
- Un archivo `.properties` configurado con los parametros para acceder a tu db.
- Tener instalada la dependencia `graphviz` en tu pc `npm install -g graphviz`


## 🚀 Cómo usar

Ejecuta ese comando en el directorio donde se encuentra schemaspy.

```bash
java -jar schemaspy-6.x.x.jar
```

## 📁 Estructura esperada

```bash
.
├── schemaspy-6.x.x.jar
├── mysql-connector-j-8.x.x.jar
├── schemaspy.properties
├── output/

