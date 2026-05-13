# Tarea-de-Interfaces-POO
Ejercicios con uso de interfaces

Tarea 1: Sistema académico de documentos

Objetivo: usar una interfaz con tres clases.
Interfaz: Imprimible con método imprimir().
Clases: Certificado, ActaNotas, HorarioAcademico.

Tarea 2: Sistema bancario de pagos
Objetivo: aplicar interfaz con validación de montos.
Interfaz: Pagable con método procesarPago(double monto).
Clases: PagoEfectivo, PagoTarjeta, Transferencia.

Tarea 3: Sistema de roles empresariales
Objetivo: diferenciar responsabilidades con varias interfaces.
Interfaces:
Autenticable → iniciar sesión
Reportable → generar reportes
Gestionable → gestionar datos
Clases:
Cajero: Autenticable + Gestionable
Administrador: Autenticable + Reportable + Gestionable

Supervisor: Autenticable + Reportable
