# 💼 Portafolio Profesional de Proyectos de Software y Datos
**Desarrollador:** Gabriel  
**Especialidad:** Ingeniería en Sistemas de Información | Full-Stack, Arquitectura de Microservicios & Data/AI Engineering  
**GitHub:** [github.com/Gabriel200545](https://github.com/Gabriel200545)  
**Contacto:** [Dark05studios@gmail.com](mailto:Dark05studios@gmail.com)  

---

## 🌟 Visualización del Portafolio Web Interactivo & Demos en Vivo
Abre el archivo [`index.html`](./index.html) directamente en cualquier navegador web moderno (Edge, Chrome, Firefox, Safari) para interactuar con:

### 🎮 Demos Funcionales Integrados:
1. **Distribuidora Walter (ERP & Microservicios):**
   - **Terminal Punto de Venta (POS) & Facturación:** Selección interactiva de productos, cálculo dinámico de subtotal e IVA, y generación de facturas electrónicas con animación de confetti y comprobante fiscal imprimible.
   - **Monitor de Lotes & Trazabilidad de Vencimientos:** Tabla interactiva basada en la app de Flutter con búsqueda en tiempo real y semáforos de caducidad.
   - **API & Swagger Playground:** Consola interactiva para probar peticiones HTTP (`GET /api/Productos`, `POST /api/Venta/Crear`, `GET /api/Auditoria`, `POST /api/Reports/embed-token`) con JWT Bearer y respuestas JSON simuladas con latencia real.

2. **AgroVerde Analytics (Data Mining & IA):**
   - **Predictor de Riesgo Agrícola (Inferencia XGBoost en Vivo):** Controles interactivos para modificar precipitación, temperatura, déficit hídrico del suelo y plagas, calculando la probabilidad de bajo rendimiento en tiempo real mediante un Gauge animado, explicabilidad estilo SHAP y recomendación agronómica con ahorro proyectado en USD.
   - **Auditor de Calidad (6 Dimensiones) & Anti-Leakage en C# .NET:** Simulador de consola del motor `AgroVerde.Quality` y `AgroVerde.Governance` que detecta y bloquea intentos de fuga de información (*Target Leakage*) y envía registros incompletos a Cuarentena.

---

## 🏗️ Resumen de Ecosistemas de Proyectos

### 1. 🏢 Ecosistema ERP & Microservicios — Distribuidora Walter
Ubicación: `../01_Distribuidora_Walter_ERP`

| Módulo | Directorio | Tecnologías | Descripción Principal |
| :--- | :--- | :--- | :--- |
| **App Móvil / Escritorio** | `distribuidora-mobile-app` | Flutter 3.x, Dart, PDF/Printing | Sistema POS con gestión de bodegas, categorías, marcas, lotes con vencimiento, compras, ventas y generación de facturas en PDF. |
| **Backend API Central** | `distribuidora-backend-api` | ASP.NET Core 8, C#, EF Core, Azure SQL | API REST con autenticación JWT, repositorio desacoplado, políticas de roles (Gerente, Vendedor) y tabla de Auditoría. |
| **Microservicios (2026)** | `distribuidora-microservices` | ASP.NET Core, Swagger, OpenAPI | Microservicios de alto rendimiento con middlewares de telemetría y generadores de datos de prueba sintéticos. |
| **Panel Web & PowerBI** | `distribuidora-web-admin` | JavaScript ES6, PowerBI Client SDK, HTML5 | Tableros ejecutivos integrando PowerBI Embedded para métricas de inventario y rotación comercial. |

### 2. 🌱 Plataforma de Minería de Datos & IA — AgroVerde R.L.
Ubicación: `../02_AgroVerde_Data_Mining`

| Componente | Directorio | Tecnologías | Métricas / Logros |
| :--- | :--- | :--- | :--- |
| **Modelos de ML** | `src/models/` | Python, XGBoost, LightGBM, Scikit-Learn | **ROC-AUC: 0.9481**, Recall: 86.53%, F1-Score: 73.0 pts. Previene pérdidas por \$164,050 USD anuales. |
| **Blindaje Anti-Leakage** | `src/features/` & `dotnet/` | Python & C# | Prohibición estricta de `rendimiento_ton_ha` y variables directas para evitar contaminación del predictor. |
| **Motor de Calidad & Gobernanza** | `dotnet/` | C# .NET Core, SQL Server, SqlBulkCopy | 6 dimensiones de calidad evaluadas, 5 políticas DAMA, 97.63% de registros conformes y aislamiento en cuarentena. |
| **Cuadernos de Investigación** | `notebooks/` | Jupyter Notebooks (10 notebooks) | Validación de hipótesis, ciclo PHVA (Planear, Hacer, Verificar, Actuar) y estabilidad temporal por ciclo. |
