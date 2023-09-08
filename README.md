# Descripcion
Este proyecto es un sistema de inventario basado en microservicios, el cual permite realizar la gestion completa de 
cualquier tipo de mercancia creando, editando o eliminando su existencia, para ello podra ingresar con cualquier usuario
(predeterminado) al sistema para operar, las tecnologias que se usan para el aplicativo son las siguientes:

- Docker
- Postgresql
- Spring Boot
- Angular

Asi mismo los repositorios que componen el sistema son:
- [Base de datos](https://github.com/JhojanLopez/inventory_system_database) (Aqui se incluye el archivo de la estrucrura de la db (backup.backup))
- [Eureka Server](https://github.com/JhojanLopez/inventory_system_eureka)
- [Api Gateway](https://github.com/JhojanLopez/inventory_system_gateway)
- [Microservicio usuarios](https://github.com/JhojanLopez/inventory_system_users)
- [Microservicio mercancia](https://github.com/JhojanLopez/inventory_system_merchandise)
- [Sistema de inventario (frontend)](https://github.com/JhojanLopez/inventory_system_frontend)

# Despliegue
Para desplegar el backend use el docker compose añadido en la raiz del repositorio, de manera predeterminada ya esta 
configurado para que se use en un entorno local con los siguientes comandos:

- Subir sistema:
```shell
docker compose up -d
```

- Bajar sistema:
```shell
docker compose down
```

De manera opcional tambien puede ir a los repositorios antes mencionados y desplegarlos de manera individual con el orden
en el que se mencionan, tenga en cuenta que si se despliegan con docker y no con el orquestador añadido debe indicar 
las variables de entorno para que se puedan comunicar correctamente ya que no estaran en la misma red virtual.

Ahora debemos de desplegar el frontend para ello puede seguir los pasos que esta en la documentacion de 
[Sistema de inventario (frontend)](https://github.com/JhojanLopez/inventory_system_frontend). Donde debera:

- Instalar dependencias de angular:
```shell
npm install
```

- Correr el proyecto con el proxy.config añadido en la raiz del proyecto frontend.
```shell
ng serve -o --proxy-config proxy.config.js
```

Por ultimo, se añade el archivo de [evidencias.md](evidencias%2Fevidencias.md) donde se mostrara el funcionamiento general del sistema.
