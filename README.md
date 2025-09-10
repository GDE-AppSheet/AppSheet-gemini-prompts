<img width="775" height="263" alt="Logo-ESC-2020-hor2" src="https://github.com/user-attachments/assets/85c51d3e-d953-43bb-8cde-d7c033aa2b0b" />
 #🚀 Guía Definitiva para la Creación de Prompts en AppSheet

Este repositorio es una guía completa y un catálogo de ejemplos para crear aplicaciones en AppSheet utilizando su función de generación por IA a través de "prompts" o instrucciones de texto. Un prompt bien estructurado es la diferencia entre obtener una aplicación básica que requiere mucho trabajo y una base sólida y funcional que acelera el desarrollo exponencialmente.

El objetivo de este documento es servir como un recurso de referencia para cualquiera que desee maximizar el potencial de la IA de AppSheet. 🎯

---

## 🗺️ Tabla de Contenidos
* [📜 Guía Paso a Paso para Generar Prompts Efectivos](#-guía-paso-a-paso-para-generar-prompts-efectivos)
  * [💡 Paso 1: Definir el Núcleo](#-paso-1-definir-el-núcleo-el-qué)
  * [👥 Paso 2: Identificar a los Usuarios](#-paso-2-identificar-a-los-usuarios-el-quién)
  * [🗃️ Paso 3: Listar las Entidades Principales](#-paso-3-listar-las-entidades-principales-los-sustantivos)
  * [⚙️ Paso 4: Detallar las Funcionalidades](#-paso-4-detallar-las-funcionalidades-y-acciones-los-verbos)
  * [🔗 Paso 5: Considerar Integraciones](#-paso-5-considerar-integraciones-y-funciones-avanzadas-el-plus)
* [📋 Catálogo de 21 Prompts de Ejemplo](#-catálogo-de-21-prompts-de-ejemplo-para-appsheet)
  * [🟢 Nivel Básico](#-nivel-básico-aplicaciones-para-empezar)
  * [🟡 Nivel Intermedio](#-nivel-intermedio-aplicaciones-conectadas-y-con-lógica)
  * [🔴 Nivel Avanzado](#-nivel-avanzado-soluciones-empresariales-integrales)
* [🤝 Cómo Contribuir](#-cómo-contribuir)
---
## 📜 Guía Paso a Paso para Generar Prompts Efectivos

Piensa en el prompt no como una simple idea, sino como el **plano de construcción** que le entregas a un asistente experto (la IA de AppSheet). Sigue estos pasos para construir un plano claro y detallado.

### 💡 Paso 1: Definir el Núcleo (El "Qué")
Empieza con una frase clara y concisa que describa el propósito principal de la aplicación. ¿Qué problema fundamental va a resolver?

* **Pregunta clave:** ¿Para qué es esta aplicación?
* **Ejemplos:**
    * "Crear una app para gestionar el inventario de una bodega."
    * "Diseñar una app para realizar seguimiento de proyectos de construcción."

### 👥 Paso 2: Identificar a los Usuarios (El "Quién")
Define quiénes usarán la aplicación. Esto ayuda a AppSheet a pensar en roles, permisos y diferentes tipos de vistas (por ejemplo, una vista para administradores y otra para empleados).

* **Pregunta clave:** ¿Quién va a usar esta app y en qué rol?
* **Ejemplos:**
    * "...para el equipo de logística y los gerentes de almacén."
    * "...para jefes de obra, inspectores y clientes."

### 🗃️ Paso 3: Listar las Entidades Principales (Los "Sustantivos")
Piensa en las "cosas" o los conceptos principales que necesitas rastrear o gestionar. Estas se convertirán en las **tablas** de tu base de datos.

* **Pregunta clave:** ¿Qué información o elementos clave necesito gestionar?
* **Ejemplos:**
    * **Inventario:** Productos, Proveedores, Pedidos de compra, Entradas y Salidas.
    * **Construcción:** Proyectos, Tareas, Hitos, Reportes de Avance, Fotos.

### ⚙️ Paso 4: Detallar las Funcionalidades y Acciones (Los "Verbos")
Esta es la parte más importante. Describe las acciones que los usuarios podrán realizar. Usa verbos de acción y sé lo más específico posible.

* **Pregunta clave:** ¿Qué podrán hacer los usuarios con los datos?
* **Ejemplos:**
    * **Inventario:** *Escanear* códigos de barras, *recibir* alertas automáticas de bajo stock, *generar* órdenes de compra.
    * **Construcción:** *Asignar* tareas, *actualizar* el estado de un proyecto, *adjuntar* fotos a un reporte, *firmar* digitalmente.

### 🔗 Paso 5: Considerar Integraciones y Funciones Avanzadas (El "Plus")
Si necesitas que tu app se conecte con otras herramientas o tenga capacidades especiales, menciónalo.

* **Pregunta clave:** ¿Necesita la app interactuar con otros sistemas o usar funciones especiales del dispositivo?
* **Ejemplos:**
    * "Generar un archivo PDF con el resumen del pedido y enviarlo por correo."
    * "Usar la ubicación GPS para registrar dónde se realiza una inspección."
    * "Integrar con Google Calendar para agendar las tareas."

---

## 📋 Catálogo de 21 Prompts de Ejemplo para AppSheet

Aquí tienes una colección de prompts listos para usar, clasificados por complejidad.

### 🟢 Nivel Básico: Aplicaciones para Empezar
*Aplicaciones ideales para digitalizar un solo proceso. Fáciles de usar y centradas en resolver una tarea específica.*

#### 1. Directorio de Empleados 👤
* **💬 Prompt:**
    > "Crear una aplicación para **todos los empleados** para que sirva como un **directorio de contactos centralizado**. La app debe gestionar una lista de **Empleados** (con nombre, cargo, email, teléfono) y su **Departamento**. Debe permitir a los usuarios **buscar** por nombre o departamento y **hacer clic** para llamar o enviar un correo."
* **🎁 ¿Qué obtendrás?**
    Una "agenda de contactos" interna de la empresa. Tendrás una pantalla principal con la lista de todos los empleados, una barra de búsqueda para encontrar a alguien rápidamente y botones de acción para iniciar una llamada o un correo.

#### 2. Seguimiento de Tareas Sencillas ✅
* **💬 Prompt:**
    > "Diseñar una app para **equipos pequeños** para **gestionar tareas diarias**. La aplicación debe manejar una lista de **Tareas** con descripción, fecha de vencimiento, prioridad (Alta, Media, Baja) y estado (Pendiente, En Progreso, Completada). Los usuarios deben poder **crear**, **asignar** y **actualizar** el estado de las tareas."
* **🎁 ¿Qué obtendrás?**
    Un tablero de tareas digital tipo "To-Do List". Verás las tareas organizadas y podrás cambiar su estado con un solo clic. Perfecta para reemplazar post-its o una hoja de cálculo simple.

#### 3. Registro de Gastos de Viaje 💸
* **💬 Prompt:**
    > "Crear una app para **empleados que viajan** para **registrar sus gastos de manera sencilla**. La app debe gestionar **Gastos**, permitiendo **ingresar** fecha, monto, categoría (transporte, comida, hotel) y **adjuntar una foto del recibo** usando la cámara del teléfono."
* **🎁 ¿Qué obtendrás?**
    Una bitácora de gastos digital en tu bolsillo. La app tendrá un botón para "Añadir Gasto", donde llenas los detalles, tomas una foto del recibo y guardas. Todo quedará en un historial organizado.

#### 4. Checklist de Inspección de Seguridad 🛡️
* **💬 Prompt:**
    > "Diseñar una aplicación para **supervisores de seguridad** para realizar **inspecciones diarias**. La app debe contener un **Checklist de Inspección** con ítems a verificar (Sí/No/NA). El supervisor debe poder **completar** el formulario, **añadir comentarios** y **registrar su firma digital**."
* **🎁 ¿Qué obtendrás?**
    Un formulario de inspección digital que reemplaza el papel. El supervisor podrá marcar cada punto, tomar fotos si hay anomalías y firmar directamente en la pantalla del teléfono.

#### 5. Registro de Visitantes para Recepción 👋
* **💬 Prompt:**
    > "Crear una aplicación para la **recepción** para **modernizar el registro de visitantes**. La app debe tener un formulario para registrar **Visitantes**, capturando nombre, empresa y persona a la que visita. Debe mostrar una **lista cronológica** de los visitantes del día y permitir **marcar la hora de salida**."
* **🎁 ¿Qué obtendrás?**
    Un libro de visitas digital y profesional. La tableta de recepción tendrá un formulario limpio y mostrará una lista en tiempo real de quién está actualmente en el edificio.

#### 6. Inventario Básico de Suministros de Oficina 📎
* **💬 Prompt:**
    > "Diseñar una app para el **personal administrativo** para **controlar el inventario de suministros de oficina**. La app debe gestionar una lista de **Suministros** y su cantidad. Debe permitir **actualizar rápidamente** la cantidad y tener una vista que resalte los suministros con **stock bajo**."
* **🎁 ¿Qué obtendrás?**
    Un controlador de stock para la papelería. Tendrás una lista de suministros con su cantidad actual y la app usará colores (como rojo) para señalar visualmente los artículos que están por agotarse.

#### 7. Reserva de Salas de Juntas 🗓️
* **💬 Prompt:**
    > "Crear una app para **todos los empleados** para **reservar salas de juntas**. La aplicación debe gestionar **Salas** y **Reservas**. Los usuarios deben poder **ver la disponibilidad** de las salas en un calendario, **seleccionar un horario** y **crear una reserva**."
* **🎁 ¿Qué obtendrás?**
    Un sistema de calendario visual para las salas. Podrás ver qué salas están ocupadas y a qué hora. Para reservar, solo tendrás que tocar un espacio libre en el calendario y llenar un breve formulario.

### 🟡 Nivel Intermedio: Aplicaciones Conectadas y con Lógica
*Aplicaciones que manejan varios tipos de información relacionados entre sí e incluyen automatizaciones simples como notificaciones.*

#### 1. Gestión de Proyectos 📊
* **💬 Prompt:**
    > "Crear una app para **gerentes y equipos** para **planificar y seguir proyectos**. La app debe gestionar **Proyectos**, **Tareas** (vinculadas a un proyecto) y **Miembros del Equipo**. Permitirá a los gerentes **crear proyectos**, **asignar tareas** y **visualizar el avance**. Los miembros podrán **actualizar el estado** de sus tareas."
* **🎁 ¿Qué obtendrás?**
    Un centro de control de proyectos. Los gerentes verán una lista de todos los proyectos y, al entrar en uno, verán todas sus tareas asociadas. Los miembros del equipo tendrán una vista personal de "Mis Tareas".

#### 2. CRM de Ventas y Seguimiento de Clientes 💼
* **💬 Prompt:**
    > "Diseñar una app para el **equipo de ventas** para **gestionar clientes y oportunidades**. La app debe gestionar **Clientes**, **Contactos** y **Oportunidades de Venta**. Permitirá **registrar** oportunidades, **agendar actividades** y **actualizar la etapa** de la venta."
* **🎁 ¿Qué obtendrás?**
    Una herramienta de ventas móvil. Cada vendedor podrá ver su lista de clientes, sus oportunidades de venta asociadas y mover una oportunidad de una etapa a otra (ej. "Propuesta Enviada").

#### 3. Gestión de Activos de TI 💻
* **💬 Prompt:**
    > "Crear una aplicación para **TI** para **rastrear los activos tecnológicos**. La app debe manejar **Activos** (laptops, teléfonos), **Empleados** y **Registros de Mantenimiento**. Debe permitir **asignar** un activo a un empleado, **registrar** mantenimientos y **usar el escáner de códigos de barras**."
* **🎁 ¿Qué obtendrás?**
    Un inventario inteligente de tecnología. Cada equipo tendrá su "historial de vida": a quién está asignado, cuándo se le hizo mantenimiento, etc. Con el teléfono, podrás escanear su código de barras y ver toda su información al instante.

#### 4. Solicitudes de Vacaciones y Ausencias 🌴
* **💬 Prompt:**
    > "Diseñar una app para **empleados y RRHH** para **gestionar solicitudes de vacaciones**. Los empleados pueden **enviar solicitudes**. Los gerentes o RRHH reciben una **notificación por email** para **aprobar o rechazar**, lo que actualiza el estado y notifica al empleado."
* **🎁 ¿Qué obtendrás?**
    Un flujo automatizado para pedir vacaciones. El empleado llena un formulario, su jefe recibe un correo con botones ("Aprobar"/"Rechazar") y el sistema se actualiza solo, notificando a ambas partes.

#### 5. Gestión de Órdenes de Compra 🛒
* **💬 Prompt:**
    > "Crear una app para el **departamento de compras** para **crear y seguir órdenes de compra**. La app debe gestionar **Proveedores**, **Catálogo de Productos** y **Órdenes de Compra**. Los usuarios podrán **crear** una orden, **añadir productos** y **enviar la orden por PDF** al proveedor."
* **🎁 ¿Qué obtendrás?**
    Una herramienta para agilizar las compras. Podrás seleccionar un proveedor, elegir productos de una lista y generar una orden de compra profesional en PDF, lista para ser enviada por correo desde la app.

#### 6. Partes de Trabajo para Servicio en Campo 🚚
* **💬 Prompt:**
    > "Diseñar una app para **técnicos de campo** para **gestionar órdenes de servicio**. La app debe gestionar **Clientes** y **Órdenes de Trabajo**. Los técnicos podrán **ver sus órdenes asignadas**, **navegar a la ubicación**, **registrar el trabajo** con notas/fotos, y **capturar la firma de conformidad** del cliente."
* **🎁 ¿Qué obtendrás?**
    La oficina móvil para el técnico. Verá su ruta del día, documentará el trabajo realizado con fotos y el cliente podrá firmar en la pantalla, generando un reporte de servicio digital completo.

#### 7. Control de Flotilla Vehicular 🚗
* **💬 Prompt:**
    > "Crear una app para el **administrador de flotilla** para **gestionar los vehículos**. La app debe gestionar **Vehículos**, **Conductores** y **Bitácoras de Mantenimiento**. Debe permitir **asignar** vehículos, **registrar inspecciones** y **llevar un historial** de servicios."
* **🎁 ¿Qué obtendrás?**
    La "hoja de vida" de cada vehículo de la empresa. La app recordará cuándo toca el próximo mantenimiento y los conductores podrán reportar incidencias a través de un formulario, adjuntando fotos.

### 🔴 Nivel Avanzado: Soluciones Empresariales Integrales
*Sistemas completos que gestionan procesos complejos, integran varias áreas de un negocio y utilizan funciones avanzadas.*

#### 1. Gestión de Inventario y Ventas (Mini ERP) 🏭
* **💬 Prompt:**
    > "Crear una solución para una **PYME** para **integrar inventario, compras y ventas**. La app debe gestionar **Productos** (con control de stock), **Proveedores**, **Órdenes de Compra**, **Clientes** y **Órdenes de Venta**. Al **recibir una compra**, el stock debe **aumentar automáticamente**. Al **registrar una venta**, el stock debe **disminuir**. Incluir un dashboard para gerentes."
* **🎁 ¿Qué obtendrás?**
    Un pequeño sistema de gestión empresarial. Cuando compras ingresa mercancía, el stock se actualiza. Cuando ventas registra un pedido, el stock se descuenta. Un gerente podrá ver en un panel gráfico las ventas del día y qué productos necesitan ser reordenados.

#### 2. Logística y Seguimiento de Entregas 📦
* **💬 Prompt:**
    > "Diseñar una app para una **empresa de logística** con roles para **administradores y conductores**. La app debe gestionar **Paquetes**, **Rutas** y **Conductores**. Los conductores podrán **escanear paquetes**, **actualizar el estado** de la entrega en tiempo real y **capturar prueba de entrega** con foto y firma."
* **🎁 ¿Qué obtendrás?**
    Un centro de control logístico completo. El administrador en la oficina asignará rutas y verá el estado de cada entrega. El conductor usará su teléfono para escanear y actualizar el estado, y la foto y firma del cliente quedarán como prueba del servicio.

#### 3. Sistema de Mantenimiento de Instalaciones 🛠️
* **💬 Prompt:**
    > "Crear una app para **equipos de mantenimiento** para gestionar **mantenimiento preventivo y correctivo**. La app debe gestionar **Activos/Equipos** (identificables por código QR), **Planes de Mantenimiento** y **Órdenes de Trabajo**. Los técnicos podrán **escanear un código QR** en un equipo para ver su historial y crear una orden de trabajo."
* **🎁 ¿Qué obtendrás?**
    Un sistema inteligente de mantenimiento. Cada máquina tendrá un código QR. Al escanearlo, el técnico verá toda su historia. Si hay un problema, creará una orden de trabajo ahí mismo que llegará al supervisor para que la asigne.

#### 4. Control de Calidad en Línea de Producción 🔬
* **💬 Prompt:**
    > "Diseñar una app para **inspectores de calidad** para **realizar controles**. La app debe gestionar **Productos**, **Lotes** y **Reportes de Inspección**. Los inspectores seguirán **checklists dinámicos**. Si se encuentra una **No Conformidad**, se podrá **documentar con fotos** y **crear automáticamente una tarea de Acción Correctiva**."
* **🎁 ¿Qué obtendrás?**
    Un guardián digital de la calidad. Si el inspector encuentra una pieza defectuosa, tomará una foto y generará un reporte de "No Conformidad". Automáticamente, el sistema creará una tarea para el supervisor de producción, notificándole que debe tomar acción.

#### 5. Auditoría de Tiendas y Cumplimiento de Franquicias 🏪
* **💬 Prompt:**
    > "Crear una app para **auditores regionales** para **evaluar el cumplimiento en tiendas**. La app debe gestionar **Tiendas** y **Cuestionarios de Auditoría** (con secciones y puntajes). Al finalizar, la app **calculará un puntaje** y **generará un reporte en PDF** que se envía automáticamente."
* **🎁 ¿Qué obtendrás?**
    Una herramienta de auditoría profesional. Al terminar la evaluación, la app generará un informe en PDF con resultados, fotos y un plan de acción, y lo enviará por correo al gerente de la tienda y a la central.

#### 6. Gestión Integral de Eventos Corporativos 🎉
* **💬 Prompt:**
    > "Diseñar una app para **organizadores y asistentes** de una conferencia. Los organizadores gestionan la **Agenda**. Los asistentes pueden **inscribirse**, **crear su agenda personal**, **participar en encuestas en vivo** y **hacer networking** escaneando los códigos QR de otros asistentes."
* **🎁 ¿Qué obtendtás?**
    La aplicación oficial de tu evento. Será una guía interactiva para ver horarios, votar en encuestas en vivo y escanear códigos QR de otros asistentes para intercambiar contactos digitalmente.

#### 7. Gestión de Propiedades Inmobiliarias 🏡
* **💬 Prompt:**
    > "Crear una app para **administradores de propiedades e inquilinos**. La app gestiona **Propiedades**, **Inquilinos** y **Contratos**. Los administradores **rastrean pagos** y **gestionan solicitudes de mantenimiento**. Los inquilinos pueden **enviar solicitudes** con fotos y **recibir notificaciones**."
* **🎁 ¿Qué obtendrás?**
    Un portal de comunicación centralizado. Si un inquilino tiene una fuga, abrirá la app y enviará la solicitud con fotos. El administrador la recibirá formalmente para gestionarla. El sistema también podrá enviar recordatorios automáticos de pago.
