# Práctica: Latch S-R con Compuertas NOR
**Estudiante:** Guadalupe Jetzemani Granillo Hernandez  

## Descripcion
Diseño, armado y simulación de un Latch S-R básico utilizando compuertas NOR en Logisim para analizar sus estados fundamentales: Set, Reset y Memoria.

## Evidencia del Circuito Animado
*(Para poner tu foto aquí, solo arrastra el archivo de la captura de tu circuito verde desde tu computadora y suéltalo justo debajo de este renglón)*


## Tabla de Resultados (Diagrama de Tiempos)
A continuación se detallan las transiciones obtenidas durante la simulación manual en Logisim:

| R (Input 110) | S (Input 310) | Q (Output 130) | ~Q (Output 290) | Estado del Latch |
| :---: | :---: | :---: | :---: | :---: |
| 1 | 0 | 0 | 1 | **Reset** (Salida Q en 0) |
| 0 | 0 | 0 | 1 | **Memoria** (Mantiene el Reset) |
| 0 | 1 | 1 | 0 | **Set** (Salida Q cambia a 1) |
| 0 | 0 | 1 | 0 | **Memoria** (Mantiene el Set) |

*(Si quieres, también puedes arrastrar aquí la captura de tu ventanita "Table" para que quede como doble evidencia)*<img width="1623" height="553" alt="Captura de pantalla 2026-05-26 005423" src="https://github.com/user-attachments/assets/dec03cec-ee14-4dd6-bedb-e94d50c395d1" />
<img width="1013" height="626" alt="Captura de pantalla 2026-05-26 005029" src="https://github.com/user-attachments/assets/654a664f-30cd-45d2-82f0-2b67dc2b60e7" />
<img width="1415" height="861" alt="Captura de pantalla 2026-05-26 004717" src="https://github.com/user-attachments/assets/73842ef6-8560-4996-8a10-2ccc5c27f236" />
<img width="1719" height="979" alt="Captura de pantalla 2026-05-26 000817" src="https://github.com/user-attachments/assets/de87523b-5034-4b15-b3bc-9911e592fc9f" />
