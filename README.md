# Academia Web — Login y Registro

## Descripción

Este proyecto amplía **Academia Web** con dos páginas de acceso: un formulario de inicio de sesión y otro de registro de usuarios.

Se creó para ofrecer una interfaz coherente con el sitio principal y practicar la construcción de formularios web, el uso de HTML semántico y el diseño responsivo.

## Tecnologías utilizadas

- **HTML5:** permite estructurar el contenido mediante etiquetas semánticas como `header`, `nav`, `main`, `section`, `article`, `form` y `footer`. También se utiliza para incorporar validaciones nativas en los campos.
- **CSS3:** se utiliza para definir los colores, las tipografías, los espacios, los estados interactivos y la presentación visual de las páginas.
- **Flexbox:** organiza los elementos principales y permite que el footer quede al final de la página cuando el contenido no ocupa toda la pantalla.
- **Media queries:** adaptan la interfaz a distintos tamaños de pantalla, como celulares, tablets y computadoras.
- **Google Fonts:** se utilizan las tipografías Raleway y Rubik para mantener la identidad visual de Academia Web.

## Estructura de archivos

```text
AcademiaWeb/
├── login.html
├── login.css
├── registro.html
├── registro.css
└── README.md
```

## Páginas incluidas

### Inicio de sesión (`login.html`)

Contiene campos para correo electrónico y contraseña. Incluye validaciones HTML básicas y un enlace para ir al formulario de registro.

### Registro (`registro.html`)

Contiene campos para nombre completo, correo electrónico, contraseña y confirmación de contraseña, además de una casilla para aceptar los términos y condiciones. Incluye validaciones HTML básicas y un enlace para volver al inicio de sesión.

## Validaciones

Se utilizan atributos nativos de HTML:

- `required`: obliga a completar los campos.
- `type="email"`: comprueba que el correo tenga un formato válido.
- `minlength`: establece una cantidad mínima de caracteres.
- `type="checkbox"` junto con `required`: exige marcar la casilla de aceptación.

**Importante:** estas validaciones se realizan en el navegador. La coincidencia entre la contraseña y su confirmación requiere JavaScript, y el registro o inicio de sesión real necesita un backend. Los formularios de este proyecto son una interfaz de ejemplo y todavía no guardan ni autentican usuarios.

## Diseño y responsividad

Las páginas mantienen la identidad visual de Academia Web mediante las variables CSS de color, las tipografías y un header y footer compartidos en su apariencia.

El diseño utiliza un enfoque adaptable con media queries para que los formularios y la navegación puedan utilizarse en pantallas pequeñas y grandes.

## Objetivo educativo

Este proyecto permite practicar:

- La creación de formularios con HTML.
- El uso de etiquetas semánticas y atributos de validación.
- La separación del contenido HTML y los estilos CSS.
- La reutilización de una identidad visual.
- La organización de una página con Flexbox.
- La adaptación de interfaces mediante diseño responsivo.
