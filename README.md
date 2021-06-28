# SimpleShuntingYardAlgorithm-Kotlin-Class

Class destined to analyze a string with a mathematical expression that can include +, -, /, *, (,) and numbers of 1 or more digits. The parser executes the operations in the correct arithmetic order, first parentheses, then multiplication and division, and finally addition and subtraction from left to right.

This is a personal challenge that I set myself after receiving the test on CoderByte for a job interview.

More info: https://en.wikipedia.org/wiki/Shunting-yard_algorithm

Clase destinada a analizar una cadena con una expresión matemática que puede incluir +, -, /, *, (,) y números de 1 o más dígitos. El analizador ejecuta las operaciones en el orden aritmético correcto, primero entre paréntesis, luego multiplicación y división, y finalmente suma y resta de izquierda a derecha.

Este es un desafío personal que me planteé después de recibir la prueba en CoderByte para una entrevista de trabajo. 

More info: https://es.wikipedia.org/wiki/Algoritmo_shunting_yard




```kotlin
fun main(){
    val yard = TheShuntingYard()
    println(yard.calculate("(9/9)*9+(5+5+5)/6*44"))
}
```