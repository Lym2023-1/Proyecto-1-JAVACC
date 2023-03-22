# Proyecto 1 - Lenguajes y maquinas

## Integrantes
- Daniel Felipe Diaz Moreno  202210773  d.diazm@uniandes.edu.co
- Nicolás Miguel Murillo Cristancho  202213891 n.murilloc@uniandes.edu.co

Aun en desarrollo.

## Comentarios entrega

### Uso
- La carpeta ProyectoJavaCC incluye el parser con el funcionamiento del robot
- El archivo NuevoParser.jj incluye solo el parser, funciona al introducirse en el esqueleto del tp1


### Decisiones
En el enunciado hay una inconsistencia con: canMoveToThe
Se explica que su sintaxis es de la forma: canMoveToThe: n ,O – where O is one of: front, right, left, or back
Sin embargo, en el ejemplo sale: while : canMovetoThe : 1 , north do
En la implementacion nos basamos en el enunciado
