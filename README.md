# tarea_git

## enunciados 

EJERCICIO 1: Práctica: Realizar una guía práctica a modo de tutorial, sobre el uso de GitHub, algunos de los elementos que debe cubrir son:
1. Creación de repositorio y conexión con repositorio personal de gitHub mediante terminal con ejemplos
2. Push Y pulls a los repositorios desde el terminal con ejemplos.
3. Cada miembro del equipo debe realizar cambios en el repositorio propiedad de uno de los miembros, documenta el proceso.


## 0.markdown rules 
https://www.markdownguide.org/basic-syntax

## 1.crear llave privada ssh 
```bash 
ssh-keygen.exe -t ed25519 -C "<tu email>"
``` 
y luego dale 
```bash 
cat ~/.ssh/id_ed25519.pub
```

y sale la llave publica del ssh   

![img](https://github.com/kesshouban/tarea_git/raw/main/img/1.png)   

ahora vamos a añadirlo al github.   

`settings` > `ssh and pgp keys`

![img](https://github.com/kesshouban/tarea_git/raw/main/img/2.png)

## 2.crear y clonar repo en github 
copiar el commando 
 ![img](https://github.com/kesshouban/tarea_git/raw/main/img/3.png)

luego 
```bash 
git clone git@github.com:kesshouban/tarea_git.git
```
 ![img](https://github.com/kesshouban/tarea_git/raw/main/img/4.png)

## 3. ejemplo de git push 

