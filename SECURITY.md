# Seguridad de NEXO

**Estado:** beta no auditada para uso público general.

- Sandbox de Chromium y aislamiento de contenido web activados.
- Integraciones nativas mediadas por IPC solo para la interfaz interna.
- SQL Studio conecta con Oracle a través del proceso de la aplicación; las
  contraseñas no se guardan en el historial ni favoritos.
- SQL Studio restringe la sintaxis por defecto, **pero ninguna validación de SQL
  por expresiones regulares garantiza que una consulta SELECT no tenga efectos
  secundarios**. Usar siempre cuentas Oracle con permisos de solo lectura.
- No utilizar instaladores modificados ni opciones `--no-sandbox`.
- NEXO no incorpora todavía todas las protecciones de un navegador de consumo
  (p. ej. navegación segura, políticas de extensiones, actualizaciones automáticas
  verificadas y auditoría externa).

Antes de publicar públicamente cualquier instalador: revisar dependencias,
firmas y actualizaciones de Chromium, permisos, privacidad, certificados y
comportamiento en una instalación limpia.

Para comunicar problemas de seguridad, usar los mecanismos privados de
`Security Advisories` de GitHub cuando estén habilitados. No enviar credenciales
ni información personal por incidencias públicas.
