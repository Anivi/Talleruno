# Descripción del UML del taller uno - Diseñando con algoritmos

# Main
## Atributos
- **Logica log:** Aquí inicializo la logica.
## Metodos
- **Settings():void:** Se usa para definir el tamaño el lienzo.
- **setUp():void:** Aquí se define lo que se ejecuta al iniciar el codigo.
- **keyPressed():void:** Este permitira la realización de las acciones usando el teclado.
- **mouseReleased():void:** Este permitira la realización de las acciones usando el mouse.

# Logica
## Atributos
- **LinkedList <Elementos>:** Se usará para realizar una lista de elementos.
- **Elementos Temp:** Mantiene un objeto de elementos para realizar una acción.
    
## Metodos
- **pintar():void:** Se usará para pintar lo elementos
- **teclado():void:** Se usará para poder usar el teclado
- **mouse():void:** Se usará para poder usar el mouse
- **generador()void:** Crea elementos
- **ordena():void:** Ordena los elementos
    
# Elemento
## Atributos
- **colur:int:** Le dará color a mis elementos
- **tam:int:** Le dará tamaño a mis elementos
- **pos:Pvector:** Le dará la posición y coordenadas a mis elementos
- **z:int:** Se usará para dar un efecto de profundidad a los objetos
- **vel1:int:** Se usará para la velocidad
- **vel2:int:** Se usará para la velocidad
## Metodos
- **pintar():void:** Se usará para pintar los elementos
- **actualizar():void:** Se usará para modificar las coordenadas de X y Y según Z

# Tierra
## Metodos
- **pintar():void:** Se usará para pintar los elementos tierra
- **mover():void:** Se usará para mover los elementos
- **actualizar():void:** Se usará para modificar las coordenadas de X y Y según Z

# Fuego
## Metodos
- **pintar():void:** Se usará para pintar los elementos fuego
- **mover():void:** Se usará para mover los elementos
- **actualizar():void:** Se usará para modificar las coordenadas de X y Y según Z

# Agua
## Metodos
- **pintar():void:** Se usará para pintar los elementos agua
- **mover():void:** Se usará para mover los elementos
- **actualizar():void:** Se usará para modificar las coordenadas de X y Y según Z

# Aire
## Metodos
- **pintar():void:** Se usará para pintar los elementos aire
- **mover():void:** Se usará para mover los elementos
- **actualizar():void:** Se usará para modificar las coordenadas de X y Y según Z

# CompararTamaño
## Metodos
- **compare(elemento1,elemento2):int:** Compara dos objetos en el arreglo de elementos
    