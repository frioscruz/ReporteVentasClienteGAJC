# ReporteVentasClienteGAJC

Reporte de ventas por cliente 2025-2026 y su tablero HTML.

## Contenido

| Carpeta / archivo | Qué es |
|---|---|
| `tablero/tablero.html` | Tablero de analítica de ventas. Se abre en el navegador y lee el Excel (hoja `2025-2026`) desde OneDrive/SharePoint o desde un archivo local. |
| `tablero/logo.jpg` | Logo del encabezado del tablero. |
| `CHANGELOG.md` | Lista de versiones y qué cambió en cada una. |

Los libros de Excel (`FacGAJC2025-2026-*.xlsx`) no están en el repositorio porque
contienen datos de clientes y el repositorio es público (ver `.gitignore`).

## Versiones (CalVer)

Cada versión se marca con una etiqueta según la fecha: `AAAA.MM.DD`.
Si hay más de una versión el mismo día, se agrega un número: `AAAA.MM.DD.1`, `AAAA.MM.DD.2`, etc.

Ya no hace falta guardar copias como `tablero_.html` o `-4a2`: cada versión
anterior queda guardada en el historial y se puede recuperar en cualquier momento.
