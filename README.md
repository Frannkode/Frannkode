<p align="center">
  <img src="./assets/banner.svg" width="100%" alt="Franco, desarrollador full stack. Webs, tiendas online y sistemas a medida, para que tu negocio venda más y trabaje mejor.">
</p>

<p align="center">
  <a href="https://wa.me/5493482232529?text=Hola%20Franco%2C%20vi%20tu%20GitHub%20y%20quiero%20consultarte%20por%20un%20proyecto">
    <img src="https://img.shields.io/badge/WhatsApp-Escribime-3342C9?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Escribime por WhatsApp">
  </a>
  <a href="mailto:poncefrancomiguel@gmail.com">
    <img src="https://img.shields.io/badge/Email-Pedime%20presupuesto-16203A?style=for-the-badge&logo=gmail&logoColor=white" alt="Pedime presupuesto por email">
  </a>
  <a href="https://frannkode.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-Ver%20trabajos-16203A?style=for-the-badge&logo=vercel&logoColor=white" alt="Ver mi portfolio">
  </a>
</p>

<img src="./assets/divisor.svg" width="100%" alt="">

## ERP industrial a medida

Un ERP completo para una industria de alimentos: va desde la producción en planta hasta la contabilidad y los impuestos, con trazabilidad de punta a punta. Proyecto de equipo, en producción, desarrollado durante más de un año. Tiene más de 370 mil líneas de Python, más de 900 migraciones de base de datos y más de 850 archivos de test.

<p align="center">
  <img src="./assets/erp-flujo.svg" width="100%" alt="Cadena del ERP: producción, stock, contabilidad, impuestos y reportes. Alrededor: tesorería, sueldos, socios, precios, reparto e integraciones.">
</p>

**Mi rol: QA y revisión técnica dentro del equipo.**

- Planificación de pruebas por sprint, cruzando datos de Jira con copias de la base para detectar inconsistencias antes de salir a producción.
- Diagnóstico de errores en producción, incluyendo fallas de esquemas y de conectividad con la base de datos gestionada.
- Revisión de pull requests con comentarios técnicos.
- Testing de la app móvil en React Native y depuración de entornos Docker y migraciones.

<details>
<summary><b>Todo lo que cubre el sistema (13 áreas)</b></summary>

<br>

| Área | Qué resuelve |
|---|---|
| **Producción industrial** | Quesería, faena, chacinados y alimentos. Fórmulas versionadas, plantillas de consumo de materia prima, mermas y controles de calidad de leche y producto terminado. |
| **Producción primaria** | Campañas, tickets de flujo operativo y activos biológicos con trazabilidad. |
| **Stock y trazabilidad** | Stock híbrido (contable y operativo, con reservas y en proceso), lotes de producción, producto terminado, merma y stock, recuento físico y costeo FIFO. |
| **Contabilidad** | Motor de partida doble, movimientos y submovimientos, cierre de mes y períodos, conciliación bancaria, activos fijos y en formación, préstamos, gastos con prorrateo y absorción de costos indirectos. |
| **Impuestos y facturación** | Motor fiscal que decide qué impuestos aplican a cada operación, crédito fiscal, Libro IVA, facturación electrónica (CAE) y doble circuito declarado / no declarado en los reportes. |
| **Tesorería** | Cuentas bancarias, caja, tarjetas y billeteras digitales, cartera de cheques, medios de pago y punto de venta con sesiones de caja y arqueo. |
| **Socios y sueldos** | Cuenta corriente de socios, aportes y retiros, y liquidación de sueldos con provisiones (SAC, vacaciones e indemnizaciones). |
| **Precios y márgenes** | Un único modelo de formación de precios: costo FIFO, valor agregado entre secciones y márgenes mayorista y minorista, con control de precios de los locales. |
| **Logística** | Reparto con ruteo, asignación y pedidos. |
| **Reportes y KPIs** | Dashboard con tablas, tarjetas y gráficos, exportes a CSV, motor de indicadores, margen bruto y resultado. |
| **Calidad y mantenimiento** | No conformidades ligadas a lotes y mantenimiento de equipos. |
| **Integraciones** | Bancos, Google Calendar, liquidación de sueldos externa y el sistema de ventas de los locales (SQL Server). |
| **Seguridad** | Usuarios, roles y permisos por sección, con autenticación JWT. |

</details>

<details>
<summary><b>Cómo está construido por dentro</b></summary>

<br>

- **Arquitectura en capas estricta:** Controller, Service, Repository y Model, con clases base genéricas que traen filtros dinámicos, paginación y precarga automática de relaciones.
- **Dinero sin errores de redondeo:** columnas `Numeric` (nunca `Float`) y aritmética monetaria con `Decimal`.
- **Herencia polimórfica** en el módulo contable para compras, ventas y transferencias internas.
- **Más de 900 migraciones** con Alembic y seeders versionados.
- **Más de 850 archivos de test** con aislamiento por transacción.
- **CI/CD con runner propio**, Docker y un bot de revisión de PRs con IA.
- **Documentación técnica extensa:** reglas de negocio, decisiones de arquitectura y criterios fiscales por escrito.

