# 1. Funcion print()
"Elimina las comillas dobles y ejecuta tu código. Mira la reacción de Python. ¿Qué tipo de error arroja?"
La terminal arroja un error de sintaxis (invalid syntax) y nos especifica la linea donde esta el error.
<img width="1319" height="271" alt="Captura de pantalla 2026-04-22 190146" src="https://github.com/user-attachments/assets/2e3fe729-b26f-4f6d-b341-3dfa8da778b9" />

"Luego, elimina los paréntesis, vuelve a colocar las comillas dobles y ejecuta tu código nuevamente. ¿Qué tipo de error arroja esta vez?"
Nos aparece otro error de sintaxis pero en este caso nos dice que hacen falta esos parentesis para poder usar la funcion print.
<img width="1514" height="402" alt="Captura de pantalla 2026-04-22 190355" src="https://github.com/user-attachments/assets/b84ff7ea-3e60-4b48-bdc4-9f35dcc702b2" />

"Experimenta todo lo que puedas. Cambia las comillas dobles a comillas simples, usa múltiples funciones print() en la misma línea, y luego en diferentes líneas. Mira qué pasa."

Al momento de usar comillas simples (' ') el codigo se ejecuta sin problemas.
<img width="1126" height="545" alt="Captura de pantalla 2026-04-22 190640" src="https://github.com/user-attachments/assets/911598fc-6dc7-4c56-8c0a-d40048d43e4a" />

Cuando usamos multiples print en la misma linea ocurre un error de sintaxis.
<img width="1400" height="833" alt="Captura de pantalla 2026-04-22 190722" src="https://github.com/user-attachments/assets/168db229-d356-4e38-a8c4-8696de0f0a6c" />

Pero cuando usamos multiples print en diferentes lineas se ejecuta sin problemas aunque el texto sea igual.
<img width="548" height="221" alt="Captura de pantalla 2026-04-22 190749" src="https://github.com/user-attachments/assets/9aec5886-bfe4-47de-9536-7e286f53c8f3" />

# 2. Print() y sus argumentos

Pude obtener la salida esperada del laboratorio usando los argumentos sep="***" y end="..."

# 3. Dando formato a la salida
- minimizar el número de invocaciones de la función **`print()`** insertando **`\n`** en las cadenas;

- hacer que la flecha sea el doble de grande (pero mantener las proporciones)
- duplica la flecha, colocando ambas flechas una al lado de la otra; nota: una cadena se puede multiplicar usando el siguiente truco: **`"string" * 2`** producirá **`"stringstring"`** (pronto contaremos más al respecto)

- elimina cualquiera de las comillas y observe detenidamente la respuesta de Python; presta atención a dónde Python ve un error - ¿es este el lugar donde realmente existe el error?

- haz lo mismo con algunos de los paréntesis;

- cambia cualquiera de las palabras **`print`** por otra cosa, que difiera solo en mayúsculas y minúsculas (por ejemplo, **`Print`**) - qué sucede ahora?

- reemplaza algunas de las comillas con apóstrofes; observa lo que sucede con cuidado.

# 4. Literales de Python - Cadenas
<img width="1165" height="816" alt="Captura de pantalla 2026-04-22 194919" src="https://github.com/user-attachments/assets/8d2fdd6b-4273-4690-9715-8463f00de794" />
<img width="437" height="842" alt="Captura de pantalla 2026-04-22 195954" src="https://github.com/user-attachments/assets/0506eb75-a3c8-47d3-be9d-d838bba0fb37" />
<img width="317" height="855" alt="Captura de pantalla 2026-04-22 200414" src="https://github.com/user-attachments/assets/efa73236-a562-44b2-a842-4757cc27a0a4" />
<img width="1398" height="735" alt="Captura de pantalla 2026-04-22 200546" src="https://github.com/user-attachments/assets/c944ff80-eb7c-4710-8b40-3595cd39a9b4" />
<img width="1516" height="732" alt="Captura de pantalla 2026-04-22 200610" src="https://github.com/user-attachments/assets/04108d7c-b176-44af-8e58-af5c78211781" />
<img width="380" height="835" alt="Captura de pantalla 2026-04-22 200711" src="https://github.com/user-attachments/assets/bf36dd0c-0962-4de9-b8ea-11f6a1f289e6" />
<img width="415" height="829" alt="Captura de pantalla 2026-04-22 201025" src="https://github.com/user-attachments/assets/ba03d76b-089c-4e89-987a-03328fac08d1" />


