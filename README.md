# Introduction

Introduccion del libro

### Titulo 1

Texto del titulo 1

### Titulo 2

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


{% questionjs %}
¿Quienes reinaban en España cuando se descubrió America?
{% solution %}
reyes catolicos
{% validation %}
function(respuesta) {
  if (respuesta.match(/reyes\s+catolicos/i)) return true;
  if (respuesta.match(/isabel/i && respuesta.match(/fernando/i) )) return true;
}
{% endquestionjs %}