</details>

<p>
  <img src="https://img.shields.io/badge/Python-16203A?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-16203A?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-16203A?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Docker-16203A?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub%20Actions-16203A?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/React%20Native-16203A?style=flat-square&logo=react&logoColor=white" alt="React Native">
</p>

El código es privado. Si necesitás algo parecido para tu negocio, escribime.

<img src="./assets/divisor.svg" width="100%" alt="">

## ViciosBurger, pedidos online para hamburguesería

Pensado para el celular: versión web instalable (PWA) y app móvil en React Native.

<p>
  <a href="https://viciosburgerr.vercel.app">
    <img src="https://img.shields.io/badge/Ver%20en%20vivo-viciosburgerr.vercel.app-3342C9?style=for-the-badge&logo=vercel&logoColor=white" alt="Ver ViciosBurger en vivo">
  </a>
</p>

Código: [ViciosBurgerApp (PWA)](https://github.com/Frannkode/ViciosBurgerApp) y [ViciosBurger (React Native)](https://github.com/Frannkode/ViciosBurger).

<img src="./assets/divisor.svg" width="100%" alt="">

## Qué puedo hacer por tu negocio

- **Tiendas online y e-commerce:** desde cero o sobre Tiendanube, con personalizaciones que la plataforma no trae (selectores de packs, SKUs dinámicos, lógica a medida).
- **Sistemas de gestión:** punto de venta (POS), control de stock y paneles con estadísticas para decidir con datos.
- **Pedidos online para gastronomía:** menú mobile-first, pedidos por WhatsApp y apps de delivery.
- **Webs y landing pages:** rápidas, responsive y pensadas para que te contacten.
- **Mejoras sobre lo que ya tenés:** arreglos, integraciones y nuevas funciones en tu sitio o sistema actual.

<img src="./assets/divisor.svg" width="100%" alt="">

## Más proyectos

| Proyecto | Qué es |
|---|---|
| [**ReactVicios**](https://github.com/Frannkode/ReactVicios) | Menú mobile-first con pedidos por WhatsApp |
| [**ElCruceRestaurant**](https://github.com/Frannkode/ElCruceRestaurant) | Sitio de restaurante con React y Tailwind v4 |
| [**QuickOrder**](https://github.com/Frannkode/QuickOrder) | Sistema de pedidos en TypeScript |
| [**FullBebidas**](https://github.com/Frannkode/FullBebidas) | E-commerce de bebidas |
| [**Indumentaria**](https://github.com/Frannkode/Indumentaria) | E-commerce de ropa |
| [**MotoPartes**](https://github.com/Frannkode/MotoPartes) | E-commerce de repuestos de moto |

Más trabajos en mi [portfolio](https://frannkode.vercel.app).

<img src="./assets/divisor.svg" width="100%" alt="">

## Tecnologías

<p>
  <img src="https://img.shields.io/badge/HTML5-16203A?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-16203A?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-16203A?style=flat-square&logo=javascript&logoColor=white" alt="JavaScript">
  <img src="https://img.shields.io/badge/TypeScript-16203A?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-16203A?style=flat-square&logo=react&logoColor=white" alt="React">
  <img src="https://img.shields.io/badge/Vite-16203A?style=flat-square&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-16203A?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Python-16203A?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-16203A?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-16203A?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Firebase-16203A?style=flat-square&logo=firebase&logoColor=white" alt="Firebase">
  <img src="https://img.shields.io/badge/Supabase-16203A?style=flat-square&logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/Docker-16203A?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Git-16203A?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Vercel-16203A?style=flat-square&logo=vercel&logoColor=white" alt="Vercel">
</p>

<img src="./assets/divisor.svg" width="100%" alt="">

## Cómo trabajo

1. **Charlamos y definimos qué necesitás.** Sin tecnicismos, con un alcance claro.
2. **Entregas por etapas.** Ves avances reales y decidimos juntos en cada paso.
3. **Lanzamiento y soporte.** Te acompaño después de publicar.

<p align="center">
  <b>¿Tenés un proyecto en mente?</b><br>
  Contame qué necesitás y te respondo con una propuesta.<br><br>
  <a href="https://wa.me/5493482232529?text=Hola%20Franco%2C%20vi%20tu%20GitHub%20y%20quiero%20consultarte%20por%20un%20proyecto">
    <img src="https://img.shields.io/badge/Hablemos%20por%20WhatsApp-3342C9?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Hablemos por WhatsApp">
  </a>
</p>
