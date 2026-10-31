<h1 align="center">Franco · Desarrollador Full Stack</h1>

<p align="center">
  <b>Webs, tiendas online y sistemas de gestión a medida,<br>para que tu negocio venda más y trabaje mejor.</b>
</p>

<p align="center">
  <a href="https://wa.me/5493482232529?text=Hola%20Franco%2C%20vi%20tu%20GitHub%20y%20quiero%20consultarte%20por%20un%20proyecto">
    <img src="https://img.shields.io/badge/WhatsApp-Escribime-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>
  <a href="mailto:poncefrancomiguel@gmail.com">
    <img src="https://img.shields.io/badge/Email-Pedime%20presupuesto-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://frannkode.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-Ver%20trabajos-111827?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio">
  </a>
</p>

---

## ⭐ Proyecto destacado · ERP industrial a medida

<p>
  <img src="https://img.shields.io/badge/Desarrollo-m%C3%A1s%20de%201%20a%C3%B1o-4F46E5?style=flat-square" alt="Más de 1 año de desarrollo">
  <img src="https://img.shields.io/badge/Python-370k%2B%20l%C3%ADneas-4F46E5?style=flat-square" alt="370k+ líneas de Python">
  <img src="https://img.shields.io/badge/API-100%2B%20controladores-4F46E5?style=flat-square" alt="100+ controladores de API">
  <img src="https://img.shields.io/badge/Base%20de%20datos-900%2B%20migraciones-4F46E5?style=flat-square" alt="900+ migraciones">
  <img src="https://img.shields.io/badge/Tests-850%2B%20archivos-4F46E5?style=flat-square" alt="850+ archivos de test">
</p>

**Un ERP completo para una industria de alimentos: va desde la producción en planta hasta la contabilidad y los impuestos, todo conectado y con trazabilidad de punta a punta.** Proyecto de equipo, en producción, desarrollado durante más de un año.

**Mi rol: QA y revisión técnica dentro del equipo.**

- Planificación de pruebas por sprint, cruzando datos de Jira con copias de la base de datos para detectar inconsistencias antes de salir a producción.
- Diagnóstico de errores en producción, incluyendo fallas de esquemas y de conectividad con la base de datos gestionada.
- Revisión de pull requests con comentarios técnicos.
- Testing de la app móvil en React Native y depuración de entornos Docker y migraciones.

### Qué cubre el sistema

| Área | Qué resuelve |
|---|---|
| 🏭 **Producción industrial** | Quesería, faena, chacinados y alimentos. Fórmulas versionadas, plantillas de consumo de materia prima, mermas y controles de calidad de leche y producto terminado. |
| 🐖 **Producción primaria** | Campañas, tickets de flujo operativo y activos biológicos con trazabilidad. |
| 📦 **Stock y trazabilidad** | Stock híbrido (contable y operativo, con reservas y en proceso), lotes de producción, producto terminado, merma y stock, recuento físico y costeo FIFO. |
| 📚 **Contabilidad** | Motor de partida doble, movimientos y submovimientos, cierre de mes y períodos, conciliación bancaria, activos fijos y en formación, préstamos, gastos con prorrateo y absorción de costos indirectos. |
| 🧾 **Impuestos y facturación** | Motor fiscal que decide qué impuestos aplican a cada operación, crédito fiscal, Libro IVA, facturación electrónica (CAE) y doble circuito declarado / no declarado en los reportes. |
| 💰 **Tesorería** | Cuentas bancarias, caja, tarjetas y billeteras digitales, cartera de cheques, medios de pago y punto de venta con sesiones de caja y arqueo. |
| 👥 **Socios y sueldos** | Cuenta corriente de socios, aportes y retiros, y liquidación de sueldos con provisiones (SAC, vacaciones e indemnizaciones). |
| 🏷️ **Precios y márgenes** | Un único modelo de formación de precios: costo FIFO, valor agregado entre secciones y márgenes mayorista y minorista, con control de precios de los locales. |
| 🚚 **Logística** | Reparto con ruteo, asignación y pedidos. |
| 📊 **Reportes y KPIs** | Dashboard con tablas, tarjetas y gráficos, exportes a CSV, motor de indicadores, margen bruto y resultado. |
| 🛡️ **Calidad y mantenimiento** | No conformidades ligadas a lotes y mantenimiento de equipos. |
| 🔌 **Integraciones** | Bancos, Google Calendar, liquidación de sueldos externa y el sistema de ventas de los locales (SQL Server). |
| 🔐 **Seguridad** | Usuarios, roles y permisos por sección, con autenticación JWT. |

