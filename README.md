Indicaciones:
- Modificar las credenciales de acceso a la base de datos Mysql en los archivos(docker-composeyml, properties de CustomerMs y AccountMs).
- Ejecutar mvn clean install en cada servicio para generar la carpeta target de los contratos OpenApi, se utilizo ContractFist.
- Se puede probar los endpoints desde el puesto del gateway: 8091 o sino los puertos de cada servicio por separado CustomerMs: 8080 y AccountMs: 8090.
