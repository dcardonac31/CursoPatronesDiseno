# Curso Patrones de Diseño en .Net

## Notas curso patrones de diseño dictado en Udemy por Hector De León

## 1. ¿Qué es un patrón de diseño?

Son tecnicas comprobadas que ayudan a resolver problemas comunes en la programación.

### Se dividen en 3 tipos:

- Creacionales:
  Indican como crear los objetos.

- Estructurales:
  Indican como estan los objetos armados.

- Comportamiento:
  Indican como actuan los objetos.
 
Los patrones de diseño ayudan a tener buenas practicas como código limpio, escalabilidad, legibilidad y un camino practico para trabajar en equipo.

## 2. ¿Repaso programación orientada a objetos?

Es un paradigma de programación, una forma de trabajar la programación.

La programación se representa en objetos que tienen propiedades, metodos y funciones.

Yo soy un objeto que estoy en un universo que a su vez es otro objeto, poseo propiedades ojos, piel, cabello, gustos y y tengo funcionalidades como tomar cerveza, conducir carro. Los objetos pueden trabajr en conjunto y gracias a los patrones de diseño se puede hacer trabajar los objetos de una manera mas eficiente.

Una clase es una especificación o una plantilla de como debe ser creado un objeto, por ejemplo persona:

### persona
- nombre
- edad
- nacionalidad

Se puede crear un objeto a partir de la clase persona o de tipo persona.

### Ejemplo en C#

Asi se crea una clase

`public class Persona`  
`{`  
`        public string name;`  
`        public int age;`  
`        public string nationality;`  
`}`  

Asi se crea un objeto instanciadolo de la clase creada

`static void Main(string[] args)`  
`{`  
`        Person andres = new Person("Andres", "34", "Colombiano";`   
`        Console.WriteLine(hector.Show())";`    
`}`  

### Constructor: 
es un metodo para construir la clase y recibe nulo, uno, varios o todos los atributos de la clase

`public Person(string _name, int _age, string _nationality)`  
`{`  
`        name = _name;`  
`        age = _age;`  
`        nationality = _nationality;`  
`}`  

### Metodo:

`public string show()`  
`{`  
`        return name + " " + age + " "_+ nationality;`  
`}`  