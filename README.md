# Informe Final del Proyecto: Pruebas de Regresión para Urban Routes

## **Descripción del Proyecto**
**Urban Routes** es una aplicación diseñada para crear rutas personalizadas y calcular la duración y el costo del viaje para diversos tipos de transporte. Su interfaz consta de los siguientes elementos:

- **Campos de entrada:**
  - `Desde`: Dirección inicial.
  - `Hasta`: Dirección de destino.
- **Modos de transporte:**
  - Óptimo
  - Flash
  - Personal
- **Tipos de transporte disponibles:**
  - Automóvil del usuario
  - A pie
  - Taxi
  - Bicicleta
  - Scooter
  - Compartir automóvil

El propósito del proyecto fue realizar pruebas de regresión para garantizar la estabilidad de la aplicación y detectar errores previos, con un enfoque en mantener una excelente experiencia de usuario.

---

## **Objetivo**
- Ejecutar casos de prueba previamente preparados para validar las funcionalidades principales de Urban Routes.
- Identificar errores y documentarlos en informes detallados para su solución.
- Realizar pruebas exclusivamente en **Google Chrome**.

---

## **Proceso de Pruebas**
### 1. **Preparación**
- Revisión de los casos de prueba.
- Configuración del entorno de pruebas en **Google Chrome**.
- Definición de los criterios de éxito para cada caso de prueba.

### 2. **Ejecución de Pruebas**
- **Campos de direcciones:**
  - Validación de entradas válidas e inválidas.
  - Manejo de errores al dejar campos vacíos.
- **Modos de transporte:**
  - Pruebas funcionales para los modos "Óptimo", "Flash" y "Personal".
  - Verificación de cálculos de tiempo y costo del viaje.
- **Selección de tipos de transporte:**

 - Combinación de opciones (e.g., a pie + compartir automóvil).
  - Cambios de estado al alternar íconos de transporte.
- **Compatibilidad del navegador:**
  - Validación de la interfaz y funcionalidades en Google Chrome.

### 3. **Resultados de Pruebas**
- **Casos de prueba ejecutados:** `100`
- **Casos exitosos:** `85`
- **Errores detectados:** `15`

---

## **Errores Detectados**
### 1. **Errores Funcionales**
- El modo **"Flash"** no calcula correctamente el tiempo de viaje en distancias largas.
- Los costos mostrados para el modo **"Personal"** no se actualizan al cambiar entre diferentes tipos de transporte.
### 2. **Errores de UI/UX**
- Al seleccionar el ícono de bicicleta, este desaparece temporalmente.
- El campo `Hasta` no muestra sugerencias al escribir direcciones conocidas.

### 3. **Errores de Validación**
- No se muestra mensaje de error si ambos campos (`Desde` y `Hasta`) están vacíos.
- Permite caracteres especiales en los campos de dirección sin emitir advertencias.

---

## **Acciones Realizadas**
- Documentación detallada de los errores encontrados en un sistema de seguimiento de bugs.
- Priorización de errores críticos y comunicación al equipo de desarrollo.
- Organización de reuniones para discutir soluciones a los problemas reportados.
- 
---

## **Conclusión**
Las pruebas de regresión permitieron identificar y documentar errores que, al corregirse, mejorarán significativamente la experiencia del usuario. La estabilidad de la aplicación es crucial para evitar malas reseñas y mantener la fidelidad de los usuarios frente a la competencia.

**Enlace a los reportes finales:** [[https://drive.google.com/drive/folders/1rii3xu2T-NtLCo8w5XoYfbiX8KMbJhKC?usp=sharing]]

---

## **Recomendaciones**
1. Realizar una nueva ronda de pruebas tras la corrección de errores críticos.
2. Automatizar las pruebas de regresión para reducir el tiempo de ejecución en futuras iteraciones.
3. Ampliar las pruebas a otros navegadores para garantizar la compatibilidad multiplataforma.

---

**Equipo QA de Urban Routes**  
