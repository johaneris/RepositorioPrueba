# Proyecto de Ejemplo en C#

Este es un proyecto de ejemplo creado para fines educativos en una clase de programación. Está desarrollado en C# usando Visual Studio.

## Objetivo

Demostrar el uso de clases, métodos y estructuras básicas en C#.

## Estructura del Proyecto

- `Program.cs`: Contiene el punto de entrada del programa.
- `Persona.cs`: Ejemplo de una clase con propiedades y métodos.

## Ejemplo de Código

```csharp
public class Persona
{
    public string Nombre { get; set; }
    public int Edad { get; set; }

    public void Saludar()
    {
        Console.WriteLine($"Hola, mi nombre es {Nombre} y tengo {Edad} años.");
    }
}
