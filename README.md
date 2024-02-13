# DATE

Es un objeto en javaScript que nos ayuda a especificar un momento fijo en el tiempo en un formato independiente, tomando la nota desde el 1 de enero del 1970

#### Date.now()

Devuelve el numero exacto de mili segundos que han transcurrido desde el 1 de enero de 1970, 00:00:00 UTC.

```js
let mensaje = Date.now()
```



#### Date.parse()

Retorna la fecha que le entregamos en el tiempo transcurrido desde el 1 de enero de 1970 en milisegundos.

```js
let mensaje = Date.parse("7/10/2021")
```



#### Date.UTC()

Acepta una fecha de una forma especifica, y devuelve el tiempo transcurrido desde el 1 de enero de 1970 

```js
let mensaje = new Date(Date.UTC(96, 11, 1, 0, 0, 0));
```



#### .getDate()

Retorna el dia del mes (1-31) segun la hora local

```js
let mensaje = new Date();
console.log(mensaje.getDate())
```



#### .getDay()

Retorna el dia de la semana en el que nos encontramos en un numero del (0-6) segun la hora local

```js
let mensaje = new Date();
console.log(mensaje.getDay())
```



#### .getFullYear()

Retorna el año en 4 dígitos dependiendo de la hora local

```js
let mensaje = new Date();
console.log(mensaje.getFullYear())
```



#### .getHours()

Retorna la hora en un rango de números del (0-23) segun la hora local

```js
let mensaje = new Date();
console.log(mensaje.getHours())
```



#### .getMilliseconds()

Retorna los milisegundos en un rango del (0-999) según la hora local

```js
let mensaje = new Date();
console.log(mensaje.getMilliseconds())
```



#### .getMinutes()

Retorna los minutos del momento en un rango del (0-59) según la hora local 

```js
let mensaje = new Date();
console.log(mensaje.getMinutes())
```



#### .getMonth()

Retorna el mes actual en un numero entre (0-11) según la hora actual

```js
let mensaje = new Date();
console.log(mensaje.getMonth())
```



#### .getSeconds()

Retorna los segundos (0-59) según la hora actual

```js
let mensaje = new Date();
console.log(mensaje.getSeconds())
```



#### .getTime()

Retorna los mili segundos transcurridos desde la fecha especificada

```js
let mensaje = new Date();
console.log(mensaje.getTime())
```



#### .getTimezoneOffset()

Retorna la diferencia horaria en minutos para la hora local.

```js
let mensaje = new Date();
console.log(mensaje.getTimezoneOffset())
```



#### .getUTCDate()

Retorna el dia del mes (1-31) segun la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.getUTCDate())
```



#### .getUTCDay()

Retorna el dia de la semana en el que nos encontramos en un numero del (0-6) segun la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.getUTCDay())
```



#### .getUTCFullYear()

Retorna el año en 4 dígitos dependiendo de la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.getUTCFullYear())
```



#### .getUTCHours()

Retorna la hora en un rango de números del (0-23) segun la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.getUTCHours())
```



#### .getUTCMilliseconds()

Retorna los milisegundos en un rango del (0-999) según la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.getUTCMilliseconds())
```



#### .getUTCMinutes()

Retorna los minutos del momento en un rango del (0-59) según la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.getUTCMinutes())
```



#### .getUTCMonth()

Retorna el mes actual en un numero entre (0-11) según la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.getUTCMonth())
```



#### .getUTCSeconds()

Retorna los segundos (0-59) según la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.getUTCSeconds())
```



#### .getYear()

Retorna 3 digitos que son el siglo del año y sus 2 ultimos digitos.

```js
let mensaje = new Date();
console.log(mensaje.getYear())
```



#### .setDate()

Cambia el dia del mes en la fecha especificada segun la hora local

```js
let mensaje = new Date();
console.log(mensaje.setDate(24))
```



#### .setFullYear()

Cambia el año completo los 4 digitos en la fecha especificada segun la hora local

```js
let mensaje = new Date();
console.log(mensaje.setFullYear(2021))
```



#### .setHours()

