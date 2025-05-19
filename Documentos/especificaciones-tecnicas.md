# Requisitos Técnicos – Proyecto UAV-VTOL: Mecanismo Rotatorio de Motores

## 1. Requisitos funcionales

- El mecanismo debe permitir la **rotación sincronizada** de los motores de 0° (despegue vertical) a 90° (vuelo horizontal).
- El cambio de orientación debe realizarse en un **tiempo máximo de 2 segundos**.
- Debe operar en ambos sentidos (vertical a horizontal y viceversa) de forma segura y repetible.
- Se requiere mantener la **alineación precisa** durante la transición para evitar vibraciones o pérdida de control.

## 2. Requisitos estructurales

- **Peso máximo del mecanismo**: 200 gramos (incluyendo materiales, motor/servo, uniones y soporte).
- El diseño debe soportar un **momento de torsión mínimo de 2 N·m** sin deformarse de forma permanente.
- **Tolerancia dimensional máxima**: ±0.2 mm para partes móviles o ensambladas.
- Integración mecánica con el ala y el cuerpo del UAV mediante puntos de anclaje definidos (mínimo 3 puntos de sujeción).

## 3. Requisitos de materiales

- Los materiales principales deben ser:
  - **PLA+ o PETG** para impresión 3D (prototipo funcional).
  - **Aluminio 6061-T6** o equivalente en caso de versión fabricada para vuelo real.
- Todas las piezas deben tener **resistencia a la fatiga y buena estabilidad térmica** (mínimo 50°C de operación continua).
- Cojinetes, rodamientos o ejes deberán ser de **acero inoxidable o latón**.

## 4. Requisitos de fabricación

- Las piezas deben ser diseñadas para ser:
  - Imprimibles en 3D con extrusores de 0.4 mm.
  - Mecanizables en fresadora CNC o fabricables con herramientas básicas.
- Tiempo estimado de fabricación por unidad: **< 6 horas** (prototipo).

## 5. Requisitos eléctricos

- Motorización activa:
  - **Voltaje operativo del motor/servo**: 5V – 12V DC.
  - Consumo máximo estimado: **< 1 A** por unidad.
  - Compatibilidad con control PWM o protocolo I2C (según microcontrolador del UAV).

## 6. Requisitos de pruebas y validación

- Debe soportar al menos **100 ciclos de rotación completos** sin pérdida de funcionalidad.
- Pruebas de alineación, torsión y resistencia mecánica deben ser realizadas con tolerancias definidas.
- Se debe documentar cualquier deformación, fallo mecánico o desviación tras los ciclos de prueba.

## 7. Requisitos de seguridad

- El diseño no debe presentar bordes filosos ni elementos expuestos que puedan poner en riesgo a los operadores.
- La rotación debe tener un **tope mecánico o límite de software** para evitar giros excesivos.

## 8. Requisitos de integración

- El mecanismo debe permitir **mantenimiento sencillo**, incluyendo desmontaje de piezas sin necesidad de herramientas especializadas.
- Debe adaptarse a futuras versiones de alas/motores sin rediseñar el sistema completo (modularidad).
- Compatible con motores tipo **brushless 2207–2212** con hélice de 6–8 pulgadas (según configuración prevista).

---
