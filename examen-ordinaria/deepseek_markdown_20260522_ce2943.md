# EXAMEN ORDINARIO - MPO ROBÓTICA

**Módulo:** Robótica  
**Curso:** 1º CFGM SMR  
**Duración:** 1 hora 30 minutos  
**Porcentaje sobre módulo:** 100%

---

## Instrucciones

- Responde en hoja aparte indicando claramente el número de pregunta.
- Parte práctica: utiliza el robot asignado (mBot, Arduino robot, Lego SPIKE o similar).
- Cuando se pida un **dibujo o esquema**, realízalo a mano en tu hoja de respuestas.
- Sube el código al ordenador del profesor si es necesario.

---

## RA1 – Introducción a la robótica y componentes (25 puntos)

### Pregunta 1 (6 puntos)

Define los siguientes conceptos y da un ejemplo práctico en un robot educativo:

- Actuador
- Sensor
- Controlador (placa)

### Pregunta 2 (6 puntos) – PRÁCTICA

Sobre el robot real o una fotografía facilitada por el profesor, identifica:

1. Microcontrolador
2. Motor DC
3. Sensor de ultrasonidos
4. Sensor de línea (infrarrojos)

**Elabora una tabla con dos columnas:** | Componente | Función |

### Pregunta 3 (6 puntos)

Explica brevemente qué mide cada uno de estos sensores y para qué sirven en un robot:

- Sensor ultrasónico HC-SR04
- Sensor de línea TCRT5000
- Sensor de luz (fotorresistor o LDR)

### Pregunta 4 (7 puntos)

**Dibuja a mano** el esquema de conexión básico de un sensor de ultrasonidos HC-SR04 a una placa Arduino (pines VCC, GND, Trig, Echo). Indica claramente cada cable y su pin correspondiente en Arduino (por ejemplo: Trig → pin 9, Echo → pin 10).

---

## RA2 – Programación básica de robots (40 puntos)

### Pregunta 5 (10 puntos)

Escribe en **pseudocódigo** un programa que haga lo siguiente:

1. El robot avanza 2 segundos.
2. Si el sensor ultrasónico detecta un obstáculo a menos de 20 cm:
   - Gira 90 grados a la derecha.
   - Reanuda