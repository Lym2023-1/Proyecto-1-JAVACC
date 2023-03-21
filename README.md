# Proyecto 1 - Lenguajes y maquinas

## Integrantes
- Daniel Felipe Diaz Moreno  202210773  d.diazm@uniandes.edu.co
- Nicolás Miguel Murillo Cristancho  202213891 n.murilloc@uniandes.edu.co

Aun en desarrollo.

## Comentarios entrega

### Uso
La carpeta ProyectoJavaCC incluye el parser con el funcionamiento del robot
La carpeta ParserTesterClean incluye el archivo newparser.jj, el cual sirve para ejecutar el parser sin usar el robot


### Decisiones
En el enunciado hay una inconsistencia con: canMoveToThe
Se explica que su sintaxis es de la forma: canMoveToThe: n ,O – where O is one of: front, right, left, or back
Sin embargo, en el ejemplo sale: while : canMovetoThe : 1 , north do
En la implementacion nos basamos en el enunciado
