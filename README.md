"# bem-css-itcss" 

# Udemy: BEM CSS + ITCSS = Metodología BEMIT - Diseño web Avanzado

URL: https://itauchile.udemy.com/course/bem-css-itcss-metodologia-bemit-diseno-web-avanzado/learn/lecture/12964598#overview

# BEM
## 2. ¿Qué es BEM?
- Es una metodología de nomenclatura para definir las clases del HTML. 
- El objetivo de BEM es dar transparencia y claridad a nuestro HTML y CSS.
- BEM te dice como se relacionan las clases entre ellas.
- Todas las clases del proyecto pueden encajar con esta filosofía.

- BEM son tres siglas 
    * B de Bloque
    * E de Elemento
    * M de Modificador

- Un bloque es una entidad independiente con significado propio. 
- Un elemento es una porción más pequeña de un bloque.
- Un modificador es una clase que sirve para modificar propiedades de un bloque. 

- Se puede dar el caso que existan algunas clases independientes a nuestro sistema BEM en el proyecto, pero no es lo más recomendable.

- Esas clases independientes normalmente serán generadas por plugins de tercero.

## 3. BEM - B de bloque

### B DE BLOQUE

- Entidad independiente con significado propio
- Existen bloques simples y compuestos (bloques dentro de bloques)
- Para nombrar un bloque puedes usar letras, digitos y guiones.
- No puedes usar mayúsculas
- No puedes usar dos guiones bajos seguidos, está reservado para los elementos __ (block__element)
- No puedes usar dos guiones seguidos, está reservado para los modificadores -- (block--modifier)

Ejemplo: bloque.html y bloque.css

Notes:
    - Usar la clase del bloque como selector.

## 4. BEM - E de elemento 
### E DE ELEMENTO

- Segmento de un bloque, no tiene significado independiente por si solo.
- Está ligado a su bloque, tiene que vivir dentro de el.
- Cualquier TAG HTML dentro de un bloque puede ser un elemento.
- Dentro de un bloque, todos sus elementos son iguales semanticamente.
- Para nombrar un elemento puedes usar letras, digitos y guiones.
- No puedes usar mayúsculas
- No puedes usar dos guiones seguidos, está reservado para los modificadores -- (block--modifier)

- La formula para crear nombres de elementos es:

    nombre-de-bloque + dos guiones bajos (__) + nombre-de-elemento

    Es decir:
    block + __ + element

    Es decir:
    block__element => Así es un nombre de elemento
