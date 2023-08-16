**08/08**
**métodos http:** 

CRUD: Create Read Update Delete

GET:recuperar info de 1 server mediante URL

POST: enviar datos al server; cargar formularios o archivos

PUT: reemplaza todas las representaciones de 1 recurso especificado por el contenido cargado
(EDITAR)

DELETE: elimina representación actual del recurso de destino

>Herramientas de desarrollo: ver archivos de origen e info. sobre página web.
>Visualiza HTML, CSS, Jscript
>Visualiza solicitudes/respuestas HTTP

Web se basa en contenido. Aplicaciones web se centran en interacción del usuario; es decir, Wiki vs Google Earth.

**Introducción a algoritmos**

>>Algoritmo: procedimiento o fórmula para resolver problemas.
>>Variables: almacenes de datos que utilizamos para almacenar, recuperar y modificar datos en aplicaciones.

>>Las var necesitan ser etiquedas o nombradas de forma adecuada.
>>Existen convenciones de nomenclatura: al escribir código hay formas más adecuadas para hacerlo legible. Es necesario para que ese código puede ser leído por 3ros, pares y por incluso yo mismo en un futuro.
https://www.neoguias.com/tipos-notacion-nombres/
>>Existen palabras reservadas que no se pueden usar como id de variable.
Hay 6 tipos de primitivos:
boolean: true or false
null: sin valor
no definido: var declarada pero sin valor
number: enteros float
string: matriz de caracteres, palabras
símbolo: valor único que no es ningún otro valor

**08/09**

**JScript** y tipos de datos.

dinámico: no tienen valor particular asociado, es posible asiganr y reasignar cualquier valor a cualquier variable.

tipado débil: podemos realizar opearciones entre valores de distinto tipo creando una coeconversión de tipos 
_____

¿qué son los valores primitivos?

son valores básicos para los lenguajes de programación, fundamentales para la realización de operaciones 
> no poseen métodos ni propiedades, son innmutables  

strings = ""
numbers = 
        typeof 2
        typeof (-10)
        typeof 3.14
        typeof NaN
        typeof Infinity
        typeof -Infinity  <Cualquier número / x -0 dará -Infinity>

(0.1 + 0.2) .toFixed(1) ---> método para truncar decimales para float numbers (números con decimales), lo imprime como str, es posible fijarlo a número con + previo a paréntesis () o con Number()

// Rango mínimo y máximo del formato IEEE 754

var min = Number.MIN_SAFE_INTEGER;
var max = Number.MAX_SAFE_INTEGER;>

// ¿son iguales las var min y max a la operación?
min === -(2 ** 53) + 1;
max === (2 ** 53) - 1; 

console.log(min === -(2 ** 53) + 1);
console.log(min);
console.log(max === (2 ** 53) - 1);
console.log(max);

__________-

booleanos: true or false 

Los booleanos son un tipo de dato fundamental en la programación que representan dos valores posibles: true (verdadero) y false (falso). Los booleanos son esenciales para la toma de decisiones en la programación, ya que se utilizan para evaluar condiciones y controlar el flujo de ejecución de un programa.

==: Igual a (compara valores)
!=: Diferente de
===: Estrictamente igual a (compara valores y tipos)
!==: Estrictamente diferente de
>: Mayor que
<: Menor que
>=: Mayor o igual que
<=: Menor o igual que

var condicion = true
if(condicion){
    console.log("Se cumple la condicion")
} else{
    console.log("No se cumple")
}

esto dependerá del contexto

0, null, string vacío return false

____

null: 
El valor null en JavaScript es un valor especial que se utiliza para representar la ausencia intencional de un valor o para indicar que una variable o propiedad no tiene un valor asignado. Aquí hay algunas cosas que debes saber sobre el valor null

symbols.**

Los símbolos (Symbol) son un tipo de dato introducido en ECMAScript 2015 (ES6) que permite crear identificadores únicos e inmutables en JavaScript. A diferencia de otros tipos de datos como cadenas o números, los símbolos no tienen un valor legible y no son comparables entre sí. Aquí hay algunas cosas importantes que debes saber sobre los símbolos:

Creación de Símbolos:
Puedes crear símbolos utilizando la función Symbol(). Cada símbolo creado será único y no igual a ningún otro símbolo, incluso si tienen el mismo nombre.

var sym1 = Symbol();
var sym2 = Symbol("descripcion"); // Puedes agregar una descripción opcional para fines de depuración


_________

bigInt: El tipo de dato BigInt es una adición relativamente nueva a JavaScript, introducida en ECMAScript 2020 (ES11), que permite representar enteros arbitrariamente grandes sin perder precisión. A diferencia del tipo Number, que tiene un límite en la precisión debido a su representación en punto flotante, BigInt puede manejar números enteros muy grandes. Aquí hay

Sintaxis:
Para crear un valor BigInt, debes agregar la letra n al final del número literal. 
<var numeroBigInt = 1234567890123456789012345678901234567890n;>

Criptografía y Claves: En criptografía, las claves de cifrado pueden ser números enteros extremadamente grandes. Aquí hay un ejemplo simplificado:

const clavePrivada = 12345678901234567890123456789012345678901234567890n;
const clavePublica = 98765432109876543210987654321098765432109876543210n;

const resultado = clavePrivada * clavePublica;
console.log(resultado); // 121932631137021795415964883836242943571444916683888829754100
______

**10-08**
**HABILIDADES BLANDAS**

¿qué harías tú?

>compañero autoritario, imponente, manipulador.

---> Enfrentaría la situación directamente, su actitud está determinando el trabajo del equipo entero, por lo que no es válido que por su bienestar en particular todos trabajemos incómodos y con una presión impuesta solo por esa persona. 

>dificultad para avanzar, poca coordinación.

Es necesario hacerse cargo de la situación, tomaría acción en cuanto horarios y asumiría un rol coordinador. Haría una reunión "ultimátum" donde quede claro que no tenemos más chances y que es primordial lograr un avance demostrable.


>hipócrita y burlesco. pasivo, agresivo.

No me agradan las situaciones pasivo-agresivas, probablemente. Primero, le preguntaría a la persona "afectada" cómo se toma esos comentarios, quizás no tengo idea de que normalmente bromean así. En caso de que la persona de la que se burlan tiene una actitud pasiva y no logra engrentarlo, iría directamente con esa persona, es decir, no expondría su actitud sino que le dejaría en claro que lo que hace es algo negativo para la persona que recibe ese trato.
_____________________________________

**11-08**


