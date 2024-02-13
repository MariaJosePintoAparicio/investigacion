Métodos de instanciación

1.  .getDate()
Para que me de  la fecha de hoy 
ejemplo: 
new Date().getDate()
12

2.  .getDay()
me dice en que dia de la semana estoy
ejemplo:
new Date().getDay()
1

3.  .getFullYear()
me dice el año en el que me encuentro 
ejemplo:
new Date().getFullYear()
2024

4.  .getHours()
me dice la hora en la que estoy actualmente 
ejemplo:
new Date().getHours()
9

5. .getMilliseconds()
medice los segundos en los que voy segun la hora en la que estoy
ejemplo:
new Date().getMilliseconds()
405

6. .getMinutes()
me dice los minutos en los que esta la hora en este momento son las 9:13
ejemplo:
new Date ().getMinutes()
13

7. .getMonth()
me dice en el mes que nos encontramos 
ejemplo:
new Date ().getMonth()
2

8.  .getSeconds()
me dice los seguntos que voy en el minuto actualmente
elemplo:
new Date().getSeconds()
52

9. .getTime()
me dice cuantos segundos han pasado desde que inicio el año 
ejemplo:
new Date().getTime()
1707747426780

10.  .getTimezoneOffset()
me dice cuantas horas han pasado desde que inicio el año 
ejemplo:
new Date().getTimezoneOffset()
300

11.  .getUTCDate() 
me dice que dia de el mes en el que me encunetro 
ejemplo:
new Date().getUTCDate() 
12

12. .getUTCDay() 
me dice en que dia de la semana estoy 
ejemplo:
new Date().getUTCDay() 
1

13. .getUTCFullYear()
me dice el año en el que estoy 
ejemplo:
new Date().getUTCFullYear()
2024

14. .getUTCHours()
me dice la hora exacta en la que estoy del dia ejemplo el dia tiene 24 horas y me encuento en la hora numero 
ejemplo: 
new Date().getUTCHours()
14

15. .getUTCMilliseconds() 
me dice cuantos segundos llevo desde que inicio el año 
ejemplo:
new Date().getUTCMilliseconds()
964

16. .getUTCDay() 
me dice en que dia de la semana estoy 
ejemplo:
new Date ().getUTCDay() 
1

17.  .getUTCFullYear()
me dice el año actualmente
ejemplo:
new Date().getUTCFullYear()
2024

18. .getUTCHours() 
me dice actualmente la hora en la q estoy de el dia 
ejemplo:
new Date().getUTCHours()
14

19.  .getUTCMilliseconds()
me dicen los milisegundos en los que me encuentro 
ejemplo:
new Date().getUTCMilliseconds()
219

20. .getUTCMinutes() 
minutos en los que estoy de la hora actualmente 
ejemplo:
new Date().getUTCMinutes()
34


21. .getUTCMonth()
mes en el que me encuentro 
ejemplo:
new Date().getUTCMonth()
1

22. .getUTCSeconds() 
me dice en que segundos estoy actualmente 
ejemplo:
new Date().getUTCSeconds() 
59

23. .getYear()
me dice la hora en la que me encuentro del año 
ejemplo:
new Date().getYear()
124

24. .setDate()
se supone que me dice el dia de el mes en el que me encuentro pero me salio esto
ejemplo:
new Date().setDate()
NaN

25.  .setFullYear()
me dice el año y la fecha especificada como no coloque nada me salio asi 
ejemplo:
new Date().setFullYear()
NaN

26. .setHours() 
me dice la hora de una fecha que yo elija 
ejemplo:
new Date().setHours()
NaN
como no ejegi fecha sale asi 

27. .setMilliseconds() 
me dice los milisegundos a una fecha que yo le de como no coloque nada sale asi 
ejemplo:
new Date().setMilliseconds() 
NaN

28. .setMinutes() 
me dice los minutos de una hora especificada 
ejemplo:
new Date().setMinutes() 
NaN


29.  .setMonth()
establece una hora para una fecha que yo le asigne 
ejemplo: 
new Date().setMonth()
NaN

30. .setSeconds() 
me dice los segundos a una hora especifica que yo le de
ejemplo:
new Date().setSeconds() 
NaN

31. .setTime()
Establece el objeto Date al tiempo representado por un número de milisegundos desde el 1 de Enero de 1970, 00:00:00 UTC. Usa números negativos para fechas previas.
ejemplo:
new Date().setTime()
NaN

