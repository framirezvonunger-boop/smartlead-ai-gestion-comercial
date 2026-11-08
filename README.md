# SmartLead AI Gestión Comercial

**Autora:** Francisca Beatriz Ramírez von Unger  
**Curso:** IA Automation · Coderhouse  
**Corte documental:** 8 de noviembre de 2026  
**Estado:** preparación de entrega; repositorio privado.

SmartLead AI organiza consultas comerciales con Gmail, n8n, GPT-4o mini y Airtable. El workflow contempla revisión humana y registro de errores de IA.

## Documentación

- [Informe técnico y ejecutivo PDF](SmartLead_AI_Informe_Verificado.pdf)
- [Informe Word editable](SmartLead_AI_Informe_Verificado.docx)
- [Esquema Airtable verificado](SmartLead_AI_Esquema_Airtable_Verificado.json)
- [Evidencia directa de Ejecución 10](SmartLead_AI_Evidencia_Ejecucion_10.json)
- [Validación de registros y metadatos del dashboard](SmartLead_AI_Validacion_Airtable.json)
- [Video de tres minutos](SmartLead_AI_Video_Demostrativo.mp4)
- [Guion opcional de narración](SmartLead_AI_Guion_Video.txt)

## Resultados verificados

Las capturas documentan el ingreso de correo y el envío y recepción de la alerta interna de revisión humana. La consulta directa a Airtable confirma 71 campos, cuatro pares de vínculos recíprocos y el registro de la Ejecución 10 en estado Error, con el texto del fallo simulado. El registro 10 no tiene ID de n8n informado.

La Ejecución 9 tiene ID n8n 39, Estado En cola y Estado de aprobación Aprobado. Se verifica el valor actual del campo, sin afirmar quién aprobó ni por qué mecanismo. Los primeros ocho registros de Ejecuciones son datos de demostración; no equivalen a ocho pruebas reales ni sus costos a facturas.

El video utiliza capturas reales y texto explicativo. Dura tres minutos, no tiene audio ni representa una ejecución nueva en vivo.

## Dashboard y acceso

[Pipeline comercial en Airtable](https://airtable.com/appJ8tQtzVQsC2evt/tblp7CFnECr8E6QZI/viwX5P0FH14HKUTjU?blocks=hide) es una vista de cuadrícula de Leads. La interfaz SmartLead AI - Dirección Comercial contiene Dashboard Ejecutivo **en borrador**. El enlace público, la publicación y sus indicadores siguen pendientes. La consulta de metadatos no permite certificar el contenido visual del borrador.

## Respaldo técnico y pendientes

`respaldo_anterior` contiene un export de ocho nodos, sin referencias de credenciales ni datos fijados. No es el JSON vigente de la captura. No sustituir el workflow actual por ese archivo.

Antes de entregar:

1. Exportar el workflow actualizado y comprobar sus mapeos dinámicos. El export anterior contiene un email ficticio fijo en Create a record.
2. Documentar al menos cinco ejecuciones reales, incluida la ruta de datos incompletos y el error de API.
3. Probar aprobación y rechazo completos y el bloqueo de la acción crítica.
4. Publicar y verificar el dashboard con KPIs y tasa de errores, identificando datos de demostración.
5. Contrastar los esquemas JSON de las integraciones y la evidencia de Omni AI si corresponde.
6. Cerrar las diferencias respecto a la rúbrica en costos: lectura densa y procesamiento por lotes son propuestas, no implementaciones verificadas; no se certifica un ahorro real del 50 %.
7. Confirmar la publicación del repositorio para evaluación o el acceso autorizado del evaluador.

La rúbrica oficial asigna 20 % a cada uno de los cinco criterios. Este repositorio organiza la evidencia disponible sin presentar pendientes como resultados logrados.
