# Oscar Yair Núñez Hernández

En este repositorio se almacenan las prácticas de la materia "Sistemas Operativos y Redes"

## Prácticas parcial 1

- [Práctica 1](./Practica1.md)
- [Práctica 2](./Practica2.md)
- [Práctica 4](https://github.com/OzcarDev/practica4)
- [Práctica 8](Practica8.md)
 
 ## Prácticas parcial 2

 - [Práctica 1](https://github.com/OzcarDev/Parcial2-Practica1)

Creando la versión 1.0.0 de este repositorio

---

# Fundamentos de GIT

- **¿Cómo se inicializa un repositorio en Git?**

Para inicializar un repositorio en git, tenemos que usar el siguiente comando en la carpeta dónde queremos crear el repositorio
```bash
git init
```
- **¿Cómo creas un repositorio en GitHub?**

Para ello tenemos que ir a la pagina de GitHub y darle a crear nuevo repositorio, ahí podemos configurar su nombre y si queremos que sea publico, luego nos apareceran una lista de comandos para conectar nuestro repositorio local.

- **¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?**

Usaremos los comandos que nos indica la página de GitHub para así conectar nuestro repositorio local con el remoto y hacer nuestro primer commit.

```bash
git add .
git commit -m "Primer commit"
git branch -M main
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin main
```

Despues de esos pasos, nuestro repositorio ya estara conectado y funcional.
- **¿Cuál es el flujo básico de trabajo en Git y GitHub?**

Después de hacer cualquier cambio en nuestro repositorio 
tenemos que subir el cambio al *"Stage Area"* con el comando:

```bash
git add .
```

Después de eso tendremos que hacer un *"Commit"* con el cambio, para ello tendremos que poner una descripción del cambio que acabamos de hacer;

```bash
git commit -m "Corrigiendo errores menores"
```

Al final subiremos nuestro commit al repositorio remoto usando:

```bash
git push
```

y si queremos especificar una ruta usaremos:

```bash
git push -u origin main
```
