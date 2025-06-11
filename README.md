## TPO 2 Lenguajes Declarativos: Las Seis Mujeres del Té

Juego web interactivo que combina JavaScript, SWI-Prolog para resolver un puzzle lógico basado en posiciones y características de seis mujeres en una mesa.
Además, se utiliza la librería WASM para la implementación del archivo Prolog en la página web.

---

## Tabla de Contenidos

- [Descripción](#descripción)
- [Problema](#problema)
- [Instalación](#instalación)
- [Tecnologías](#tecnologías)
- [Autores](#autores)

---

## Descripción

Este proyecto web permite arrastrar cartas con nombres y características para colocarlas en asientos (slots), y verificar si la solución cumple con un conjunto de pistas lógicas usando un motor Prolog embebido. También se permite generar soluciones del problema lógico.

## Problema

Una mujer invitó recientemente a tomar el té a cinco personas.  
Los nombres de las seis mujeres que se sentaron alrededor de una mesa circular son:  
**Jane, Ada, Katherine, Marie, Grace y Chien.**

Cada una tiene una característica diferente:

- Una era profesora
- Otra era modesta
- Otra odiaba las polillas
- Otra admiraba a Marie
- Otra era viajera
- Otra era la dueña de casa

Además, se cumplen las siguientes condiciones:

1. La mujer que admiraba a Marie se sentó enfrente de la señora Ada.
2. La mujer que era profesora se sentó enfrente de la señora Katherine.
3. Katherine se sentó entre la mujer que era viajera y la mujer que admiraba a Marie.
4. La mujer que odiaba a las polillas se sentó frente a la señora Jane.
5. La mujer que odiaba a las polillas se sentó junto a la mujer que era profesora y a la izquierda de la que admiraba a Marie.
6. La mujer que era viajera se sentó al lado de la señora Katherine.
7. La mujer viajera se sentó al lado de Ada.
8. Ada se sentó enfrente de la mujer que admiraba a Marie.
9. La señora Chien, que era buena amiga de todas, se sentó junto a la mujer que odiaba las polillas y enfrente de la dueña de casa.

## Instalación

Clonar el repositorio:

```bash
git clone https://github.com/StheyCede/TPO2---Lenguajes-Declarativos.git
```

ejecutar Swi - Prolog dentro del proyecto:

```bash
swipl
```

Finalmente, ejecutar el servidor.

```prolog
    ?- [server].
```

## Tecnologias

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?logo=webassembly&logoColor=white)
![SWI-Prolog](https://img.shields.io/badge/SWI--Prolog-FF0000?logo=prolog&logoColor=white)
![Scryer Prolog](https://img.shields.io/badge/Scryer--Prolog-333333?logo=prolog&logoColor=white)

## Autores

- Cedeño, Sthefany
- Coronel, Paula
- Sarmiento, Antonio
