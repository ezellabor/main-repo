![Convocatoria](https://img.shields.io/badge/Convocatoria-Ordinaria-blue?style=for-the-badge)
![Módulo](https://img.shields.io/badge/Módulo-Informática_aplicada_a_sistemas_electrónicos-brown?style=for-the-badge)
![Grupo](https://img.shields.io/badge/Grupo-ASIR1-brown?style=for-the-badge)
![Duración](https://img.shields.io/badge/Duración-90_minutos?style=for-the-badge)   
![Profesor](https://img.shields.io/badge/Profesor-Ezequiel_Llarena_Borges-blue?style=for-the-badge)

--  
![issue](https://img.shields.io/badge/issue-Arrays_Bidimensionales_(Matrices)-navy?style=for-the-badge)  
```"El Tesoro Escondido"```

# EXAMEN ORDINARIO - MPO ROBÓTICA

**Módulo:** Robótica (MPO)  
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
   - Reanuda la marcha.
3. Si no hay obstáculo, sigue recto.

### Pregunta 6 (18 puntos) – PRÁCTICA

**Programa el robot para realizar un recorrido autónomo siguiendo una línea negra sobre fondo blanco.**

Requisitos:
- Avanza siguiendo la línea durante 1 minuto.
- Al final del recorrido (o si pierde la línea durante 3 segundos), se detiene.
- Emite un pitido de 1 segundo al detenerse.

*Evaluación: funcionamiento correcto + código limpio y comentado.*

### Pregunta 7 (12 puntos)

El siguiente código tiene errores. Identifica al menos **tres errores** y escríbelos corregidos:

```cpp
void setup() {
  pinMode(9, OUTPUT);
  pinMode(10, OUTPUT);
}

void loop() {
  digitalWrite(9, HIGH);
  delay(500);
  digitalWrite(9, LOW);
  digitalWrite(10, LOW);
  delay(500);
}
```

*Objetivo deseado: LED o motor en pin 9 parpadea, pin 10 debe estar alternado (encendido cuando pin 9 apagado).*

---

## RA3 – Mantenimiento y seguridad en robots (20 puntos)

### Pregunta 8 (8 puntos)

Nombra **tres medidas de seguridad obligatorias** al manipular robots con motores y baterías recargables.

¿Qué haces si un motor se sobrecalienta durante una práctica?

### Pregunta 9 (8 puntos) – PRÁCTICA

Realiza el **cambio de batería** del robot educativo siguiendo este protocolo. Anota cada paso:

1. Apagar el robot.
2. Desconectar conector de alimentación.
3. Retirar batería agotada.
4. Insertar batería cargada (mismo tipo y voltaje).
5. Verificar conexión y encendido.

### Pregunta 10 (4 puntos)

¿Cada cuánto tiempo recomiendas limpiar los sensores ópticos de un robot que se usa semanalmente? ¿Con qué producto o herramienta?

---

## RA4 – Proyecto integrador (15 puntos)

### Pregunta 11 (15 puntos)

Diseña un pequeño robot que solucione un problema real del aula. Ejemplos:
- Evitar golpear mesas
- Seguir una cinta hasta una papelera
- Detenerse ante un borde o escalón

**Tu diseño debe incluir (entregar en hoja aparte):**

1. Nombre del proyecto
2. Problema que resuelve
3. Componentes necesarios (mínimo 3)
4. Diagrama de flujo de funcionamiento (dibujo a mano)
5. Dos medidas de seguridad aplicadas

---

# SOLUCIONARIO - MPO ROBÓTICA

## RA1 – Soluciones (25 puntos)

### Solución Pregunta 1 (6 puntos)

| Concepto | Definición | Ejemplo en robot educativo |
|----------|-----------|---------------------------|
| Actuador | Dispositivo que convierte energía eléctrica en movimiento físico | Motor DC que hace girar las ruedas |
| Sensor | Dispositivo que detecta cambios físicos o químicos del entorno | Sensor ultrasónico que mide distancia a obstáculos |
| Controlador (placa) | Circuito electrónico que procesa señales y ejecuta programas | Placa Arduino Uno o mCore (mBot) |

**Criterio:** 2 puntos por cada concepto (1 definición correcta + 1 ejemplo apropiado).

---

### Solución Pregunta 2 (6 puntos) – Práctica

| Componente | Función |
|------------|---------|
| Microcontrolador | Procesa el código almacenado y controla todos los periféricos |
| Motor DC | Convierte energía eléctrica en movimiento rotatorio continuo |
| Sensor de ultrasonidos | Emite ondas sonoras y mide el tiempo de rebote para calcular distancia |
| Sensor de línea (infrarrojos) | Detecta la reflectividad de la superficie (blanco refleja más, negro absorbe) |

**Criterio:** 1,5 puntos por cada componente correctamente identificado + función descrita correctamente.

---

### Solución Pregunta 3 (6 puntos)

| Sensor | Mide | Aplicación en robot |
|--------|------|---------------------|
| HC-SR04 (ultrasónico) | Distancia a objetos entre 2 cm y 400 cm | Evitar obstáculos, aparcamiento autónomo, seguimiento de pared |
| TCRT5000 (línea) | Reflectividad de la superficie (digital: blanco/negro) | Seguir líneas negras sobre fondo blanco o viceversa |
| LDR (fotorresistor) | Intensidad de luz ambiental (valor analógico) | Seguir una linterna, detectar si es de día/noche, activar luces |

**Criterio:** 2 puntos por sensor (1 punto qué mide + 1 punto aplicación).

---

### Solución Pregunta 4 (7 puntos)

El alumno debe dibujar un esquema con los siguientes elementos claramente etiquetados:

**Sensor HC-SR04:**
- Pin VCC
- Pin TRIG
- Pin ECHO
- Pin GND

**Placa Arduino:**
- Pin 5V
- Pin GND
- Pin digital 9 (para TRIG)
- Pin digital 10 (para ECHO)

**Conexiones:**
- VCC del sensor → 5V de Arduino
- GND del sensor → GND de Arduino
- TRIG del sensor → Pin 9 de Arduino
- ECHO del sensor → Pin 10 de Arduino

**Criterio:**
- 2 puntos por identificar correctamente los 4 pines del sensor
- 3 puntos por realizar las 4 conexiones correctas (0,75 puntos cada cable)
- 2 puntos por claridad del dibujo y etiquetado completo

---

## RA2 – Soluciones (40 puntos)

### Solución Pregunta 5 (10 puntos)

**Pseudocódigo modelo:**

```
INICIO
    // Avanzar durante 2 segundos al inicio
    ACTIVAR motor izquierda ADELANTE
    ACTIVAR motor derecha ADELANTE
    ESPERAR 2000 milisegundos
    
    // Bucle principal infinito
    REPETIR
        distancia = LEER sensor ultrasonidos (en cm)
        
        SI distancia < 20 cm ENTONCES
            // Girar 90 grados a la derecha
            ACTIVAR motor izquierda ADELANTE
            ACTIVAR motor derecha ATRAS
            ESPERAR 300 milisegundos (ajustable según robot)
            
            // Reanudar marcha recta
            ACTIVAR motor izquierda ADELANTE
            ACTIVAR motor derecha ADELANTE
        SINO
            // Seguir recto
            ACTIVAR motor izquierda ADELANTE
            ACTIVAR motor derecha ADELANTE
        FIN SI
    FIN REPETIR
FIN
```

**Criterio:**
- 3 puntos: estructura correcta del programa (inicio, pausa inicial, bucle infinito)
- 3 puntos: lectura del sensor y condición de distancia correcta
- 2 puntos: control de motores para avanzar recto
- 2 puntos: control de motores para girar y reanudar marcha

---

### Solución Pregunta 6 (18 puntos) – Práctica

**Código de referencia en Arduino C:**

```cpp
/*
 * Robot seguidor de línea negra sobre fondo blanco
 * Con detención por pérdida de línea y pitido final
 */

// Definición de pines (ajustar según el robot)
#define SENSOR_IZQUIERDO 8
#define SENSOR_DERECHO   7
#define MOTOR_IZQ_A      5
#define MOTOR_IZQ_B      6
#define MOTOR_DER_A      9
#define MOTOR_DER_B      10
#define BUZZER           11

// Variables globales
unsigned long tiempoPerdido = 0;
bool siguiendo = true;
unsigned long tiempoInicio = 0;

void setup() {
  // Configurar pines de sensores como entrada
  pinMode(SENSOR_IZQUIERDO, INPUT);
  pinMode(SENSOR_DERECHO, INPUT);
  
  // Configurar pines de motores como salida
  pinMode(MOTOR_IZQ_A, OUTPUT);
  pinMode(MOTOR_IZQ_B, OUTPUT);
  pinMode(MOTOR_DER_A, OUTPUT);
  pinMode(MOTOR_DER_B, OUTPUT);
  
  // Configurar buzzer como salida
  pinMode(BUZZER, OUTPUT);
  
  // Iniciar temporizador de 1 minuto
  tiempoInicio = millis();
}

// Función: avanzar recto
void avanzar() {
  digitalWrite(MOTOR_IZQ_A, HIGH);
  digitalWrite(MOTOR_IZQ_B, LOW);
  digitalWrite(MOTOR_DER_A, HIGH);
  digitalWrite(MOTOR_DER_B, LOW);
}

// Función: girar izquierda
void girarIzquierda() {
  digitalWrite(MOTOR_IZQ_A, LOW);
  digitalWrite(MOTOR_IZQ_B, HIGH);
  digitalWrite(MOTOR_DER_A, HIGH);
  digitalWrite(MOTOR_DER_B, LOW);
}

// Función: girar derecha
void girarDerecha() {
  digitalWrite(MOTOR_IZQ_A, HIGH);
  digitalWrite(MOTOR_IZQ_B, LOW);
  digitalWrite(MOTOR_DER_A, LOW);
  digitalWrite(MOTOR_DER_B, HIGH);
}

// Función: detener
void detener() {
  digitalWrite(MOTOR_IZQ_A, LOW);
  digitalWrite(MOTOR_IZQ_B, LOW);
  digitalWrite(MOTOR_DER_A, LOW);
  digitalWrite(MOTOR_DER_B, LOW);
}

// Función: emitir pitido
void pitido(int frecuencia, int duracion) {
  tone(BUZZER, frecuencia);
  delay(duracion);
  noTone(BUZZER);
}

void loop() {
  // Si ya se detuvo, no hacer nada
  if (!siguiendo) return;
  
  // Comprobar si ha pasado 1 minuto (60000 ms)
  if (millis() - tiempoInicio > 60000) {
    detener();
    pitido(1000, 1000);  // Pitido de 1 segundo a 1000Hz
    siguiendo = false;
    return;
  }
  
  // Leer sensores de línea
  int izquierdo = digitalRead(SENSOR_IZQUIERDO);
  int derecho = digitalRead(SENSOR_DERECHO);
  
  // Lógica de seguimiento (negro = LOW, blanco = HIGH en muchos sensores)
  if (izquierdo == LOW && derecho == LOW) {
    // Ambos sensores sobre línea negra -> avanzar recto
    avanzar();
    tiempoPerdido = 0;  // Resetear contador de pérdida
  }
  else if (izquierdo == LOW && derecho == HIGH) {
    // Solo izquierdo sobre línea negra -> girar izquierda
    girarIzquierda();
    tiempoPerdido = 0;
  }
  else if (izquierdo == HIGH && derecho == LOW) {
    // Solo derecho sobre línea negra -> girar derecha
    girarDerecha();
    tiempoPerdido = 0;
  }
  else {
    // Ambos sensores sobre blanco -> ha perdido la línea
    if (tiempoPerdido == 0) {
      tiempoPerdido = millis();  // Iniciar contador
    }
    if (millis() - tiempoPerdido > 3000) {
      // Ha perdido la línea durante 3 segundos
      detener();
      pitido(1000, 1000);  // Pitido de 1 segundo
      siguiendo = false;
    }
  }
  
  delay(10);  // Pequeña pausa para estabilidad
}
```

**Rúbrica de evaluación práctica:**

| Criterio | Puntos |
|----------|--------|
| Conexión correcta de los sensores de línea a la placa | 3 |
| Lógica de seguimiento de línea funcional (avanza y corrige) | 5 |
| Detección de pérdida de línea con temporizador de 3 segundos | 3 |
| Detención correcta al perder la línea o cumplirse 1 minuto | 3 |
| Pitido de 1 segundo al detenerse | 2 |
| Código limpio, ordenado y con comentarios | 2 |
| **Total** | **18** |

---

### Solución Pregunta 7 (12 puntos)

**Errores identificados en el código original:**

| Error | Explicación | Corrección |
|-------|-------------|------------|
| 1. Pin 10 nunca se enciende | El código solo escribe LOW en pin 10, nunca HIGH | Añadir digitalWrite(10, HIGH) en algún momento |
| 2. No hay alternancia entre pin 9 y pin 10 | Pin 9 se enciende y apaga, pero pin 10 permanece siempre apagado | Crear un ciclo donde pin 9 y pin 10 se enciendan de forma alternada |
| 3. Falta la mitad del ciclo de alternancia | El código solo tiene dos estados, pero necesitas cuatro acciones (9HIGH/10LOW, delay, 9LOW/10HIGH, delay) | Añadir el estado faltante con pin 9 LOW y pin 10 HIGH |

**Código corregido:**

```cpp
void setup() {
  pinMode(9, OUTPUT);
  pinMode(10, OUTPUT);
}

void loop() {
  // Primer estado: pin 9 encendido, pin 10 apagado
  digitalWrite(9, HIGH);
  digitalWrite(10, LOW);
  delay(500);
  
  // Segundo estado: pin 9 apagado, pin 10 encendido (alternado)
  digitalWrite(9, LOW);
  digitalWrite(10, HIGH);
  delay(500);
}
```

**Otra solución igualmente válida (con variable de estado):**

```cpp
bool estado = false;

void setup() {
  pinMode(9, OUTPUT);
  pinMode(10, OUTPUT);
}

void loop() {
  if (estado) {
    digitalWrite(9, HIGH);
    digitalWrite(10, LOW);
  } else {
    digitalWrite(9, LOW);
    digitalWrite(10, HIGH);
  }
  estado = !estado;  // Alternar estado
  delay(500);
}
```

**Criterio:** 4 puntos por cada error correctamente identificado (2 puntos identificación + 2 puntos corrección). Máximo 12 puntos (3 errores).

---

## RA3 – Soluciones (20 puntos)

### Solución Pregunta 8 (8 puntos)

**Tres medidas de seguridad obligatorias:**

| Medida | Explicación |
|--------|-------------|
| 1. Desconectar la batería antes de cualquier manipulación interna | Evita cortocircuitos, arranques involuntarios del robot y daños por contacto eléctrico |
| 2. No tocar los motores durante el funcionamiento | Los motores pueden alcanzar altas temperaturas (más de 50°C) y tienen partes móviles que pueden atrapar dedos o cables |
| 3. No invertir la polaridad de la batería ni forzar conexiones | Invertir polaridad puede quemar la placa controladora, los drivers de motor y la batería |

**Procedimiento si un motor se sobrecalienta:**

1. **Detener inmediatamente** el robot (apagar con interruptor o desconectar batería).
2. **Desconectar la batería** por completo para evitar alimentación residual.
3. **Dejar enfriar** el motor durante al menos 10-15 minutos sin tocarlo directamente.
4. **Inspeccionar** si hay obstrucción mecánica: rueda atascada, engranaje sucio, cuerpo extraño atrapado, correa desajustada.
5. **Revisar el código** para detectar si se exige un esfuerzo excesivo: por ejemplo, giros forzados contra una pared durante mucho tiempo, o velocidad demasiado alta (PWM alto) durante periodos largos.
6. **Si el sobrecalentamiento persiste** después de solucionar las causas anteriores, el motor podría estar dañado (bobinas en cortocircuito) y debe reemplazarse.

**Criterio:** 
- 3 puntos por las 3 medidas de seguridad (1 punto cada una con explicación clara)
- 5 puntos por el procedimiento completo (1 punto por cada paso correcto)

---

### Solución Pregunta 9 (8 puntos) – Práctica

El alumno debe ejecutar y anotar los siguientes pasos:

| Paso | Acción correcta | Puntos |
|------|----------------|--------|
| 1 | Apagar el robot mediante su interruptor principal (nunca tirar del cable) | 1 |
| 2 | Desconectar el conector de alimentación (tipo JST, barrel jack, XT30, etc.) | 1 |
| 3 | Retirar la batería agotada del compartimento con cuidado (no tirar de los cables) | 1 |
| 4 | Insertar la batería cargada verificando: mismo voltaje nominal (ej. 7.4V, 11.1V o 4xAA 6V), misma polaridad, mismo tipo de conector | 3 |
| 5 | Reconectar el conector de alimentación, encender el robot y verificar funcionamiento (LEDs, movimiento, sensores) | 2 |

**Observaciones adicionales:**
- Si la batería es LiPo (las más comunes en robots educativos), manejar con cuidado: no perforar, no exponer al calor, no dejar descargada completamente.
- La batería agotada debe llevarse al **punto limpio** o contenedor específico de baterías (nunca a la basura general).

**Criterio:** 
- 5 puntos por ejecución correcta de los 5 pasos básicos
- 3 puntos por la verificación adicional de voltaje, polaridad y tipo de conector

---

### Solución Pregunta 10 (4 puntos)

**Frecuencia recomendada de limpieza:**

- **Limpieza preventiva:** Cada **2-4 semanas** si el robot se usa semanalmente en el aula.
- **Limpieza correctiva:** **Inmediatamente** si se detecta mal funcionamiento del sensor (el robot no sigue bien la línea, respuestas erráticas o lentas, no detecta obstáculos).

**Productos y herramientas:**

| Permitido / Recomendado | Prohibido / No usar |
|------------------------|---------------------|
| Paño de microfibra seco | Agua (puede dañar la electrónica y causar cortocircuitos) |
| Bastoncillo de algodón (hisopo) seco o con alcohol isopropílico | Limpiadores multiuso, disolventes, acetona, alcohol de farmacia (contiene agua) |
| Alcohol isopropílico (99%) ligeramente humedecido en el hisopo | Objetos punzantes (destornillador, aguja, pinzas metálicas) |
| Aire comprimido a baja presión (para quitar polvo suelto previamente) | Aire comprimido a alta presión o a corta distancia (puede dañar el LED infrarrojo o desplazar componentes pequeños) |

**Procedimiento correcto:**
1. Apagar el robot y desconectar la batería.
2. Soplar suavemente con aire comprimido a distancia para quitar polvo superficial.
3. Pasar el bastoncillo de algodón seco o ligeramente humedecido con alcohol isopropílico sobre la superficie del sensor (LED emisor y fototransistor/fotorresistor).
4. Movimientos circulares suaves, sin presionar demasiado.
5. Dejar secar completamente (el alcohol isopropílico se evapora rápido) antes de encender.

**Criterio:** 
- 2 puntos por la frecuencia (1 punto preventiva + 1 punto correctiva)
- 2 puntos por los materiales correctos (1 punto lista de permitidos + 1 punto diferenciación de prohibidos)

---

## RA4 – Soluciones (15 puntos)

### Solución Pregunta 11 (15 puntos) – Proyecto integrador

**Ejemplo de solución completa (el alumno puede elegir otro problema similar):**

| Elemento | Contenido del proyecto |
|----------|------------------------|
| **Nombre del proyecto** | "RoboBorde - Protector de caídas para mesas y escaleras" |
| **Problema que resuelve** | En el taller de robótica, los robots educativos sin protección pueden caerse de la mesa de trabajo al no detectar el borde, causando daños en el robot y riesgos para los componentes electrónicos. También puede ocurrir en prácticas en el suelo cerca de escalones o desniveles. |
| **Componentes necesarios** (mínimo 3) | 1. Sensor infrarrojo de proximidad (o sensor ultrasónico con montaje descendente) apuntando hacia el suelo 2. Placa controladora (Arduino Uno/Nano o mCore) 3. Dos motores DC con ruedas 4. Buzzer o LED de alerta (opcional pero recomendado) 5. Chasis y batería |
| **Diagrama de flujo** | El alumno debe dibujar a mano un diagrama con esta lógica: **Inicio → Leer sensor de borde (distancia al suelo) → ¿Distancia mayor a 15 cm? (borde detectado) → Si: retroceder 0.5 segundos → girar 90 grados → avanzar 1 segundo → volver a leer sensor / No: avanzar normalmente → repetir bucle** |
| **Medidas de seguridad aplicadas** | 1. **Sujeción segura de la batería:** La batería debe ir fijada con velcro, bridas o compartimento cerrado para que no se suelte en caso de caída o giro brusco del robot. 2. **Limitación de velocidad máxima:** Configurar la velocidad de los motores a un 30-40% del PWM máximo (ej. analogWrite 128 en lugar de 255) para reducir la energía de impacto si el robot choca contra algo o se cae. 3. (Opcional) **Bordes redondeados** en el chasis impreso o protectores de goma para minimizar daños por impacto. |

**Rúbrica de evaluación del proyecto:**

| Criterio | Puntos máximos | Descripción |
|----------|----------------|-------------|
| Nombre del proyecto y problema bien definidos | 3 | El nombre debe ser original y descriptivo. El problema debe ser real del aula, no inventado ni demasiado genérico. |
| Componentes (mínimo 3) listados correctamente | 3 | Cada componente debe estar claramente identificado y debe ser necesario para la solución propuesta (no añadir componentes irrelevantes). |
| Diagrama de flujo con lógica correcta | 5 | El diagrama debe mostrar: inicio, lectura de sensor, condición (decisión SI/NO), acciones para cada caso, y bucle de repetición. Debe estar bien dibujado y etiquetado. |
| Medidas de seguridad (mínimo 2) adecuadas | 2 | Las medidas deben ser específicas para el problema (ej. "no tocar el robot" es demasiado genérico; "sujetar bien la batería porque puede caerse" sí es específico). |
| Originalidad y viabilidad técnica | 2 | El proyecto debe ser realizable con los materiales disponibles en el taller. No se penaliza si es similar a los ejemplos, pero se valora la adaptación al contexto real del aula. |
| **Total** | **15** | |

**Otros ejemplos de proyectos válidos:**

| Nombre del proyecto | Problema | Componentes clave |
|---------------------|----------|-------------------|
| "LineaRecicla" | Los alumnos no separan correctamente los residuos en las papeleras del aula | Sensor de color (TCS3200), servo motor para abrir tapa, buzzer de acierto/error |
| "EvitaChoques" | El robot choca constantemente contra las patas de las mesas y sillas durante prácticas de navegación | Sensor ultrasónico HC-SR04 + sensor táctil de parachoques (microswitch) |
| "BuscaLuz" | El aula no tiene suficiente luz natural y los alumnos olvidan encender las luces cuando nubla | Dos sensores LDR (comparación de luz ambiental), LED de aviso o relé para encender luz |
| "SigueVoz" | El robot debe ser controlado por comandos de voz para alumnos con movilidad reducida | Módulo de reconocimiento de voz (VR-002), driver de motores, altavoz de respuesta |

**Criterio de evaluación adicional:** 
- Se valora especialmente que el alumno **no copie literalmente el ejemplo** y proponga una solución adaptada a su aula real.
- El diagrama de flujo debe ser lógico y completo (incluir inicio, condiciones, acciones y bucle).
- Las medidas de seguridad deben ser específicas para el proyecto, no las medidas generales del taller.

---

## Resumen de puntuación por RA

| RA | Descripción | Puntos |
|----|-------------|--------|
| RA1 | Introducción a la robótica y componentes | 25 |
| RA2 | Programación básica de robots | 40 |
| RA3 | Mantenimiento y seguridad en robots | 20 |
| RA4 | Proyecto integrador | 15 |
| **TOTAL** | | **100** |

---

## Rúbrica general de evaluación del examen

| Rango | Calificación | Descripción |
|-------|--------------|-------------|
| 90 - 100 | Sobresaliente (SB) | Todo correcto. Código funcional y bien comentado. Dibujos claros y etiquetados. Proyecto original, viable y bien argumentado. |
| 70 - 89 | Notable (NT) | Algún error menor no grave. Código funcional pero con pequeños fallos. Proyecto bien planteado. |
| 50 - 69 | Aprobado (AP) | Errores significativos pero la práctica funciona parcialmente. Proyecto completo pero con carencias. |
| 0 - 49 | Suspenso (SS) | No alcanza los mínimos en varios RAs. Práctica no funcional o proyecto incompleto. |

---

**FIN DEL EXAMEN Y SOLUCIONARIO DE ROBÓTICA**