# 5. Ejercicios de Operadores, Matematicos

### Ejercicio 1

**Expresión:**

`5 + 3 * 2`

- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?

### Solucion y Explicacion

**Expresión:**

`5 + 3 * 2`

**Paso a paso:**

1. **Identificar las operaciones y su prioridad:**
    - Suma (`+`)
    - Multiplicación ()
    
    La multiplicación tiene mayor prioridad que la suma.
    
2. **Realizar la multiplicación primero:**
    - `3 * 2 = 6`
3. **Realizar la suma:**
    - `5 + 6 = 11`

**Resultado final:**

`11`

---

### Ejercicio 2
 
**Expresión:**
`8 / 2 + 4 * 3`
 
- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?
### Solución y Explicación
 
**Expresión:**
`8 / 2 + 4 * 3`
 
**Paso a paso:**
 
1. **Identificar las operaciones y su prioridad:**
   - División (`/`)
   - Multiplicación (`*`)
   - Suma (`+`)
   División y multiplicación tienen la misma prioridad, y mayor que la suma. Cuando dos operadores tienen la misma prioridad, Python los evalúa de **izquierda a derecha**.
2. **Realizar la división primero (está más a la izquierda):**
   - `8 / 2 = 4.0` *(en Python, `/` siempre devuelve float)*
3. **Realizar la multiplicación:**
   - `4 * 3 = 12`
4. **Realizar la suma:**
   - `4.0 + 12 = 16.0`
**Resultado final:**
`16.0`
 
---
 
### Ejercicio 3
 
**Expresión:**
`(7 + 3) * 2 - 5`
 
- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?
### Solución y Explicación
 
**Expresión:**
`(7 + 3) * 2 - 5`
 
**Paso a paso:**
 
1. **Identificar las operaciones y su prioridad:**
   - Paréntesis (`()`)
   - Multiplicación (`*`)
   - Resta (`-`)
   Los paréntesis tienen la mayor prioridad de todas.
2. **Resolver el paréntesis:**
   - `7 + 3 = 10`
3. **Realizar la multiplicación:**
   - `10 * 2 = 20`
4. **Realizar la resta:**
   - `20 - 5 = 15`
**Resultado final:**
`15`
 
---
 
### Ejercicio 4
 
**Expresión:**
`10 - 4 + 2 * 3`
 
- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?
### Solución y Explicación
 
**Expresión:**
`10 - 4 + 2 * 3`
 
**Paso a paso:**
 
1. **Identificar las operaciones y su prioridad:**
   - Multiplicación (`*`)
   - Resta (`-`) y Suma (`+`)
   La multiplicación va primero. Resta y suma tienen la misma prioridad, se evalúan de izquierda a derecha.
2. **Realizar la multiplicación:**
   - `2 * 3 = 6`
3. **Resolver de izquierda a derecha:**
   - `10 - 4 = 6`
   - `6 + 6 = 12`
**Resultado final:**
`12`
 
---
 
### Ejercicio 5
 
**Expresión:**
`(10 / 2) * (3 + 2) - 4`
 
- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?
### Solución y Explicación
 
**Expresión:**
`(10 / 2) * (3 + 2) - 4`
 
**Paso a paso:**
 
1. **Identificar las operaciones y su prioridad:**
   - Paréntesis (`()`)
   - Multiplicación (`*`)
   - Resta (`-`)
2. **Resolver los paréntesis (de izquierda a derecha):**
   - `10 / 2 = 5.0`
   - `3 + 2 = 5`
3. **Realizar la multiplicación:**
   - `5.0 * 5 = 25.0`
4. **Realizar la resta:**
   - `25.0 - 4 = 21.0`
**Resultado final:**
`21.0`
 
---
 
### Ejercicio 6
 
**Expresión:**
`2 + 3 * (4 - 1)`
 
- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?
### Solución y Explicación
 
**Expresión:**
`2 + 3 * (4 - 1)`
 
**Paso a paso:**
 
