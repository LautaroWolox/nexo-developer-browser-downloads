# Estado de publicación: v0.6.0

**NO APROBADA PARA DISTRIBUCIÓN MASIVA** (13 octubre 2026).

Validado:
- Linux .deb y .AppImage generados localmente.
- 25 pruebas automatizadas de navegación, GUI y SQL con driver simulado.
- `npm audit --omit=dev`: 0 avisos en dependencias de producción.
- Paquete Electron con sandbox y permisos web restrictivos.
- No se observaron credenciales reales en los archivos revisados.

Pendiente antes de Release público:
- Auditoría detallada de seguridad / prueba manual en sistema limpio.
- Resolver o aceptar expresamente los avisos de dependencias del builder.
- Validar SQL Studio con base Oracle de prueba de lectura; limitar permisos DB.
- Reemplazar el `homepage` provisional example.org dentro del instalador.
- Definir contacto, identidad de mantenimiento, licencia de distribución.
- Firmar y comprobar instaladores; definir actualización de Chromium.
- Validar AppImage en distintos Linux y producir versiones Windows/macOS.
- Crear repositorio público y cargar activos SOLO mediante Releases,
  jamás incorporando binarios grandes ni código fuente al repositorio.
