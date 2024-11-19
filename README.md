Sección reseñas

Crear al menos 3 cards en la sección de "Reseñas", utilizando Grid, para organizar al menos tres cards de  manera responsiva.

    1.  Estructura HTML: Asegurate  de tener una estructura básica que incluya una sección para "Reseñas" dentro de <main>, y qe cada reseña esté dentro de un <div> con la clse card.
    2. Aplicar CSS Grid: En el archivo styles.css, aplicá display: grid y grid-template-columns con repeat(auto-fit, minmax(250px, 1fr)) para hacer que las cards sean responsivas y se adapten a la pantalla.
    3. Márgenes y Espaciado: Usá gap para dar espacio entre las cards y padding para que no se  queden pegadas a los bordes del contenedor.
    4. Interactividad: Añadí un efecto de hoverr con transform: translateY(-5px) para que las tarjetas se eleven al pasar el mouse.
    5. Box Model: Aplicá padding, border y box-shadow para darle estructura a las cards y hacerlas más atractivas visualmente

Media Queries

Implementar una media queries en la sección "Contacto" que ajuste el diseño de la página para dispositivos móviles, asegurándote de que el layout de las cards de reseñas se adapte a pantallas más pequeñas

    1. Estructura HTML: Asegurate de tener una estructura básica en el  HTML con la sección de "Contacto" y el formulario correspondiente. Usá etiquetas como <section>, <form>, <input>, y <textarea> para  los campos del formulario.
    2. Media Queries: Implementá las media queries en el archivo styles.css usando @media(max-width: 768px) para ajustar el diseño en pantallas más chicas, como tablets o celulares.
    3. Ajustar Cards: Utilizá grid-template-columns: 1fr en las cards de reseñas para que se apilen en pantallas pequeñas, lo que mejora la legibilidad y el uso en dispositivos móviles.
    4. Forulario Adaptable: Cambiá el padding y los tamaños de los campos del formulario para que se vean más compactos y legibles en dispositivos con menos espacio.
    5. Probar el Diseño: Probá el diseño con las herramientas de desarrollador para asegurarte de que las media queries se activan correctamente y el contenido se adapta a diferentes tamaños de pantalla.