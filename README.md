# ejercicio_05

5.- Crear un proyecto Imc ( Índice de masa corporal) que cumpla las siguientes condiciones: Crea una clase Persona, sus atributos son: nombre, edad, peso y altura. No queremos que se accedan directamente a ellos. Piensa que modificador de acceso es el más adecuado, también su tipo. Si quieres añadir algún atributo puedes hacerlo.

Todos los atributos serán valores por defecto según su tipo (0 números, cadena vacía para String, etc.). Se implantaran varios constructores:
  • Un constructor por defecto.
  • Un constructor con el nombre, edad y el resto por defecto.
  • Un constructor con todos los atributos como parámetro. Los métodos que se implementaran son:
    calcularIMC(): calculará si la persona esta en su peso ideal (peso en kg/(altura^2 en m)), si esta fórmula devuelve un valor menor que     20, la función devuelve un -1, si devuelve un número entre 20 y 25 (incluidos), significa que esta por debajo de su peso ideal la           función devuelve un 0 y si devuelve un valor mayor que 25 significa que tiene sobrepeso, la función devuelve un 1. Se recomienda que       uses constantes para devolver estos valores. Sugerencia: Usar Math.pow(double a,doube b). Permite obtener lapotencia de un número.         esMayorDeEdad(): indica si es mayor de edad, devuelve un booleano. toString(): devuelve toda la información del objeto. Métodos set de     cada parámetro.

Ahora, crea una clase ejecutable que haga lo siguiente: Pide por teclado el nombre, la edad, peso y altura. Crea 3 objetos de la clase anterior, el primer objeto obtendrá las anteriores variables pedidas por teclado, el segundo objeto obtendrá todos los anteriores menos el peso y la altura y el último por defecto, para este último utiliza los métodos set para darle a los atributos un valor. Para cada objeto, deberá comprobar si esta en su peso ideal, tiene sobrepeso o por debajo de su peso ideal con un mensaje. Indicar para cada objeto si es mayor de edad. Por último, mostrar la información de cada objeto.
