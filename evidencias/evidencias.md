# Evidencias

## Despliegue
1. Despliegue del backend (microservicios y base de datos):

- Descarga imagen y despliega contenedores:

![img.png](assets/img.png)


![img_1.png](assets/img_1.png)

2. Despliegue del frontend:

- Instalacion de dependencias y despliegue:

![img_2.png](assets/img_2.png)

![img_3.png](assets/img_3.png)

## Funcionalidades

1. Ingresar al sistema, para ello, segun los usuarios predeterminados que se crearon en la base de datos, se puede seleccionar
con cual queremos ingresar:

![img_4.png](assets/img_4.png)

2. Entramos al sistema, aqui podremos ver el listado de la mercancia default que viene en la base de datos y gestionarla,
tambien podemos seleccionar otro usuario:

![img_5.png](assets/img_5.png)

3. Visualizacion de la mercancia, donde podemos traer con paginacion la mercancia y filtrarla ya sea por id o por coincidencia
de nombre, tambien podemos restaurar el listado como viene de manera default:

- filtro por id:

![img_6.png](assets/img_6.png)

- filtro por coincidencia de nombre:

![img_7.png](assets/img_7.png)

4. Crear mercancia:

- Flujo correcto:

![img_8.png](assets/img_8.png)

![img_10.png](assets/img_10.png)

![img_9.png](assets/img_9.png)

- Flujo incorrecto se tuvieron en cuenta validaciones:

![img_11.png](assets/img_11.png)

![img_12.png](assets/img_12.png)

5. Ver detalle y actualizar mercancia (opcion editar), se tuvieron en cuenta las mismas validaciones de creacion:

- Flujo correcto:

![img_13.png](assets/img_13.png)

![img_14.png](assets/img_14.png)

![img_15.png](assets/img_15.png)

- Flujo incorrecto:

![img_16.png](assets/img_16.png)

6. Eliminar, se tuvo en cuenta que solo puede eliminar quien creo la mercancia:

- Flujo correcto:

![img_19.png](assets/img_19.png)

![img_20.png](assets/img_20.png)

- Flujo incorrecto: 

como ejemplo intentamos eliminar el producto recien creado por mi usuario jhohan lopez con otro usuario:

![img_17.png](assets/img_17.png)

![img_18.png](assets/img_18.png)

De manera general estas son las funcionalidades del sistema, igualmente invito a su despliegue con la guia en el [README.md](..%2FREADME.md).