1. **Identificar las operaciones y su prioridad:**
   - Paréntesis (`()`)
   - Multiplicación (`*`)
   - Suma (`+`)
2. **Resolver el paréntesis:**
   - `4 - 1 = 3`
3. **Realizar la multiplicación:**
   - `3 * 3 = 9`
4. **Realizar la suma:**
   - `2 + 9 = 11`
**Resultado final:**
`11`
 
---
 
### Ejercicio 7
 
**Expresión:**
`5 * 2 ** 3`
 
- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?
### Solución y Explicación
 
**Expresión:**
`5 * 2 ** 3`
 
**Paso a paso:**
 
1. **Identificar las operaciones y su prioridad:**
   - Potencia (`**`)
   - Multiplicación (`*`)
   La potencia tiene mayor prioridad que la multiplicación. Es el operador con mayor precedencia entre los aritméticos.
2. **Realizar la potencia:**
   - `2 ** 3 = 8`
3. **Realizar la multiplicación:**
   - `5 * 8 = 40`
**Resultado final:**
`40`
 
---
 
### Ejercicio 8
 
**Expresión:**
`6 + 4 / 2 ** 2`
 
- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?
### Solución y Explicación
 
**Expresión:**
`6 + 4 / 2 ** 2`
 
**Paso a paso:**
 
1. **Identificar las operaciones y su prioridad:**
   - Potencia (`**`) — mayor prioridad
   - División (`/`)
   - Suma (`+`)
2. **Realizar la potencia:**
   - `2 ** 2 = 4`
3. **Realizar la división:**
   - `4 / 4 = 1.0`
4. **Realizar la suma:**
   - `6 + 1.0 = 7.0`
**Resultado final:**
`7.0`
 
---
 
### Ejercicio 9
 
**Expresión:**
`10 % 3 + 2 * 5`
 
- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?
### Solución y Explicación
 
**Expresión:**
`10 % 3 + 2 * 5`
 
**Paso a paso:**
 
1. **Identificar las operaciones y su prioridad:**
   - Módulo (`%`) y Multiplicación (`*`) — misma prioridad, mayor que la suma
   - Suma (`+`)
   El operador `%` devuelve el **residuo** de una división entera.
2. **Resolver módulo y multiplicación de izquierda a derecha:**
   - `10 % 3 = 1` *(10 dividido entre 3 es 3 con residuo 1)*
   - `2 * 5 = 10`
3. **Realizar la suma:**
   - `1 + 10 = 11`
**Resultado final:**
`11`
 
---
 
### Ejercicio 10
 
**Expresión:**
`(8 + 2) * 3 ** 2`
 
- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?
### Solución y Explicación
 
**Expresión:**
`(8 + 2) * 3 ** 2`
 
**Paso a paso:**
 
1. **Identificar las operaciones y su prioridad:**
   - Paréntesis (`()`)
   - Potencia (`**`)
   - Multiplicación (`*`)
2. **Resolver el paréntesis:**
   - `8 + 2 = 10`
3. **Realizar la potencia:**
   - `3 ** 2 = 9`
4. **Realizar la multiplicación:**
   - `10 * 9 = 90`
**Resultado final:**
`90`
 
---
 
### Ejercicio 11
 
**Expresión:**
`7 + 2 * (3 + 5) / 4`
 
- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?
### Solución y Explicación
 
**Expresión:**
`7 + 2 * (3 + 5) / 4`
 
**Paso a paso:**
 
1. **Identificar las operaciones y su prioridad:**
   - Paréntesis (`()`)
   - Multiplicación (`*`) y División (`/`) — misma prioridad
   - Suma (`+`)
2. **Resolver el paréntesis:**
   - `3 + 5 = 8`
3. **Resolver multiplicación y división de izquierda a derecha:**
   - `2 * 8 = 16`
   - `16 / 4 = 4.0`
4. **Realizar la suma:**
   - `7 + 4.0 = 11.0`
**Resultado final:**
`11.0`
 
---
 
### Ejercicio 12
 
**Expresión:**
`2 ** 3 * 4 / 2`
 
- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?
### Solución y Explicación
 
**Expresión:**
`2 ** 3 * 4 / 2`
 
**Paso a paso:**
 
