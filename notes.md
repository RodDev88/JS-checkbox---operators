DIFERENCIA ENTRE

opt1 = document.querySelector('#opt1').checked
opt2 = document.querySelector('#opt2').checked

y :

opt1 = document.querySelector('#opt1').value
opt2 = document.querySelector('#opt2').value

---

Propiedad: .checked

---

-Aplica específicamente a elementos de tipo <input> con atributo type="checkbox" o type="radio".

-Devuelve un valor booleano (true o false):
true: Si el checkbox o radio está seleccionado.
false: Si no lo está.
-Uso común: Saber si una opción está marcada.

---

Propiedad: .value

---

-Aplica a muchos tipos de elementos de formulario (<input>, <textarea>, <select>, etc.).
-Devuelve un valor de tipo string que representa lo que contiene el campo de entrada:
-Para <input type="text">, devuelve el texto ingresado.
-Para <input type="checkbox"> o <input type="radio">, devuelve el valor del atributo value (que puedes definir en el HTML), pero no indica si está seleccionado o no.
-Uso común: Obtener el contenido o valor asignado al elemento.
