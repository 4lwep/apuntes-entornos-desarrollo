# Optimización de código Java

La optimización de código busca lograr el el código más eficiente posible sin perjudicar al funcionamiento del programa.
1. [Hendiondez](#hendiondez)
2. [Análisis de código](#análisis-de-código)
    1. [Análisis estático](#1-análisis-estático)
    1. [Análisis dinámico](#2-análisis-dinámico)
3. [Continuous Inspection o Continuous Analysis](#continuous-inspection-o-continuous-analysis)
4. [Refactorización](#refactorización)

## Hendiondez
La Hendiondez o code smell es indica que el código tiene un problema profundo. No un problema de funcionamiento como tal, si no un problema de diseño que puede daar lugar a problemas para entender el código o problemas de escalabilidad

## Análisis de código

El análisis de código sirve para ver el funcionamiento del código fuente

### 1. Análisis estático

El análisis estático de código permite analizar el código antes de ejecutarlo

#### Linters
Los linters son programas que ofrecen la posibilidad de analizar de forma estática el código, algunos ejemplos son:

- `Lint` para C
- `Sonar` para Java
- `JSLint` o `ESLint` para Javascript

### 2. Análisis dinámico

El análisis dínamico sirve para analizar el funcionamiento del programa durante la ejecución

## Continuous Inspection o Continuous Analysis

Esto es la inspección de código y consiste en inspeccionar el código.

Algunos sitios web que ofrecen este servicio son: 

- Scrutinizer
- SonarQube

## Refactorización

La refactorización consiste en inspeccionar el código fuente buscando reestructurarlo de la manera más optimizada posible. Existen diferentes prácticas que se llevan a cabo: 

- Renombrado de variables 
- Pasar código duplicacado a funciones 
- Eliminación de código inalcanzable 
- Eliminación de código redundante 
- Eliminación de código muerto