<details>
<summary><b>🔧 Cómo está construido por dentro</b></summary>

<br>

- **Arquitectura en capas estricta:** Controller → Service → Repository → Model, con clases base genéricas que traen filtros dinámicos, paginación y precarga automática de relaciones.
- **Dinero sin errores de redondeo:** columnas `Numeric` (nunca `Float`) y aritmética monetaria con `Decimal`.
- **Herencia polimórfica** en el módulo contable para compras, ventas y transferencias internas.
- **Más de 900 migraciones** con Alembic y seeders versionados.
- **850+ archivos de tests** con aislamiento por transacción.
- **CI/CD con runner propio**, Docker y un bot de revisión de PRs con IA.
- **Documentación técnica extensa**: reglas de negocio, decisiones de arquitectura y criterios fiscales por escrito.

</details>

<p>
  <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,docker,githubactions,react" alt="Stack del ERP">
</p>

> 🔒 Código privado. Si te interesa algo parecido para tu negocio, escribime.

---

## 🍔 Proyecto destacado · ViciosBurger

Pedidos online para una hamburguesería, pensado para el celular: versión web instalable (PWA) y app móvil en React Native.

<p>
  <a href="https://viciosburgerr.vercel.app">
    <img src="https://img.shields.io/badge/Ver%20en%20vivo-viciosburgerr.vercel.app-4F46E5?style=for-the-badge&logo=vercel&logoColor=white" alt="Ver ViciosBurger en vivo">
  </a>
</p>

Código: [ViciosBurgerApp (PWA)](https://github.com/Frannkode/ViciosBurgerApp) · [ViciosBurger (React Native)](https://github.com/Frannkode/ViciosBurger)

---

## 💼 Qué puedo hacer por tu negocio

- 🛒 **Tiendas online y e-commerce**: desde cero o sobre Tiendanube, con personalizaciones que la plataforma no trae (selectores de packs, SKUs dinámicos, lógica a medida).
- 🧾 **Sistemas de gestión**: punto de venta (POS), control de stock y paneles con estadísticas para decidir con datos.
- 🍔 **Pedidos online para gastronomía**: menú mobile-first, pedidos por WhatsApp y apps de delivery.
- 🌐 **Webs y landing pages**: rápidas, responsive y pensadas para que te contacten.
- 🔧 **Mejoras sobre lo que ya tenés**: arreglos, integraciones y nuevas funciones en tu sitio o sistema actual.

---

## 🚀 Más proyectos

| Proyecto | Qué es |
|---|---|
| [**ReactVicios**](https://github.com/Frannkode/ReactVicios) | Menú mobile-first con pedidos por WhatsApp |
| [**ElCruceRestaurant**](https://github.com/Frannkode/ElCruceRestaurant) | Sitio de restaurante con React y Tailwind v4 |
| [**QuickOrder**](https://github.com/Frannkode/QuickOrder) | Sistema de pedidos en TypeScript |
| [**FullBebidas**](https://github.com/Frannkode/FullBebidas) | E-commerce de bebidas |
| [**Indumentaria**](https://github.com/Frannkode/Indumentaria) | E-commerce de ropa |
| [**MotoPartes**](https://github.com/Frannkode/MotoPartes) | E-commerce de repuestos de moto |

Más trabajos en mi [portfolio](https://frannkode.vercel.app).

---

## 🧰 Tecnologías

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,vite,tailwind,python,fastapi,postgres,docker,firebase,supabase,git,vercel" alt="Stack">
</p>

---

## 🤝 Cómo trabajo

1. **Charlamos y definimos qué necesitás.** Sin tecnicismos, con un alcance claro.
2. **Entregas por etapas.** Ves avances reales y decidimos juntos en cada paso.
3. **Lanzamiento y soporte.** Te acompaño después de publicar.

---

<h3 align="center">¿Tenés un proyecto en mente?</h3>

<p align="center">
  Contame qué necesitás y te respondo con una propuesta.<br><br>
  <a href="https://wa.me/5493482232529?text=Hola%20Franco%2C%20vi%20tu%20GitHub%20y%20quiero%20consultarte%20por%20un%20proyecto">
    <img src="https://img.shields.io/badge/Hablemos%20por%20WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Hablemos por WhatsApp">
  </a>
</p>
