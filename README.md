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
Catholic Monarchs, also called Catholic Kings, or Catholic Majesties, Spanish Reyes Católicos, Ferdinand II of Aragon and Isabella I of Castile
{% validation %}
/
  (Catholic\s+Monarchs)            |
  (Catholic\s+Kings)               |
  (Catholic\s+Majesties)           |
  ((Spanish)?\s+Reyes\s+Católicos) |
  (Ferdinand(\s+II)?(\s+of\s+Aragon)?(\s+and)?(\s+Isabella)(\s+I)?(\s+of\s+Castill?e)) |
  ((Isabella)(\s+I)?(\s+of\s+Castill?e)(\s+and)?\s+(Ferdinand(\s+II)?(of\s+Aragon)))?
/ix
{% editor %}
Placeholder text on editor
{% endregexp %}
