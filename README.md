# asisya-vehicle-assistance
Sistema distribuido basado en microservicios para la gestión y asignación inteligente de asistencias vehiculares.

📌 Objetivo

Diseñar e implementar una arquitectura moderna, escalable y segura para el módulo:

“Asignación Inteligente de Proveedores”

Tecnologías utilizadas:

.NET 8

React (opcional)

Docker

PostgreSQL

Redis

AWS (diseño arquitectónico)

GitHub Actions

Clean Architecture + DDD

Arquitectura General

<img width="1746" height="1090" alt="image" src="https://github.com/user-attachments/assets/9ab1daa7-7317-4ab8-bfd5-7bc6b0c2738a" />

<img width="2471" height="2339" alt="image" src="https://github.com/user-attachments/assets/3c773f25-9ea9-4a7a-bdd5-2888d8324a1a" />

<img width="1306" height="1290" alt="image" src="https://github.com/user-attachments/assets/bdbaf4fb-0085-4729-83f8-44549a95a15c" />

<img width="770" height="557" alt="image" src="https://github.com/user-attachments/assets/4b8a5536-79c3-47ac-923d-00e6463993c1" />

Enfoque Arquitectónico

- Microservicios

- Domain Driven Design (DDD)

- Clean Architecture

- Event Driven Architecture

- Procesamiento asincrónico

- Infraestructura desacoplada

Componentes Principales
- API Gateway

- Rate limiting

- JWT validation

- WAF

- Routing por servicio

Microservicios
Servicio	Responsabilidad
AssistanceRequestService	Gestión de solicitudes
ProviderOptimizerService	Selección óptima de proveedor
LocationService	Cálculo geoespacial
NotificationsService	Notificaciones en tiempo real

- ProviderOptimizerService (Implementado)

- Servicio crítico encargado de seleccionar el proveedor óptimo considerando:

- Distancia

- ETA

- Rating

- Disponibilidad

- Tipo de asistencia
