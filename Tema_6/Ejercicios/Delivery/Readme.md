## API para Plataforma de Delivery de Comida

### Descripción
Diseña una API REST para una plataforma de delivery de comida. La API debe gestionar la interacción entre usuarios, restaurantes y el sistema de pagos, permitiendo un flujo eficiente desde la búsqueda de restaurantes hasta la confirmación del pedido.

### Funcionalidades para Usuarios
- **Exploración de restaurantes y menús:** Permitir la búsqueda de restaurantes por ubicación, tipo de cocina y otros filtros que consideres apropiados; visualizar menús con información detallada de cada plato. Los menus están asociados siempre a un restaurante. No se concibe, a nivel API, la consulta de un menú fuera de la consulta de un restaurante.
- **Realización de pedidos:** Facilitar la creación de pedidos seleccionando platos del menú de un restaurante.
- **Gestión de pedidos:** Permitir la cancelación o modificación de pedidos antes de su preparación o confirmación.
- **Seguimiento de pedidos:** Proveer un sistema de seguimiento en tiempo real del estado del pedido.
- **Registro de pagos:** Integrar la funcionalidad para registrar y gestionar el pago de los pedidos realizados.

### Funcionalidades para Restaurantes
- **Gestión de menú:** Permitir a los restaurantes añadir, modificar y eliminar platos de su menú.
- **Control de disponibilidad:** Actualizar el estado de cada plato (disponible o agotado) en función del stock y la demanda.
- **Administración de pedidos:** Confirmar, preparar y actualizar el estado de los pedidos recibidos a través de la plataforma.

---
