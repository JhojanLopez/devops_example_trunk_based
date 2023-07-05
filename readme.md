# Descripcion
Ejemplo de metodologia trunk based

# Metodologia
1. inicializar el proyecto en la rama master/main
2. en caso de desarrollo crear una rama feature -> feature/jl-2345678 -> feature/`<iniciales del dev>`-`<id de feature>`
3. pushear cambios en rama feature
4. finalizado el desarrollo en la rama feature se debe solicitar el pull request (deberia ser la persona responsable para ello no el mismo desarrollador quien acepte el pull request a la rama master)

![metodologia.png](images%2Fmetodologia.png)

## Notas

si se trabaja con github al realizar el pull request y aceptarlo por defecto se te pregunta si se eliminara la rama feature.
Tambien se puede establecer esa configuracion predeterminada:

![configuracion.png](images%2Fconfiguracion.png)