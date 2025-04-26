# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
El diseño visual de Greenlogist debe reflejar sus valores fundamentales: sostenibilidad, eficiencia, confianza y conexión directa entre productores y consumidores conscientes. Adicionalmente, deberá presentar un diseño limpio, con espacios amplios, buena jerarquía visual, alto contraste en botones, textos legibles, íconos comprensibles y una estética amigable pero profesional.

### **Colores**
Los colores escogidos para este producto fueron: Un Verde Natural (#4CAF50) como color principal, el cual refleja sostenibilidad, frescura y es fuertemente asociado con el campo; Beige claro (#F5F5DC) para el fondo de la página; Gris suave (#E0E0E0) para elementos secundarios de la página; Verde oscuro (#2E7D32) para los botones y elementos llamativos; y Negro (#212121) para la tipografía.

![Paleta Referencial](img_graficas/Other/verde.png)

### **Tipografía**
Para la tipografía de la página se eligió Montserrat Bold para los titulares, esto debido a su caracter moderno y a que facilita la legibilidad para el usuario. Asimismo, se hará uso de la tipografía Open Sans Regular para el cuerpo del texto debido a sus accesibilidad. 

### **Tono y comunicación**
La página debe presentar un tono claro, sencillo y positivo, que refleja la personalidad de la marca (confiable, accesible, moderna y comprometida con el cambio). Asimismo, el tono debe estar enfocado en los beneficios del comercio justo, el respeto por el medio ambiente y la colaboración entre actores.

### **Iconografía**
Se emplearán íconos lineales, y minimalistas, relacionados a la agricultura, transporte, geolocalización, sostenibilidad, calificación y contacto.Es importante priorizar su uso moderado para no saturar visualmente, pero sí facilitar la comprensión rápida de funciones.

### 4.1.2. Web Style Guidelines
Las guías de estilo web de Greenlogist aseguran una experiencia visual y funcional coherente, centrada en la usabilidad, accesibilidad y conexión con el usuario. Se alinean con los principios de diseño sostenible, simplicidad funcional y diseño centrado en el usuario.

Se empleará un diseño basado en grid de 12 columnas para flexibilidad y adaptabilidad responsiva.

![Diseño Grid de 12 columnas](img_graficas/Other/grid12.png)

Asimismo, se deberán asegurar márgenes amplios y separación clara entre secciones para evitar saturación visual.

Adicionalmente, el encabezado siempre visible con logo, buscador, categorías y acceso rápido a cuenta/perfil, y se debe establecer un pie de página con enlaces a contacto, redes sociales y certificado de sostenibilidad.

## 4.2 Information Architecture
La arquitectura de la información para Greenlogist se ha estructurado de manera clara y coherente para garantizar una navegación intuitiva tanto en la **Landing Page** como en las **Web Applications** para productores y consumidores. Se ha priorizado la facilidad de acceso a las funcionalidades principales según los perfiles de usuario.

### 4.2.1 Organization Systems

En esta sección, el equipo explica en qué grupos de información aplicará cuáles sistemas de organización. Se incluye la explicación de en qué casos se aplicará la organización visual del contenido: de forma jerárquica (visual hierarchy), organización secuencial (step-by-step to accomplish) o matricial.

**Landing Page:**
*   **Organización jerárquica:** La información se estructura de forma descendente: desde la presentación general de Greenlogist, los beneficios, funciones del producto, los planes hasta los llamados a la acción para registro e inicio de sesión.

![Organigrama Landing Page](img_graficas/OrganigramaLanding.png)

**Web Applications:**
*   **Productores:**
    *   **Organización jerárquica:** Dashboard con acceso directo a funciones clave como Productos, Solicitar Transporte y Estadísticas.
    *   **Organización secuencial:** Creación de un producto nuevo (llenado de formulario paso a paso).
    *   **Organización matricial:** Acceso cruzado entre Productos y Solicitudes de Transporte para gestionar logística de forma integral.
        
*   **Consumidores:**
    *   **Organización jerárquica:** Pantalla de inicio con categorías de productos en orden de prioridad.
    *   **Organización secuencial:** Flujo de compra: selección de productos → carrito → pago → seguimiento.
    *   **Organización matricial:** Posibilidad de navegar entre Productos, Perfil del Productor, y Métricas Ambientales sin perder el contexto.
        
### 4.2.2 Labeling Systems
**Landing Page:**
*   Menú principal con etiquetas claras: "Inicio", "Para Productores", "Para Consumidores", "Beneficios", "Regístrate", "Iniciar Sesión".
*   Botones de acción llamativos como "Únete como Productor" y "Compra Productos Orgánicos".
    
**Web Applications:**
*   Menú personalizado dependiendo del perfil.
*   Etiquetas simples y orientadas a la acción, por ejemplo:
    *   "Añadir Producto"
    *   "Solicitar Transporte"
    *   "Mis Estadísticas"
    *   "Carrito"
    *   "Seguimiento de Pedido"
    *   "Reseñar Pedido"
        
### 4.2.3 SEO Tags and Meta Tags

**Landing Page:**
*   Títulos y meta descripciones optimizados para palabras clave como "Beneficios", "Planes", "Características".
*   Etiquetas Open Graph para mejor visualización en redes sociales.
    
**Web Applications:**
*   Páginas internas optimizadas para búsquedas específicas como "comprar productos orgánicos en Perú" o "distribuir productos ecológicos".
*   Etiquetas específicas por tipo de usuario.
    
### 4.2.4 Searching Systems
**Landing Page:**
*   No requiere buscador interno debido a su enfoque informativo.

**Web Applications:**
*   **Consumidores:**
    *   Buscador de productos por nombre, categoría o productor.
    *   Filtros por tipo de producto, certificaciones, precios y distancia de entrega.
        
*   **Productores:**
    *   Buscador interno para gestión de productos.

### 4.2.5 Navigation Systems
**Landing Page:**
*   Menú principal fijo y accesible en todo momento.
*   Botones directos hacia registro.
    
**Web Applications:**
*   **Productores:**
    *   Menú superior persistente.
    *   Acceso rápido a creación de productos, solicitudes de transporte y estadísticas.
        
*   **Consumidores:**
    *   Menú superior con acceso a Home, Carrito, Seguimiento y Perfil.
    *   Breadcrumbs para regresar al catálogo desde páginas de detalle de producto.


## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
Aquí se mostrarán los wireframes para cada sección presente en nuestra lannding page.

![Encabezado](img_graficas/LandingPage/Wireframes/1.PNG)

![Características](img_graficas/LandingPage/Wireframes/2.PNG)

![Planes](img_graficas/LandingPage/Wireframes/3.PNG)

![Registro](img_graficas/LandingPage/Wireframes/4.PNG)

![Quienes somos](img_graficas/LandingPage/Wireframes/5.PNG)

![Info](img_graficas/LandingPage/Wireframes/6.PNG)

![Contacto y footer](img_graficas/LandingPage/Wireframes/7.PNG)


### 4.3.1. Landing Page Mockup
En esta sección se mostrará los mockups para nuestra landing, tomando en cuenta las pautas de estilo anteriormente detalladas.

![Encabezado](img_graficas/LandingPage/Mockups/1.PNG)

![Características](img_graficas/LandingPage/Mockups/2.PNG)

![Planes](img_graficas/LandingPage/Mockups/3.PNG)

![Registro](img_graficas/LandingPage/Mockups/4.PNG)

![Quienes somos](img_graficas/LandingPage/Mockups/5.PNG)

![Info](img_graficas/LandingPage/Mockups/6.PNG)

![Contacto y footer](img_graficas/LandingPage/Mockups/7.PNG)

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes

![Encabezado](img_graficas/WebApps/Wireframes/1inicio.PNG)

![Encabezado](img_graficas/WebApps/Wireframes/2Registro.PNG)

![Encabezado](img_graficas/WebApps/Wireframes/3dashboard_productores.PNG)

![Encabezado](img_graficas/WebApps/Wireframes/4Registrar_producto.PNG)

![Encabezado](img_graficas/WebApps/Wireframes/5solicitar_transporte.PNG)

![Encabezado](img_graficas/WebApps/Wireframes/6estadisticas.PNG)

![Encabezado](img_graficas/WebApps/Wireframes/7perfil_del_productor.PNG)

![Encabezado](img_graficas/WebApps/Wireframes/8consumidor_home.PNG)

![Encabezado](img_graficas/WebApps/Wireframes/9consumidor_detalles_productor.PNG)

![Encabezado](img_graficas/WebApps/Wireframes/10consumidor_carrito.PNG)

![Encabezado](img_graficas/WebApps/Wireframes/11consumidor_seguimiento.PNG)

![Encabezado](img_graficas/WebApps/Wireframes/consumidor_historial_y_reseña_1.PNG)

![Encabezado](img_graficas/WebApps/Wireframes/consumidor_historial_y_reseña_2.PNG)

### 4.4.2. Web Applications Wireflow Diagrams

### 4.4.3. Web Applications Mock-ups

### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

[Pendiente]


