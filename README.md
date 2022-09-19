## Despliegue de apps Spring Boot en Heroku

Crear archivo 'system.properties' en el proyecto con el contenido

```
java.runtime.version=18
```


1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el pc
   1. `git config --global user.name "Keffren Guerrero"`
   2. `git config --global user.email guerrero268@oulook.com`
3. Subir el proyecto a GitHub desde IntelliJ IDEA desde la operacion: VCS > Share project on GitHub
4. Desde Heroku, crear app y elegir metodo GitHub y buscar el repositorio subido
5. Habilitar deploy automatico y ejecutar deploy