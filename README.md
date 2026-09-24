# OLYMPIC FITNESS Alcalá — Concept Redesign V3

🌐 **Live demo:** https://lonetreee.github.io/olympic-fitness-concept/

Rediseño conceptual **no oficial** de una landing page para un gimnasio local de Alcalá de Henares.

## The problem

La presencia web pública actual del centro está muy orientada a funciones para socios —acceso, registro, reservas y gestión—, mientras que un nuevo visitante necesita entender rápidamente:

- qué tipo de entrenamiento puede encontrar;
- qué diferencia al centro;
- cuándo abre;
- dónde está;
- cómo contactar.

## The solution

La V3 convierte la propuesta en una landing de captación más completa, manteniendo el proyecto como demo de portfolio y sin utilizar fotografías ni textos propietarios.

### Customer journey

```text
Descubrir el centro
        ↓
Entender qué ofrece
        ↓
Generar confianza
        ↓
Consultar horario y ubicación
        ↓
Llamar / llegar al centro
```

## What changed in V3

- Nueva sección de confianza basada en temas recurrentes de reseñas públicas.
- Dirección y teléfono públicos integrados en los CTA.
- Botón real de llamada mediante `tel:`.
- Barra de acciones fija en móvil.
- Nueva sección de tres pasos para reducir fricción.
- FAQ interactiva y accesible.
- Animaciones suaves con `IntersectionObserver`.
- Compatibilidad con `prefers-reduced-motion`.
- Copy más orientado a conversión.
- Navegación actualizada para reflejar el recorrido del usuario.
- Información de fuentes públicas separada de testimonios inventados.

## Technologies

- HTML5
- CSS3
- JavaScript vanilla
- Git
- GitHub
- GitHub Pages

## Accessibility

- Estados `focus-visible`.
- Menú móvil con `aria-expanded`.
- FAQ con botones semánticos y estados ARIA.
- Cierre de elementos interactivos con `Escape`.
- Soporte para `prefers-reduced-motion`.
- Diseño responsive para desktop, tablet y móvil.

## Public information used

Para la V3 se consultó información pública disponible el 24/09/2026:

- Web pública del centro: https://www.olympicfitness.es/
- Ficha local y reseñas públicas: https://alcala365.com/ficha/olympic-fitness-alcala

Datos utilizados únicamente como referencia para esta demo:

- horario;
- dirección;
- teléfono público;
- tipos de entrenamiento mencionados públicamente;
- temas generales que se repiten en reseñas públicas.

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
- El nombre se utiliza únicamente para mostrar un concepto de rediseño.
- Los datos deben verificarse con el propietario antes de una publicación oficial.
- La versión oficial requeriría autorización para marca, fotografías y contenido.

## If the business accepts the project

1. Validar identidad de marca y contenido.
2. Sustituir gráficos conceptuales por fotografías autorizadas.
3. Confirmar horarios, actividades, tarifas y contacto.
4. Conectar WhatsApp, formularios o sistema real de reservas.
5. Añadir Aviso Legal, Privacidad y Cookies cuando corresponda.
6. Configurar dominio propio.
7. Retirar `noindex,nofollow` y preparar SEO local.
8. Configurar analítica respetando consentimiento y privacidad.
