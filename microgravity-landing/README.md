# Microgravity Engineers — Landing page

Sitio web de **Microgravity Engineers**, startup deep tech costarricense nacida en la Facultad de Ingeniería de ULACIT. Desarrollamos un clinostato de dos ejes, de costo accesible, que simula microgravedad para cultivar esferoides tumorales en 3D y probar tratamientos contra el cáncer con resultados más confiables.

## Contenido del sitio

- **Inicio:** propuesta de valor y diseño del clinostato
- **Problema:** cultivos 2D en placas Petri frente a equipos de microgravedad de alto costo
- **Solución:** funcionamiento del clinostato en tres pasos
- **Validación:** modelo matemático propio; la gravedad promedio baja a ≈0.01 % en menos de un minuto
- **Para quién:** universidades, empresas farmacéuticas y empresas de dispositivos biomédicos
- **Equipo y mentores**
- **Contacto**

## Estructura

```
├── index.html          # Página completa (HTML, CSS y JS en un solo archivo)
└── assets/
    ├── clinostato.png  # Render del clinostato con la paleta de marca
    ├── favicon.svg
    ├── fonts/          # Montserrat (400–700), servida localmente
    └── team/           # Fotos del equipo y los mentores
```

## Tecnología

Sitio estático en HTML, CSS y JavaScript, sin dependencias ni proceso de build. Es responsive y respeta la preferencia de movimiento reducido del sistema.

## Ver en local

Abrí `index.html` en el navegador o levantá un servidor simple:

```bash
python3 -m http.server 8000
```

## Despliegue en Vercel

1. Importá el repositorio en [vercel.com](https://vercel.com) con **Add New → Project**.
2. En **Framework Preset**, elegí **Other**.
3. Dejá vacíos el comando de build y el directorio de salida, y hacé clic en **Deploy**.

Cada push a `main` vuelve a publicar el sitio automáticamente.

## Identidad de marca

| Color | Hex | Uso |
| --- | --- | --- |
| Vacío Espacial | `#100923` | Fondos oscuros |
| Nebulosa Profunda | `#1D143E` | Texto sobre fondos claros |
| Índigo Orbital | `#2E2258` | Tarjetas sobre fondo oscuro |
| Púrpura Nebulosa | `#693D8F` | Color secundario |
| Magenta Plasma | `#B23FD6` | Acentos y llamadas a la acción |
| Lavanda Estelar | `#A788C4` | Detalles e íconos |
| Blanco Estelar | `#F7F3FF` | Fondos claros y texto sobre oscuro |

Tipografía: **Montserrat**.

## Contacto

microgravityengineers@gmail.com

---

© 2026 Microgravity Engineers · Facultad de Ingeniería, ULACIT, Costa Rica
