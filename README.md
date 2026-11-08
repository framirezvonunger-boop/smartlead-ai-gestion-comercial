# SmartLead AI Gestión Comercial

**Autora:** Francisca Beatriz Ramírez von Unger  
**Curso:** IA Automation · Coderhouse  
**Corte documental:** 8 de noviembre de 2026  
**Estado:** documentación para evaluación académica; funcionalidades y pruebas pendientes identificadas.

SmartLead AI organiza consultas comerciales con Gmail, n8n, GPT-4o mini y Airtable. El workflow contempla revisión humana y registro de errores de IA.

## Documentación

- [Informe técnico y ejecutivo PDF](SmartLead_AI_Informe_Formato_Corregido.pdf)
- [Informe Word editable](SmartLead_AI_Informe_Formato_Corregido.docx)
- [Esquema Airtable verificado](SmartLead_AI_Esquema_Airtable_Verificado.json)
- [Evidencia directa de Ejecución 10](SmartLead_AI_Evidencia_Ejecucion_10.json)
- [Validación de registros y metadatos del dashboard](SmartLead_AI_Validacion_Airtable.json)
- [Video de tres minutos](SmartLead_AI_Video_Profesional_Revisado.mp4)
- [Conversiones y supuestos en CLP y ARS](SmartLead_AI_Conversion_CLP_ARS.json)

## Resultados verificados

Las capturas documentan el ingreso de correo y el envío y recepción de la alerta interna de revisión humana. La consulta directa a Airtable confirma 71 campos, cuatro pares de vínculos recíprocos y el registro de la Ejecución 10 en estado Error, con el texto del fallo simulado. El registro 10 no tiene ID de n8n informado.

La Ejecución 9 tiene ID n8n 39, Estado En cola y Estado de aprobación Aprobado. Se verifica el valor actual del campo, sin afirmar quién aprobó ni por qué mecanismo. Los primeros ocho registros de Ejecuciones son datos de demostración; no equivalen a ocho pruebas reales ni sus costos a facturas.

El video elegido utiliza capturas reales, íconos representativos y música instrumental original. Dura tres minutos, sin locución. Es una presentación de las evidencias disponibles; no representa una ejecución nueva en vivo. Los campos del registro de error se muestran como transcripción identificada.

## Dashboard y acceso

[Pipeline comercial en Airtable](https://airtable.com/appJ8tQtzVQsC2evt/tblp7CFnECr8E6QZI/viwX5P0FH14HKUTjU?blocks=hide) es una vista de cuadrícula de Leads. La interfaz SmartLead AI - Dirección Comercial contiene Dashboard Ejecutivo **en borrador**. El enlace público, la publicación y sus indicadores siguen pendientes. La consulta de metadatos no permite certificar el contenido visual del borrador.

## Respaldo técnico y pendientes

[Workflow anterior depurado](Workflow_anterior_sin_credenciales_NO_VIGENTE.json) contiene un export de ocho nodos, sin referencias de credenciales ni datos fijados. No es el JSON vigente de la captura. No sustituir el workflow actual por ese archivo.

Antes de entregar:

1. Exportar el workflow actualizado y comprobar sus mapeos dinámicos. El export anterior contiene un email ficticio fijo en Create a record.
2. Documentar al menos cinco ejecuciones reales, incluida la ruta de datos incompletos y el error de API.
3. Probar aprobación y rechazo completos y el bloqueo de la acción crítica.
4. Publicar y verificar el dashboard con KPIs y tasa de errores, identificando datos de demostración.
5. Contrastar los esquemas JSON de las integraciones y la evidencia de Omni AI si corresponde.
6. Cerrar las diferencias respecto a la rúbrica en costos: lectura densa y procesamiento por lotes son propuestas, no implementaciones verificadas; no se certifica un ahorro real del 50 %.
7. Verificar el acceso del evaluador al dashboard; la publicación del repositorio no publica la base de Airtable.

La rúbrica oficial asigna 20 % a cada uno de los cinco criterios. Este repositorio organiza la evidencia disponible sin presentar pendientes como resultados logrados.

## Versiones de entrega

Los enlaces anteriores apuntan al informe corregido en Calibri, con resumen ejecutivo separado, y al video profesional revisado elegido por la autora. Los archivos con nombres anteriores son antecedentes de revisión y no la versión recomendada para evaluar.

## Datos y credenciales

El export anterior se comparte sin referencias de credenciales ni datos fijados. Los JSON de evidencia documentan esquema, metadatos y registros de prueba; no incluyen una exportación de contactos. No se publica la bandeja de entrada completa. Las conexiones a servicios deben configurarse en las cuentas de quien importe el workflow.