1. **Identificar las operaciones y su prioridad:**
   - Potencia (`**`)
   - Multiplicación (`*`) y División (`/`) — misma prioridad, izquierda a derecha
2. **Realizar la potencia:**
   - `2 ** 3 = 8`
3. **Resolver multiplicación y división de izquierda a derecha:**
   - `8 * 4 = 32`
   - `32 / 2 = 16.0`
**Resultado final:**
`16.0`
 
---
 
### Ejercicio 13
 
**Expresión:**
`9 - 6 + 3 ** 2`
 
- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?
### Solución y Explicación
 
**Expresión:**
`9 - 6 + 3 ** 2`
 
**Paso a paso:**
 
1. **Identificar las operaciones y su prioridad:**
   - Potencia (`**`)
   - Resta (`-`) y Suma (`+`) — misma prioridad, izquierda a derecha
2. **Realizar la potencia:**
   - `3 ** 2 = 9`
3. **Resolver resta y suma de izquierda a derecha:**
   - `9 - 6 = 3`
   - `3 + 9 = 12`
**Resultado final:**
`12`
 
---
 
### Ejercicio 14
 
**Expresión:**
`(7 - 2) * 5 + 3 ** 2`
 
- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?
### Solución y Explicación
 
**Expresión:**
`(7 - 2) * 5 + 3 ** 2`
 
**Paso a paso:**
 
1. **Identificar las operaciones y su prioridad:**
   - Paréntesis (`()`)
   - Potencia (`**`)
   - Multiplicación (`*`)
   - Suma (`+`)
2. **Resolver el paréntesis:**
   - `7 - 2 = 5`
3. **Realizar la potencia:**
   - `3 ** 2 = 9`
4. **Realizar la multiplicación:**
   - `5 * 5 = 25`
5. **Realizar la suma:**
   - `25 + 9 = 34`
**Resultado final:**
`34`
 
---
 
### Ejercicio 15
 
**Expresión:**
`4 * 2 ** 3 / 8 + 1`
 
- **Pregunta:** ¿Cuál es el resultado? ¿Por qué?
### Solución y Explicación
 
**Expresión:**
`4 * 2 ** 3 / 8 + 1`
 
**Paso a paso:**
 
1. **Identificar las operaciones y su prioridad:**
   - Potencia (`**`)
   - Multiplicación (`*`) y División (`/`) — misma prioridad, izquierda a derecha
   - Suma (`+`)
2. **Realizar la potencia:**
   - `2 ** 3 = 8`
3. **Resolver multiplicación y división de izquierda a derecha:**
   - `4 * 8 = 32`
   - `32 / 8 = 4.0`
4. **Realizar la suma:**
   - `4.0 + 1 = 5.0`
**Resultado final:**
`5.0`


# 6. Variables

<img width="940" height="442" alt="Screenshot 2026-04-23 143258" src="https://github.com/user-attachments/assets/289716a3-ad52-4bbb-937a-76bca08a4c43" />
<img width="1026" height="353" alt="Screenshot 2026-04-23 145455" src="https://github.com/user-attachments/assets/b591a48e-080d-4a1e-8376-7181a3dc6c90" />
<img width="430" height="578" alt="Screenshot 2026-04-23 150914" src="https://github.com/user-attachments/assets/0c4405ca-916f-4132-966e-811b234d3d2b" />

# 7. Variables: un convertidor simple
<img width="773" height="550" alt="Screenshot 2026-04-23 170003" src="https://github.com/user-attachments/assets/16a97f62-48a8-4fcb-8f48-0107f0cf88da" />
<img width="793" height="440" alt="Screenshot 2026-04-23 170523" src="https://github.com/user-attachments/assets/10b512ed-5f29-4a55-9d0c-c12035fc3bf8" />

# 8. Operadores y expresiones
<img width="791" height="529" alt="Screenshot 2026-04-23 172156" src="https://github.com/user-attachments/assets/ccf341eb-aa45-42e5-ad0c-192cf919aed2" />

# 9. Puntaje final jugador
<img width="713" height="376" alt="Screenshot 2026-04-23 181243" src="https://github.com/user-attachments/assets/3d546502-d243-469f-a928-a5b918ae1bc9" />










