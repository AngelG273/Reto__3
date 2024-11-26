# Reto__3

## Hallar los numeros primos hasta n

Los pasos que se deben seguir son los siguinetes:

```pseudocode
# Deternminar el tipo los valores
  a : numeros enteros <= n
  b : entero
  n : entero

Inicio
  a:= enteros <= n 
  n:= 10
  b:= entero distinto de a y 1
    Mientras (a<=n) hacer
      Si modulo(a/b) es == 0 entonces
        escribir ("no es primo")
      sino
        escribir ("es primo")
    Fin mientras
  Escribir los numeros que cumplan el no
Fin
```

## Los pasos en un diagrama de flujo son los siguientes
```mermaid
flowchart TD
    A[Inicio] -->C(numero n)
    C --> B[Numero a entero <= n]
    B --> D[Numero b diferente de a y 1]
    D --> F{residuo de a/b es 0?}
    F --> |SI| G[No es primo]
    F --> |NO| H[Es primo]
    G --> E
    H --> E[Entonces]
    E --> K(Escribir los numeros que cumplan la condicion no)
    K --> J[Fin]
