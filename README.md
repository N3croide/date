#### Obtener el día del mes:

```javascript
const currentDate = new Date();
const dayOfMonth = currentDate.getDate(); // Resultado: Número del día del mes (1-31)
```

#### Obtener el día de la semana:

```javascript
const currentDate = new Date();
const dayOfWeek = currentDate.getDay(); // Resultado: Número del día de la semana (0-6)
```

#### Obtener el mes:

```javascript
const currentDate = new Date();
const month = currentDate.getMonth(); // Resultado: Número del mes (0-11)
```

#### Obtener el año:

```javascript
const currentDate = new Date();
const year = currentDate.getFullYear(); // Resultado: Año completo (por ejemplo, 2022)
```

#### Obtener las horas:

```javascript
const currentDate = new Date();
const hours = currentDate.getHours(); // Resultado: Número de horas (0-23)
```

#### Obtener los minutos:

```javascript
const currentDate = new Date();
const minutes = currentDate.getMinutes(); // Resultado: Número de minutos (0-59)
```

#### Obtener los segundos:

```javascript
const currentDate = new Date();
const seconds = currentDate.getSeconds(); // Resultado: Número de segundos (0-59)
```

#### Obtener los milisegundos:

```javascript
const currentDate = new Date();
const milliseconds = currentDate.getMilliseconds(); // Resultado: Número de milisegundos (0-999)
```

#### Obtener el tiempo en milisegundos:

```javascript
const currentDate = new Date();
const timeInMilliseconds = currentDate.getTime(); // Resultado: Tiempo en milisegundos desde la época (1 de enero de 1970)
```

#### Establecer el día del mes:

```javascript
const currentDate = new Date();
currentDate.setDate(15); // Establece el día del mes a 15
```

#### Establecer el mes:

```javascript
const currentDate = new Date();
currentDate.setMonth(6); // Establece el mes a julio (0-11)
```

#### Establecer el año:

```javascript
const currentDate = new Date();
currentDate.setFullYear(2022); // Establece el año a 2022
```

#### Establecer las horas:

```javascript
const currentDate = new Date();
currentDate.setHours(12, 30, 0); // Establece las horas a las 12:30:00
```

#### Establecer los minutos:

```javascript
const currentDate = new Date();
currentDate.setMinutes(45); // Establece los minutos a 45
```

#### Establecer los segundos:

```javascript
const currentDate = new Date();
currentDate.setSeconds(20); // Establece los segundos a 20
```

#### Establecer los milisegundos:

```javascript
const currentDate = new Date();
currentDate.setMilliseconds(500); // Establece los milisegundos a 500
```

#### Obtener la diferencia horaria con UTC:

```javascript
const currentDate = new Date();
const timezoneOffset = currentDate.getTimezoneOffset(); // Resultado: Diferencia horaria en minutos
```

#### Devolver la fecha y hora como cadena UTC:

```javascript
const currentDate = new Date();
const utcString = currentDate.toUTCString(); // Resultado: Cadena de fecha y hora en formato UTC
```

#### Devolver la fecha y hora como cadena local:

```javascript
const currentDate = new Date();
const localString = currentDate.toLocaleString(); // Resultado: Cadena de fecha y hora en formato local
```