32. .setUTCDate() 
me dice el dia del mes y la fecha que yo le diga 
ejemplo: 
new Date().setUTCDate()
NaN

33. .setUTCFullYear()
me dice el año completo
ejemplo:
new Date().setUTCFullYear()
NaN

34. .setUTCHours()
yo le digo la hora para una fecha que yo elija 
ejemplo:
new Date().setUTCHours()
NaN

35. .setUTCMilliseconds()
me dice los milisegundos para una fecha especificada
ejemplo:
new Date().setUTCMilliseconds()
NaN


36. .setUTCMinutes()
me dice los minutos que yo le indique a una hora que yo quiera
ejemplo:
new Date().setUTCMinutes()
NaN


37. .setUTCMonth()
me dice el mes para una hora especifica 
ejemplo:
new Date().setUTCMonth()
NaN


38.  .setUTCSeconds() 
me dice los segundos de una fecha espoecificada
new Date().setUTCSeconds()
NaN


39. .setYear() 
establece el año para una fecha que yo le indique
ejemplo:
new Date().setYear()
NaN

40. .toDateString()
me dice el dias en ingles el mes el numero de dia y el año 
ejemplo:
new Date().toDateString()
'Tue Feb 13 2024'

41. .toISOString()
me dsa una fecha en cadena iso 
ejemplo:
new Date().toISOString()
'2024-02-13T11:10:18.550Z'

42. .toJSON()
me idce la fecha representaado a un objeto
ejemplo:
new Date().toJSON()
'2024-02-13T11:13:04.517Z'

43. .toGMTString()
me retorna una cadena representado un objeto basado en la zona horaria GMT
ejemplo:
new Date().toGMTString()
'Tue, 13 Feb 2024 11:15:45 GMT'

44. .toLocaleDateString()
me regala el dia , la fecha del mes y el año
ejemplo:
new Date().toLocaleDateString()
'13/2/2024'

45. .toLocaleString()
me indica la fecha y la hora 
ejemplo:
new Date().toLocaleString()
'13/2/2024, 6:25:12'

46. .toLocaleTimeString()
me dice la hora los mkinutos y los segundoa en los que me encuentro 
ejemplo:
new Date().toLocaleTimeString()
'6:26:22'


47. .toString()
me dice el dia en ingles el mes el dia en numero el año la hora con minutos y segundos GMT y me dice que es la hora estandar de colombia
ejemplo:
new Date().toString()
'Tue Feb 13 2024 06:27:35 GMT-0500 (hora estándar de Colombia)'


48. .toTimeString()
me dice la hora con minutos y segundos y me dice de donde es esa hora ejemplo yo estoy en colombia 
ejemplo:
new Date().toTimeString()
'06:29:34 GMT-0500 (hora estándar de Colombia)'


48. .toUTCString()
me dice el dia de la semana en ingles el dia de el mes me dice el mes me dice el año , me dice la hora con minutos y segundos GMT
ejemplo:
new Date().toUTCString()
'Tue, 13 Feb 2024 11:31:04 GMT'


49. .valueOf()
me retorna un valor de un objeto primitivo
ejemplo: 
new Date().valueOf()
1707824002991


ACA DEJO UNOS EJEMPLOS DE DONDE INVESTIGUE QUE ES LA SIGUIENTE PAGINA:

https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Date

OBTENER FECHA, MES Y AÑO U HORA

const date = new Date();
const [month, day, year] = [
  date.getMonth(),
  date.getDate(),
  date.getFullYear(),
];
const [hour, minutes, seconds] = [
  date.getHours(),
  date.getMinutes(),
  date.getSeconds(),
];

CALCULANDO TIEMPO TRANSCURRIDO

// Usando objetos Date
let start = Date.now();

// El tiempo a expresar va aquí:
doSomethingForALongTime();
let end = Date.now();
let elapsed = end - start; // tiempo transcurrido en milisegundos



// Usando métodos internos
let start = new Date();

// El tiempo a expresar va aquí:
doSomethingForALongTime();
let end = new Date();
let elapsed = end.getTime() - start.getTime(); // tiempo transcurrido en milisegundos


// Probar una función y regresar su valor
function printElapsedTime(fTest) {
  let nStartTime = Date.now(),
    vReturn = fTest(),
    nEndTime = Date.now();

  console.log(
    `Tiempo transcurrido: ${String(nEndTime - nStartTime)} milisegundos`,
  );
  return vReturn;
}

let yourFunctionReturn = printElapsedTime(yourFunction);



MUCHAS GRACIAS :)
