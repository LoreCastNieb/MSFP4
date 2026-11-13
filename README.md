[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=LoreCastNieb/MSFP4)
# Modelado y Control del Sistema Endocrino

## Descripción
Este proyecto desarrolla el modelado matemático y la simulación dinámica de un sistema endocrino mediante analogías eléctricas, funciones de transferencia y ecuaciones integro-diferenciales.

Se comparan dos condiciones del sistema: **Control** y **Caso**, utilizando MATLAB y Simulink. Además, se implementa un controlador PID para analizar y corregir el comportamiento dinámico de la respuesta.

## Objetivo
Representar el comportamiento de un sistema fisiológico endocrino mediante modelos matemáticos, analizar su respuesta temporal y evaluar el funcionamiento de un controlador PID.

## Modelos implementados

- **CE (Circuito Eléctrico):** representación del sistema mediante resistencias, capacitor e inductor.
- **FT (Función de Transferencia):** representación matemática de la relación entre entrada y salida.
- **EID (Ecuaciones Integro-Diferenciales):** descripción del comportamiento dinámico del sistema.
- **PID (Controlador):** mecanismo de control para reducir el error entre las condiciones de referencia y caso.

## Variables del modelo

| Variable | Descripción |
|---|---|
| Ve(t) | Señal de entrada |
| Vs(t) | Señal de salida |
| R1 | Resistencia 1 |
| R2 | Resistencia 2 |
| C | Capacitancia |
| L | Inductancia |
| e(t) | Señal de error |
| PID | Control proporcional, integral y derivativo |

## Desarrollo en Simulink

El modelo está compuesto por dos subsistemas principales:

**1. Sistema Control**
- Circuito eléctrico (CE).
- Función de transferencia (FT).
- Ecuaciones integro-diferenciales (EID).

**2. Sistema Caso**
- Circuito eléctrico (CE).
- Función de transferencia (FT).
- Ecuaciones integro-diferenciales (EID).
- Controlador PID.

## Herramientas utilizadas

- MATLAB.
- Simulink.
- BioRender.
- GitHub.

## Resultados
Se realiza la comparación de las respuestas dinámicas de los modelos Control y Caso mediante gráficas de MATLAB/Simulink.

Se analiza el comportamiento temporal de las señales, las diferencias entre condiciones y el efecto del controlador PID sobre la respuesta del sistema.

## Conclusión
Con este proyecto se logra representar un sistema endocrino mediante modelos matemáticos y circuitos eléctricos equivalentes. El uso de MATLAB y Simulink permite observar y comparar el comportamiento de las diferentes representaciones, mientras que el controlador PID permite estudiar cómo se puede corregir la respuesta de un sistema dinámico.

## Autores
- Lorena Lizel Castañeda Nieblas – 23210695
