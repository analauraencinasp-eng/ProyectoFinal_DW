# AMAC – Bolsa de trabajo para adultos mayores

Maquetación en HTML y CSS de la plataforma de empleo AMAC (Entrega 2 · Desarrollo de Aplicaciones Web, UDEM).

**Sitio publicado:** [pendiente: URL de Vercel]

## Integrantes

| Integrante | Qué hizo |
|---|---|
| Nombre 1 | variables.css, base.css, encabezado y pie |
| Nombre 2 | index.html, vacante.html |
| Nombre 3 | login.html, registro-candidato.html |
| Nombre 4 | mis-solicitudes.html, empresa-vacantes.html, README |

## Páginas

- `index.html` – Listado de vacantes con buscador y filtros (RF-001, RF-002, RF-007)
- `vacante.html` – Detalle de vacante con "Postularme" y "Llamar" (RF-003, RF-004, RF-051)
- `login.html` – Inicio de sesión (RF-008)
- `registro-candidato.html` – Registro de candidato (RF-011, RF-012, RF-013)
- `mis-solicitudes.html` – Mis solicitudes (RF-005, RF-006)
- `empresa-vacantes.html` – Panel de vacantes de la empresa (RF-020, RF-021)

## Paleta de colores (`css/variables.css`)

| Variable | Color | Uso |
|---|---|---|
| `--color-encabezado` | #192944 | Encabezado |
| `--color-primario` | #202945 | Texto y botones oscuros |
| `--color-acento` | #FF815C | Acción principal |
| `--color-fondo` | #F4FCFF | Fondo de página |
| `--color-suave` | #CAE4EF | Pie de página y paneles |
| `--color-superficie` | #FFFFFF | Tarjetas |

## Tipografía

- Títulos: **Baskervville** (Google Fonts)
- Texto: **Work Sans** (Google Fonts)
- Texto base: `1.125rem` (18 px); títulos h1 `2rem` en celular y `3rem` en escritorio.

## Componentes reutilizables

| Clase CSS | Componente React (Entrega 3) |
|---|---|
| `encabezado` / `navegacion` | `<Encabezado />` |
| `pie` | `<Pie />` |
| `boton` (`--primario`, `--secundario`, `--oscuro`) | `<Boton />` |
| `boton-ayuda` | `<BotonAyuda />` |
| `tarjeta-vacante` | `<TarjetaVacante />` |
| `etiqueta-estatus` | `<EtiquetaEstatus />` |
| `campo-formulario` | `<CampoFormulario />` |
| `grupo-campos` | `<GrupoCampos />` |
| `tarjeta` | `<Tarjeta />` |

## Capturas

**index.html en celular**

![index en celular](img/captura-celular.png)

**index.html en escritorio**

![index en escritorio](img/captura-escritorio.png)

**Lighthouse – Accessibility**

![Lighthouse](img/captura-lighthouse.png)
