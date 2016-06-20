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


{% regexp %}
Who were the Spanish kings when America was discovered?
{% solution %}
reyes catolicos
{% validation %}
/
  (reyes\s+catolicos)            |
  (isabel\s+y\s+fernando)               |
/ix
{% editor %}
Placeholder text on editor
{% endregexp %}
