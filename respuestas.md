## ¿que es una variable?
-espicios en memoria donde podemos guardar informacion (dependiendo de los tipos de datos y estructuras de datos que soporte nuetro lenguage.)

## ¿que diferencia hay entre inicializar una varible y declarar una variable?
 -declarar es cuando le desimos a javascript que vamos a crear una variable con el nombre tal. y inicilizar o reinicializar es asignarle un valor a esa variable.

(let nombre) aqui estamos declarando  (let nombre = "jeimar") inicializando una variable y si cambiamos el valor asignado de la variable estaremos reinicializando la variable.

## ¿cual es la diferencia entre sumar numeros y concatenar strings?
concatenar strings es unir los strings, sin cambiar nada los strings 

## ¿cual es el operador que nos permite sumar o concatenar?
-el operador que nos permite sumar o concatenar es (+) este operador nos permite sumar numeros cuando lo usamos con numeros  y cuando lo usamos con strings nos permite  concatenar los strings. 
let
## determina el nombre y tipo de datos para almacenar en variables la siguiente informacion:
-Nombre:string
-Apellido:string
-Nombre de usuario en platzi: string (@nombre)
-Edad:number
-correo electronico: string(jeimar@.com)
-Mayor de edad:boolean
-Dinero ahorrado:number
-Deudas:number
## traduce a codigo javascript las varibles del ejmplo anterior y deja tu codigo en los comentarios.

```
let nombre = 'jeimar Andres';
let apellido = 'cordoba';
let username = 'jeimar23';
let edad = 19;
let mail = 'jeimarpotes@.com'
let esMayorDeEdad = true;
let dineroAhorrado =1000;
let deudas = 100;
```

## calcula e imprime las siguientes variables a partir de las variables del ejemplo anterior:
-Nombre completo (nombre y apellido)
-Dinero real (dinero ahorrado menos deudas)

```
let nombreCompleto = nombre + ' ' + apellido
let dineroReal = dineroAhorrado - deudas
```
## ¿que es una funcion?
- una funcion es una herramienta que nos permite encapsular (guardar) bloques de codigo para reutilizarlos y ejecutarlos en el futuro

## ¿cuando me sirve usar una funcion en mi codigo
-Nos sirve cuando tenemos variables o bloques de codigo muy paracidos muy parecidos (con cambios que podrian ser parametros y argumentos) que podemos encapsular para reutilizar mas de una vez en el futuro.

tambien nos sirve para ordenar y mejorar la legibilidad de nuestro codigo. 

## ¿cual es la diferencia entre parametros y argumentos de una funcion?
-las funciones reciben parametros  cuando las creamos y les enviamos argumentos cuando las ejecutamos 

## convierte el siguiente codigo en una funcion, pero, cambiando cuando sea necesario las variables constantes por parametros y argumentos en una función
´´´
## ¿que tipo de condicionales existen  en javascript y cuales son sus diferencias?
el condicional if nos permite hacer validaciones  completamente distintas en acada validacion o condicional.en cambio en el switch todos los cases se comparan con la misma variable o condicion que difinimos en el switch

## ¿puedo combianr funciones y condicionales?
 si se pueden combinar y es buena practica.

## ¿que es un array ?
-es una lista de elementos

## ¿cuando es mejor usar objetos o arrays?
Arrays cuando lo que haremos en un elemento es lo mismo que en todos los demas (la regla se puede incumplir). mientras que un objeto cuando los nombres de cada elemento son importantes para nuestros algoritmo.

## ¿puedo mezclar arrays con objetos o inculso objetos con arrays?
si los arrays pueden guardar objetos. y los objetos pueden guardar arrays entre sus propiedades.

##