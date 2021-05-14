# PC #1
**course:** Programación Orientada a Objetos I  
**unit:** Unidad 1, 2 y 3  
**cmake project:** poo1_PC1_lab106_v2021_1
## Indicaciones Especificas
- El tiempo límite para la evaluación es 100 minutos.
- Cada pregunta deberá ser respondida en un archivo fuente (`.cpp`) y un archivo cabecera (`.h`) con el número de la pregunta:
  - `p1.cpp, p1.h`
  - `p2.cpp, p2.h`
  - `p3.cpp, p3.h`
- Deberás subir estos archivos directamente a [www.gradescope.com](https://www.gradescope.com) o se puede crear un `.zip` que contenga todos ellos y subirlo.

## Competencias
- Para los alumnos de la carrera de Ciencia de la Computación 
  - Aplica conocimientos de computación  apropiados para la solución de  problemas definidos y sus requerimientos en la disciplina del programa.(nivel 2)
  - Diseña, implementa y evalúa soluciones a problemas complejos de computación.(nivel 2)
  - Crea, selecciona, adapta y aplica técnicas, recursos y herramientas modernas para la práctica de la computación y comprende sus limitaciones.(nivel 2)

- Para los alumnos de las carreras de Ingeniería
  - Capacidad para aplicar conocimientos de matemática.(nivel 2)
  - Capacidad para diseñar un sistema, un componente o un proceso para satisfacer las necesidades deseadas dentro de restricciones realistas(nivel 2)

## Question #1 - Emparejando dígitos (7 points)

Escribir un programa que permita lea un texto que solo incluirá caracteres numéricos `('0','1','2','3','4','5','6','7','8','9')` debera ubicar el dígito dentro del texto de mayor valor luego de ellos debe calcula cuanto se debe incrementar cada dígito para que todos tengan el mismo valor del mayor, El programa debera devolver la suma de todos esos incrementos.

#### Input Format

```cpp
12351230
```

#### Constraints

```cpp
- El ingreso de los valores no requiere utilizar etiquetas (std::cout)
```

#### Output Format

```cpp
23
```
#### Ejemplo 1
**Input**
```cpp
103840182920284941
```
**Output**
```cpp
96
```

#### Ejemplo 2
**Input**
```cpp
2363517534326251610
```
**Output**
```cpp
96
```

## Question #2 - El producto más grande (7 ptos)

Escribir un programa y una función y que reciba 2 valores: un texto que solo incluirá caracteres numéricos y un valor numérico entero que represente una cantidad **`d`** de dígitos adyacentes (uno al lado de otro).
El programa deberá buscar y retornar la secuencia de **`d`** dígitos adyacentes de modo que al multiplicar esos dígitos se obtenga el mayor valor posible.

#### Input Format

```cpp
17939491
3
```

#### Constraints

```
- No se requiere validar los valores, 
  se debe asumir que se ingresa correctamente los digitos
- El ingreso de los valores no requiere utilizar etiquetas (std::cout)
```

#### Output Format

```cpp
949
```

#### Ejemplo 1
**Input**
```cpp
1231929102884910282340172843049812920458473191281929282929
5
```
**Output**
```cpp
28849
```

#### Ejemplo 2
**Input**
```cpp
4473629374652174058464758452790484838394219384730585833484545848384583211838173849573848
7
```
**Output**
```cpp
8495738
```

## Question #3 - Reemplazar un caracter (6 points)

Escribir una **función recursiva** cuyo nombre es `reemplazar_caracter` que reciba 3 parámetros el primero del tipo `std::string`, el segundo de tipo `char` que defina el **antiguo carácter** dentro del texto que será reemplazado y el tercero también de tipo `char` que defina el nuevo carácter, la función debe de permitir reemplazar el **antiguo carácter** por el **nuevo carácter**. La función retornará usando el tipo de retorno de la función el texto modificado. 

**NOTA:** El texto original no debe ser modificado 

#### Input Format

```cpp
texto de prueba 
e
-
```

#### Constraints

```cpp
- El ingreso de los valores no requiere utilizar etiquetas (std::cout)
```

#### Output Format

```cpp
texto de prueba 
t-xto d- pru-ba
```
#### Ejemplo 1
**Input**
```cpp
reemplazar un caracter
a
#
```
**Output**
```cpp
reemplazar un caracter
reempl#z#r un c#r#cter
```

#### Ejemplo 2
**Input**
```cpp
15,29,12,14,2,3,11
,
|
```
**Output**
```cpp
15,29,12,14,2,3,11
15|29|12|14|2|3|11
```
