# Sistema de Banca por Internet — Arquitectura de Solución

Diseño de arquitectura bajo el modelo C4 (Contexto, Contenedores y Componentes) para un sistema de banca por internet, desarrollado como ejercicio de Arquitecto de Soluciones para la entidad BP. Incluye justificación teórica de cada decisión arquitectónica: autenticación OAuth2.0, onboarding con verificación facial, patrones de resiliencia y desacoplamiento, despliegue en AWS, normativa y seguridad.

## Contenido

- 📄 **Documento completo**: [`Sistema de Banca por Internet.pdf`](./Sistema%20de%20Banca%20por%20Internet.pdf)
- 🖼️ **Diagramas en alta resolución**: carpeta [`diagramas/`](./diagramas)

## Alcance

- Diagrama de Contexto
- Diagrama de Contenedores (15 piezas: apps, API Gateway, BFF, 7 microservicios, infraestructura de soporte)
- Diagramas de Componentes (8: Transferencias, Onboarding, Datos Básicos, Movimientos, Notificaciones, Auditoría, Comprobantes, BFF)
- Arquitectura de Acceso a Datos, Seguridad, Normativa y Cumplimiento, Alta Disponibilidad/DR/Monitoreo, Manejo de Costos
