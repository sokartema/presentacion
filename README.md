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


{% question %}
¿Quienes reinaban en España cuando se descubrió America? RUBY
{% solution %}
reyes catolicos
{% validation %}
def exercise(respuesta)

  if(respuesta =~ /reyes\s+catolicos/)

    return true;

  else

    return false;

  end

end
{% language %}
ruby
{% endquestion %}

{% regexp color="red" %}
¿4+4?
{% solution %}
8
{% validation %}
/\s*8\s*/i
{% endregexp %}
