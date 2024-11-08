# instrucciones y repuestas

## Get inside the thecmdchallenge/ directory
ls y luego cd

## Print current directory path
pwd

## List all the files from the current directory including the hidden ones
ls -la

## Now list all the files inside the project, recursively (all files in the hierarchy)
ls -laR

## Clear all the clutter from the command line
clear

## Go to the last level below the small-name folder and show on the console the content of the trophy.txt file
cd y ls hasta llegar al archivo de texto y cat para mostrar el texto o find . -name trhophy.txt copias la ruta y borras el archivo de texto para llegar ahi, una vez ahi haces cat trophy.tht y te muestra el trofeo

## Move one level up and get to the funcode directory and list all files with the JavaScript typical extension
cd .. para volver nivveles y una vez ubicada la funcode ls *.js para listar los js

## Create a new directory inside funcode/the-most-funny/ called “not-that-funny“
cd en the-most-funny y una vez ahi mkdir not-that-funny y si quieres verificar cd not-that-funny

## Create a copy of the-mostboring-text.txt (you can find it within /boringfolder/‘s children) and name it lol.txt
ls y cd hasta llegar al archivo de texto, una vez ahi cp the-mostboring-text.txt lol.txt para crear una copia y cambiar el nombre

## Move funcode/kids.jpg inside funcode/images/hello/ 
volver con cd .. hasta thecmdchallenge y entrar en funcode luego de eso mv kids.jpg images, cd images, luego mv kids.jpg hello

## Remove the “small-name“ directory
volver a thecmdchallenge ahi hacer un ls y con rm -r small-name borrara el repositorio con sus archivos dentro

## Print in the command line the content of the-ultimate-joke.txt
para imprimir directamente cat $(find . -name the-ultimate-joke.txt)

## Remove all the contents from the boringfolder, they are extremely boring…
ara borrar todo usamos rm -r *

## Open the file kamehameha/dragon-ball-jokes.md using the VI command line text editor
vi dragon-ball-jokes.md para abrir una nueva terminal con todo el texto.

## Update the file kamehameha/dragon-ball-jokes.md by removing the first joke you read on the file, finally save and close the text editor
te pones en donde quieras borrar y usas la letra x para borrar luego usas shift+. y luego qw para guardar y salir
