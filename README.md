# PR_LAB8_PROGRAMACION2_MERGELISTS
**Autor:** Luis Bravo  
**Curso:** 2017–2018  
**Asignatura:** Programación II — Laboratorio 8 (A.E.D.)

## Descripción
Implementación recursiva del método `mergeLists`, cuyo objetivo es fusionar una lista de listas de enteros ordenados en una única lista ordenada sin duplicados.  

## Restricciones
- No se permiten bucles ni iteradores.  
- Se deben usar llamadas recursivas.  
- No se permite modificar el parámetro `listOfLists`.

## Ejemplo
```java
mergeLists([[3],[1,1,1],[],[2]]) // → [1,2,3]
```

## Archivos incluidos
- `MergeLists.java` — Implementación principal.
- `Tester.java` — Casos de prueba.
- `guia.pdf` — Guía oficial del laboratorio.
- `Makefile`, `.project`, `.classpath`, `pom.xml`.

## Ejecución
```bash
javac -cp .:aedlibraries.jar MergeLists.java Tester.java
java -cp .:aedlibraries.jar Tester
```

## Autor
— *Luis Bravo*
