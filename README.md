# OLYMPIC FITNESS Alcalá — Concept Redesign V4

🌐 **Live demo:** https://lonetreee.github.io/olympic-fitness-concept/

Rediseño conceptual **no oficial** de una landing page para un gimnasio local de Alcalá de Henares.

## Goal

Transformar una presencia pública muy orientada a gestión de socios en una propuesta de captación clara para nuevos visitantes:

```text
Descubrir
   ↓
Entender
   ↓
Confiar
   ↓
Consultar
   ↓
Contactar
```

## V4 — Final polish

La V4 parte de una revisión específica de desktop y móvil de la V3 y corrige los principales puntos de fricción.

### Desktop improvements

- Header sticky con fondo translúcido.
- Navegación activa según la sección visible.
- Mejor aprovechamiento visual del hero.
- Mapa conceptual convertido en un CTA clicable completo.
- CTA final presentado como tarjeta de conversión.
- Mejor jerarquía de información y estados hover/focus.
- Scroll offsets para que el header sticky no tape títulos al navegar por anclas.

### Mobile improvements

- Menú animado y bloqueo del scroll del fondo cuando está abierto.
- Botón hamburguesa animado.
- Barra fija de llamada / ubicación compatible con `safe-area-inset-bottom`.
- Botones de CTA al 100 %.
- Mejor wrapping del hero y del bloque de mapa.
- Tap targets más amplios.
- Cierre automático del menú al cambiar de breakpoint.

### Accessibility and resilience

- Skip link.
- `aria-current` en navegación activa.
- FAQ con `aria-controls`.
- Solo una pregunta FAQ abierta cada vez.
- Cierre con `Escape`.
- `focus-visible`.
- Compatibilidad con `prefers-reduced-motion`.
- El contenido permanece visible si JavaScript falla: las animaciones solo se activan cuando existe la clase `.js`.

## Technologies

- HTML5
- CSS3
- JavaScript vanilla
- Git
- GitHub
- GitHub Pages

## Public information used

Para el concepto se ha utilizado información pública del centro consultada para el proyecto:

- web pública del centro;
- ficha local;
- horario;
- dirección;
- teléfono público;
- tipos de entrenamiento mencionados públicamente;
- temas generales recurrentes en reseñas públicas.

No se han copiado fotografías, logotipos oficiales ni textos completos de reseñas.

## Structure

```text
olympic-fitness-concept/
├── index.html
├── styles.css
├── script.js
├── README.md
└── DEPLOY.md
```

## Important

Este proyecto es una **demo de portfolio** y no es la web oficial del negocio.

- No representa ni está afiliado con OLYMPIC FITNESS.
- Incluye `noindex,nofollow`.
- Los datos deben verificarse con el propietario antes de una publicación oficial.
- Una versión oficial requeriría autorización para marca, fotografías y contenido.

## If the business accepts the project

1. Validar identidad de marca, textos y servicios.
2. Sustituir gráficos conceptuales por fotografías autorizadas.
3. Confirmar horarios, actividades, tarifas y contacto.
4. Integrar WhatsApp, formulario o sistema real de reservas.
5. Añadir Aviso Legal, Privacidad y Cookies cuando corresponda.
6. Configurar dominio propio y alojamiento de producción.
7. Retirar `noindex,nofollow` y preparar SEO local.
8. Configurar analítica respetando consentimiento y privacidad.
