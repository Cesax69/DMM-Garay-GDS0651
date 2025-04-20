Proyecto de IoT - Unidad III: Desarrollo de Interfaces Gráficas
Este repositorio contiene el desarrollo de un proyecto completo de Internet de las Cosas (IoT) para la asignatura Aplicaciones de IoT, correspondiente a la Unidad III: Desarrollo de Interfaces Gráficas. El objetivo es diseñar, implementar y documentar un prototipo de monitoreo y control de sistemas embebidos, integrando almacenamiento de datos, tecnologías de comunicación y una interfaz gráfica.
Información General

Nombre del Instrumento: Ejecución de tareas
Número de Instrumento: 1
Área Académica: Tecnologías de la Información y Comunicación
Programa Educativo: Tecnologías de la Información Área Desarrollo de Software Multiplataforma
Asignatura: Aplicaciones de IoT
Grupo(s): GDS0651 / GDS0652 / GDS0653
Facilitador: Rodríguez García Anastacio
Periodo de Entrega: 31-03-2025 al 11-04-2025
Tipo de Evaluación: Ordinaria

Objetivo del Proyecto
Desarrollar un sistema IoT funcional que integre:

Aplicación de software con interfaz gráfica.
Almacenamiento de datos en una base de datos.
Sensores analógicos y digitales.
Actuadores para control.
Documentación detallada en este repositorio.

Estructura de Evaluación
El proyecto se evalúa en tres componentes principales: Teoría (30 puntos), Práctica (60 puntos) y Ser (10 puntos), sumando un total de 100 puntos.
1. Parte Teórica (30 puntos)
Curso de Cisco NetAcad (15 puntos)

Descripción: Completar los módulos asignados del curso "Introducción a IoT y Transformación Digital" en Cisco NetAcad.
Evidencias: Capturas de pantalla de los módulos finalizados.

Cuestionario en Quizzing (15 puntos)

Descripción: Resolver un cuestionario sobre:
Fundamentos de IoT y transformación digital.
Tecnologías de comunicación y almacenamiento de datos.
Aplicaciones industriales de IoT.



2. Parte Práctica (60 puntos)
Requisitos del Proyecto IoT
El sistema debe incluir los siguientes elementos, cada uno valuado en 10 puntos:



Criterio
Descripción
Puntos



Conectividad y almacenamiento
Conexión estable a una base de datos SQL/NoSQL.
10


Comunicación
Uso de Serial, Bluetooth, TCP/IP o MQTT para transmisión de datos.
10


Interfaz gráfica
Implementación de una aplicación web/móvil o dashboard interactivo.
10


Sensores y actuadores
Integración de al menos 3 sensores y 3 actuadores funcionales.
10


Notificaciones
Alertas implementadas vía Telegram, WhatsApp o Email.
10


Documentación en GitHub
Código estructurado con un README.md detallado, incluyendo diagramas y ejemplos.
10


Ejemplo de Proyecto
Un sistema de monitoreo de temperatura en una oficina:

Sensores: Temperatura y humedad.
Almacenamiento: Base de datos MySQL.
Visualización: Panel web con Grafana.
Notificaciones: Alertas en Telegram.
Control: Activación de un ventilador o aire acondicionado según la temperatura.

Tecnologías Utilizadas

Microcontrolador: ESP32 / Raspberry Pi / Arduino.
Base de Datos: SQL (ej. MySQL) o NoSQL (ej. MongoDB).
Protocolos de Comunicación: Serial, Bluetooth, TCP/IP, MQTT.
Interfaz Gráfica: Aplicación web (ej. HTML/CSS/JS) o dashboard (ej. Grafana).

3. Parte Socioafectiva (10 puntos)
Autoevaluación y Coevaluación (5 puntos)

Respuestas a:
¿Qué hice bien?
¿Qué hice mal?
¿Qué puedo mejorar?



Responsabilidad y Puntualidad (5 puntos)

Entrega puntual de todas las evidencias requeridas.

Rúbrica de Evaluación
Teoría



Criterio
0 puntos
50% (Parcial)
100% (Completo)



Curso de NetAcad
No entrega
Entrega incompleta
Completa todos los módulos


Cuestionario
No responde
Responde parcialmente
Responde correctamente


Práctica



Criterio
0 puntos
50% (Parcial)
100% (Completo)



Conectividad y almacenamiento
Sin conexión a BD
Conexión con errores
Conexión estable y funcional


Comunicación
Sin comunicación
Comunicación intermitente
Comunicación estable


Interfaz gráfica
Sin interfaz
Interfaz básica
Interfaz completa y funcional


Sensores y actuadores
No integrados
Integración parcial
Funcionales y documentados


Notificaciones
No implementadas
Implementadas con fallos
Implementadas y operativas


Documentación
Sin README
README incompleto
README detallado con diagramas


Ser



Criterio
0 puntos
50% (Parcial)
100% (Completo)



Autoevaluación y coevaluación
No entrega
Responde parcialmente
Responde todas las preguntas


Puntualidad
No entrega
Entrega tardía
Entrega puntual


Instrucciones de Configuración

Clonar el Repositorio:git clone <URL_DEL_REPOSITORIO>


Instalar Dependencias:Configura el entorno del microcontrolador y las librerías necesarias (detalladas en la documentación del proyecto).
Ejecutar el Proyecto:  
Carga el código en el microcontrolador.  
Configura la base de datos y la interfaz gráfica según las instrucciones específicas del proyecto.



Arquitectura del Sistema
graph TD
    A[Sensores] --> B[Microcontrolador]
    B --> C[Base de Datos]
    B --> D[Interfaz Gráfica]
    B --> E[Notificaciones]

Contribuciones
Si deseas contribuir, por favor revisa las Issues del repositorio o envía un Pull Request con tus mejoras.

Desarrollado por [Tu Nombre] para la asignatura Aplicaciones de IoT - Unidad III.
