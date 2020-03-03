# Destructuring and Spread

## Destructuring

```javascript
const empleado = {
    "employee": {
        "name": "sonoo",
        "salary": 56000,
        "married": true
    }
}
```

1. Extraer y/o renombrar lo siquiente
   1. employee -> empleado
   2. name -> nombre
   3. married -> gafas

2. Crear un objeto nuevo con las propiedades extraidas

-------------------------------------------------------------------------------

```javascript
const premios = [
    'oro',
    'sexy mashote',
    5,
    3,
    'po haber estudiao',
    1,
    { nombre: 'Director de cine master of the universe'}
];
```

1. Extrae los elementos tipo _string_
2. Extrae los elementos tipo _number_
3. Extrae los elementos tipo _objet_
4. Crea un array por cada tipo

-------------------------------------------------------------------------------

```javascript
const empleados = [
    {"name":"Shyam", "email":"shyamjaiswal@gmail.com"},
    {"name":"Bob", "email":"bob32@gmail.com"},
    {"name":"Jai", "email":"jai87@gmail.com"}
]
```

1. Extrae el empleado Bob _completo_
2. Extrae el _email_ del empleado Bob

-------------------------------------------------------------------------------

Convierte esto:

```javascript
const soyJujel = {
  "markers": [
    {
      "name": "Rixos The Palm Dubai",
      "position": [25.1212, 55.1535],
    },
    {
      "name": "Shangri-La Hotel",
      "location": [25.2084, 55.2719]
    },
    {
      "name": "Grand Hyatt",
      "location": [25.2285, 55.3273]
    }
  ]
}
```

...en esto:

```javascript
const soyOtro = [
  {
    "nombre": "Rixos The Palm Dubai",
    "posicion": {x: 25.1212, y: 55.1535},
  },
  {
    "nombre": "Shangri-La Hotel",
    "posicion": { x: 25.2084, y: 55.2719}
  },
  {
    "nombre": "Grand Hyatt",
    "posicion": { x: 25.2285, y: 55.3273}
  }
]
```
