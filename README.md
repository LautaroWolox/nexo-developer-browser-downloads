# NEXO Developer Browser — descargas oficiales

**Canal público de distribución.** Este repositorio contiene documentación y notas
de versión, **no incluye el código fuente de NEXO**.

## Estado

**Beta en revisión de seguridad; todavía no hay una versión pública aprobada.**
Los instaladores solo se incorporarán a [Releases] cuando finalice la revisión.

## Plataformas previstas

| Plataforma | Paquete | Estado |
|---|---|---|
| Ubuntu / Debian x64 | `.deb` | Generado localmente, pendiente de aprobación |
| Linux x64 | `.AppImage` | Generado localmente, pendiente de compatibilidad |
| Windows x64 | `.exe` | Pendiente de compilar, firmar y probar |
| macOS | `.dmg` | Pendiente de compilar, firmar y probar |

NEXO es un navegador de escritorio basado en Chromium para desarrolladores.
Incluye accesos a documentación, foros, GitHub/GitLab, clientes API, editores
de código, herramientas locales y un SQL Studio con controlador Oracle.

**Advertencias:** algunos servicios web no permiten autenticarse dentro de
navegadores embebidos. NEXO no incluye licencias ni instalaciones de Postman,
Insomnia, Apidog u otros servicios externos.

## Descargar de forma segura

Cuando exista una versión aprobada:
1. Abrí la sección **Releases** de este repositorio.
2. Descargá el instalador correspondiente a tu sistema.
3. Compará el SHA-256 con el archivo `SHA256SUMS.txt` adjunto a esa versión.
4. Seguí las instrucciones de instalación de esa versión.

**Nunca ingreses una contraseña de base de datos en un enlace de descarga.**

## Proyecto y soporte

Documentos: [seguridad](SECURITY.md) · [privacidad](PRIVACY.md) ·
[estado de la publicación](ESTADO.md).

> NEXO no está afiliado con Oracle, GitHub, GitLab, Postman ni otros proveedores citados.
