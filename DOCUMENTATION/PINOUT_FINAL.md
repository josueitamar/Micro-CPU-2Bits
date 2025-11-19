# Pinout Final - RP2040 Zero

A continuación se detalla la conexión de cada GPIO de la RP2040 Zero con los componentes del hardware.

Entradas (Botones)
Todos los botones están configurados con resistencia **PULL_UP** interna (se activan con nivel bajo/GND).

| GPIO | Función | Descripción |
| :--- | :--- | :--- |
| **GPIO 0** | Botón 0 | Dígito 0 |
| **GPIO 1** | Botón 1 | Dígito 1 |
| **GPIO 2** | Botón 2 | Dígito 2 |
| **GPIO 3** | Botón 3 | Dígito 3 |
| **GPIO 4** | Botón + | Operación Suma |
| **GPIO 5** | Botón - | Operación Resta |
| **GPIO 6** | Botón = | Ejecutar / Igual |

Salidas (LEDs de Estado)
LEDs monocromáticos para visualizar el ciclo de instrucción y banderas.

| GPIO | Función | Descripción |
| :--- | :--- | :--- |
| **GPIO 7** | LED Fetch | Fase de búsqueda de instrucción |
| **GPIO 8** | LED Decode | Fase de decodificación |
| **GPIO 9** | LED Execute | Fase de ejecución (ALU) |
| **GPIO 10**| LED WriteBack| Fase de escritura de resultado |
| **GPIO 11**| LED Zero | Bandera: El resultado es 0 |
| **GPIO 12**| LED Negative | Bandera: El resultado es negativo |
| **GPIO 16**| NeoPixel | **Overflow:** Se enciende en ROJO si hay desbordamiento |

Salidas (Display 7 Segmentos)
Configurado para Display de **Cátodo Común**.

| GPIO | Segmento |
| :--- | :--- |
| **GPIO 13** | A |
| **GPIO 14** | B |
| **GPIO 15** | C |
| **GPIO 26** | D |
| **GPIO 27** | E |
| **GPIO 28** | F |
| **GPIO 29** | G |