Cambia la hora en la fecha especificada segun la hora local

```js
let mensaje = new Date();
console.log(mensaje.setHours(2))
```



#### .setMilliseconds()

Cambia los milisegundos en la fecha especificada segun la hora local

```js
let mensaje = new Date();
console.log(mensaje.setMilliseconds(400))
```



#### .setMinutes()

Cambia los minutos en la fecha especificada segun la hora local

```js
let mensaje = new Date();
console.log(mensaje.setMinutes(40))
```



#### .setMonth()

Cambia el mes en la fecha especificada segun la hora local

```js
let mensaje = new Date();
console.log(mensaje.setMonth(5))
```



#### .setSeconds()

Cambia los segundos en la fecha especificada segun la hora local.

```js
let mensaje = new Date();
console.log(mensaje.setSeconds(50))
```



#### .setTime()

Cambia el tiempo en total en milisegundos en la fecha especificada segun la hora local.

```js
let mensaje = new Date();
console.log(mensaje.setTime(1505634234))
```



#### .setUTCDate()

Cambia el día del mes en la fecha especificada según la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.setUTCDate(15))
```



#### .setUTCFullYear()

Cambia el año completo los 4 dígitos en la fecha especificada según la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.setUTCFullYear(2025))
```



#### .setUTCHours()

Cambia la hora en la fecha especificada según la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.setUTCHours(20))
```



#### .setUTCMilliseconds()

Cambia los mili-segundos en la fecha especificada según la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.setUTCMilliseconds(200))
```



#### .setUTCMinutes()

Cambia los minutos en la fecha especificada según la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.setUTCMinutes(28))
```



#### .setUTCMonth()

Cambia el mes en la fecha especificada según la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.setUTCMonth(8))
```



#### .setUTCSeconds()

Cambia los segundos en la fecha especificada según la hora Universal

```js
let mensaje = new Date();
console.log(mensaje.setUTCSeconds(48))
```



#### .setYear()

Cambia el año en 3 dígitos siendo el primero el siglo y los otros 2 siendo los 2 ultimos dígitos del año

```js
let mensaje = new Date();
console.log(mensaje.setYear(219))
```



#### .toDateString()

Retorna la fecha como una cadena fácil de entender

```js
let mensaje = new Date();
console.log(mensaje.toDateString())
```



#### .toISOString()

Retorna una fecha a una cadena siguiendo el ISO 8601 de formato extendido

```js
let mensaje = new Date();
console.log(mensaje.toISOString())
```



#### .toJSON()

Retorna una cadena representada que luego se puede usar en un JSON.stringify().

```js
let mensaje = new Date();
console.log(mensaje.toJSON())
```



#### .toGMTString()

Retorna una cadena basado en la zona horaria GMT (UTC).

```js
let mensaje = new Date();
console.log(mensaje.toGMTString())
```



#### .toLocaleDateString()

Retorna una cadena con una representación sensible a la localización de la fecha basada en la configuración del sistema.

```js
let mensaje = new Date();
console.log(mensaje.toLocaleDateString())
```



#### .toLocaleString()

Retorna una cadena con una representación sensible a la localización de esta fecha.

```js
let mensaje = new Date();
console.log(mensaje.toLocaleString())
```



#### .toLocaleTimeString()

Retorna una cadena con una representación sensible a la localización de la fecha basada en la configuración del sistema.

```js
let mensaje = new Date();
console.log(mensaje.toLocaleTimeString())
```



#### .toString()

Retorna una cadena representando el objeto especificado según la hora local.

```js
let mensaje = new Date();
console.log(mensaje.toString())
```



#### .toTimeString()

Retorna la porción de tiempo

```js
let mensaje = new Date();
console.log(mensaje.toTimeString())
```



#### .toUTCString()

Retorna una cadena representando el objeto especificado según la hora Universal.

```js
let mensaje = new Date();
console.log(mensaje.toUTCString())
```



#### .valueOf()

Retorna el valor primitivo del objeto date.

```js
let mensaje = new Date();
console.log(mensaje.valueOf())
```

