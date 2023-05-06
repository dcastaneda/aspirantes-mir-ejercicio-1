```shell
pwd # paso 1

mkdir ejercicios # paso 2

cd ejercicios # 3

code ejercicios # paso 4

# paso 5 carpeta creada en vscode

cd ejercicio1
touch README.md  # paso 6

git config --global user.name "dcastaneda"
$ git config --global user.email example@email.com # correo omitido por privacidad  (paso 7)

cd ..
git init # paso 8

git add .
git commit -m "Versión Inicial" # paso 9

#añadiendo los pasos al README (paso 10)

git add .
git commit -m "Agrega solución primer ejercicio" # paso 11

# luego de crear el repositorio en github se agrega el remote
git remote add origin git@github.com:dcastaneda/aspirantes-mir-ejercicio-1.git 

git push origin main


git add .
git commit


```