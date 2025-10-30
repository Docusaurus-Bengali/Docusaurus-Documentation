---
sidebar_position: 5
---

# Store Users

**Para acceder se debe loguear con las credenciales correctas, el módulo se encuentra en la barra lateral izquierda al ingresar se despliega una interfaz con tres pestañas principales en la parte superior**

- **Customers**
- **Leads**
- **Ecosystems**

---

**El módulo Store Users permite gestionar los usuarios registrados en la plataforma, diferenciando entre **Customers** "clientes con suscripción" y **Leads** "usuarios registrados sin suscripción".**

**Desde este módulo es posible buscar, filtrar, exportar información en formato `XLS`**
**activar o suspender accesos según sea necesario.**

![Store Users](/img/backoffice-user/store_users_backoffice.png)

### 1. Customers

> **Usuarios Customer**: son aquellos clientes que han comprado una suscripción en Waizant Store.  
> Un Customer puede o no haber desplegado su ecosistema, y desde esta sección los administradores pueden consultar el estado de la suscripción, la información detallada del ecosistema y administrar el acceso de forma rápida según se requiera.

Dentro de esta sección es posible:

- **Visualizar el despliegue del ecosistema**:

  - Si el cliente ya desplegó su ecosistema, aparece el **nombre del ecosistema** en la columna _Ecosystem Name_.
  - Si aún no lo ha desplegado, se mostrará como **No complete**.

- **Administrar accesos** con el botón **Active**, que permite **activar o suspender de forma inmediata** el acceso al ecosistema del cliente.

  > Ejemplo: si se presenta un inconveniente a nivel de politicas y privacidad, o se esta haciendo algo indevido, por alguna situación que se presente se tiene ese acceso rápido para suspender el acceso a su ecosistema a los usuarios del ecosistema, del customer que se este activando o desactivando van a tener ese impacto, ese es el acceso rapido para activar o suspender si el core de Waizant lo amerita.

![Customers List](/img/backoffice-user/customer_list_store_user_backoffice.png)

---

### Modal de detalle Action

Al dar clic en el botón **Action**, se abre una ventana modal que muestra información completa de la suscripción del cliente, entre la que se incluye:

- Tipo de suscripción (**mensual o anual**).
- Estado actual de la suscripción.
- Fecha de inicio y fecha de finalización.
- Ecosistema asociado al cliente.
- Número de **encounters**.
- Cantidad y estado de las **licencias** disponibles.

Esta vista ofrece al administrador una visión detallada y centralizada de la información de cada cliente.

![Modal Action](/img/backoffice-user/modal_store_user_action_backoffice.png)

---

### 2. Leads

Son los usuarios que se registraron en la plataforma de Waizant Store pero **no adquirieron una suscripción**.  
Estos se listan en el módulo con el fin de que sus datos puedan exportarse y ser utilizados en campañas de marketing que incentiven la compra de planes o suscripciones.

![Leads List](/img/backoffice-user/leads_list_store_user_backoffice.png)

---

## Funcionalidades del módulo

### Search

Permite realizar búsquedas rápidas de usuarios por **First Name, Last Name, Company Email, Phone Number Company Name.**

![Search Store User](/img/backoffice-user/searh_store_user_backoffice.png)

---

### Exportación

En la parte superior derecha existe la opción para descargar los listados de **Customers** o **Leads** en archivo `XLS`.

![download Store User](/img/backoffice-user/download-list-customer.png)

---

### Paginación

En ambos listados (Customers y Leads) se encuentra un sistema de **paginado** que facilita la navegación cuando hay un gran número de usuarios.

![pagination Store User](/img/backoffice-user/pagination-list-customer.png)

---

### 3. Ecosystems

**El módulo Ecosystems List muestra el listado de los ecosistemas que han sido adquiridos o que se encuentran en proceso de adquisición dentro de la plataforma. Cada ecosistema representa un entorno configurado por un cliente, ya sea en periodo de prueba o con un plan activo.**

**Desde esta sección, el usuario puede visualizar la información general de cada ecosistema, incluyendo el nombre del cliente, la empresa asociada, el tipo de plan y el estado del ecosistema.**

![ecosystems Store User](/img/backoffice-user/image_ecosystem_store_users.png)

**Cuenta con una barra de búsqueda que permite filtrar los ecosistemas ingresando el nombre del cliente o correo electrónico, facilitando así la localización de registros específicos.**

**En la parte superior se encuentran las pestañas Customers, Leads y Ecosystems, que organizan la información según el tipo de relación o estado del usuario dentro del sistema.**

- **Ecosystem Name: Nombre asignado al ecosistema.**
- **Customer: Nombre del cliente asociado.**
- **Company Name: Nombre de la empresa vinculada al ecosistema.**
- **Company Email: Correo electrónico de contacto.**
- **Plan Name: Tipo de plan adquirido Free, Lite, Plus, Premium.**
- **Ecosystem Type: Indica si el ecosistema corresponde a un periodo de prueba Free trial o a un plan con pago activo Payment.**
- **Action: Botón View que abre una ventana modal con los datos detallados del ecosistema seleccionado, en esta ventana se muestra información específica como el nombre del cliente, la empresa asociada, el tipo de plan, el estado del ecosistema y otros datos relevantes para su gestión.**

![ecosystems Store User](/img/backoffice-user/modal_view_action.png)

**Además, dispone de un botón “Download.xls”, que permite exportar la información del listado en formato Excel para análisis o respaldo externo.**

**En la parte inferior, el paginador muestra la cantidad total de registros disponibles y permite desplazarse entre las diferentes páginas de resultados.**
