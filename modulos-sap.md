# 📦 Matriz Completa de Módulos SAP Trabajados

> **Nota de Arquitectura Funcional:** A lo largo de mi carrera como Consultor ABAP Senior y Líder Técnico, he desarrollado componentes sobre una amplia variedad de módulos de SAP[cite: 2, 3]. A continuación, se detalla la matriz de cobertura técnica clasificada por el tipo de objeto desarrollado (Reportes, Interfaces, Conversiones, Ampliaciones, Formularios, Workflow, OData y Fiori).

---

## 🏛️ 1. Área de Finanzas y Control de Gestión (FI / CO / TR)

| Módulo / Submódulo | Descripción Breve | Tipos de Objetos Técnicos Desarrollados |
| :--- | :--- | :--- |
| **FI** (General) | Gestión Financiera[cite: 5] | `Formularios` `Reportes` `Interfaces` `Conversiones` `Ampliaciones` `Workflow` `Web Dynpro` `OData`[cite: 5] |
| **FI-AP**[cite: 5] | Contabilidad de Acreedores[cite: 5] | `Reportes` `Interfaces` `Ampliaciones` `Web Dynpro`[cite: 5] |
| **FI-AR**[cite: 5] | Contabilidad de Deudores[cite: 5] | `Reportes` `Interfaces` `Ampliaciones`[cite: 5] |
| **FI-CA**[cite: 5] | Cuentas Contractuales[cite: 5] | `Reportes` `Interfaces` `Ampliaciones`[cite: 5] |
| **FI-GL**[cite: 5] | Contabilidad Principal[cite: 5] | `Reportes` `Interfaces`[cite: 5] |
| **FI-TAX**[cite: 5] | Impuestos y Localizaciones (AR, BR, UY, PY, CO, MX, CR, CL, ZA)[cite: 2, 4, 5] | `Reportes` `Interfaces` (Especialización en motores de Facturación Electrónica en LATAM)[cite: 4, 5] |
| **FI-TV / PA-TV**[cite: 5] | Gestión de Viajes y Gastos[cite: 5] | `Formularios` `Reportes` `Ampliaciones`[cite: 5] |
| **TR**[cite: 5] | Tesorería y Riesgos[cite: 5] | `Formularios` `Conversiones` `Ampliaciones`[cite: 5] |
| **CO**[cite: 5] | Controlling y Costos[cite: 5] | `Reportes` `Conversiones` (Implementaciones críticas de roll-out y costeo)[cite: 2, 5] |

---

## 📦 2. Área de Logística, Cadena de Suministro y Operaciones (SD / MM / WM / PP / QM / PM)

| Módulo / Submódulo | Descripción Breve | Tipos de Objetos Técnicos Desarrollados |
| :--- | :--- | :--- |
| **SD**[cite: 5] | Ventas y Distribución[cite: 5] | `Formularios` `Reportes` `Interfaces` `Conversiones` `Ampliaciones` `Web Dynpro` `Fiori` `OData`[cite: 5] |
| **SD-BIL**[cite: 5] | Facturación Comercial[cite: 5] | `Formularios` `Reportes` `Interfaces` `Ampliaciones`[cite: 5] |
| **MM**[cite: 5] | Gestión de Materiales (Core)[cite: 5] | `Formularios` `Reportes` `Interfaces` `Conversiones` `Ampliaciones` `Workflow` `OData`[cite: 5] |
| **MM-PUR**[cite: 5] | Compras y Abastecimiento[cite: 5] | `Reportes` `Interfaces` `Ampliaciones` `Workflow` `OData`[cite: 5] |
| **MM-SRV**[cite: 5] | Gestión de Servicios[cite: 5] | `Reportes` `Interfaces` `Ampliaciones` `OData`[cite: 5] |
| **MM-IM**[cite: 5] | Gestión de Inventarios y Stock[cite: 5] | `Formularios` `Reportes` `Interfaces`[cite: 5] |
| **WM**[cite: 5] | Gestión de Almacenes[cite: 5] | `Reportes` `Interfaces` `Ampliaciones`[cite: 5] |
| **PP / PP-SFC**[cite: 5] | Planificación de Producción y Órdenes de Fabricación[cite: 5] | `Formularios` `Reportes` `Conversiones` `Ampliaciones` `Workflow`[cite: 5] |
| **QM**[cite: 5] | Gestión de Calidad[cite: 5] | `Reportes` `Conversiones`[cite: 5] |
| **PM / PM-EQM**[cite: 5] | Mantenimiento de Planta y Ubicaciones Técnicas[cite: 5] | `Formularios` `Reportes` `Interfaces` `Conversiones` `Ampliaciones`[cite: 5] |
| **PS**[cite: 5] | Sistema de Proyectos[cite: 5] | `Reportes` `Conversiones`[cite: 5] |
| **LE-TRA** | Ejecución de Logística y Transporte[cite: 2] | `Interfaces` `Ampliaciones` `Formularios`[cite: 2] |

---

## 👥 3. Área de Capital Humano, Salud y Seguridad (HR / HCM / EHS)

| Módulo / Submódulo | Descripción Breve | Tipos de Objetos Técnicos Desarrollados |
| :--- | :--- | :--- |
| **HR / HCM**[cite: 5] | Recursos Humanos (Core)[cite: 5] | `Formularios` `Reportes` `Interfaces` `Ampliaciones` `Fiori` `OData`[cite: 5] |
| **PA**[cite: 5] | Gestión de Personal[cite: 5] | `Formularios` `Reportes` `Interfaces` `Ampliaciones`[cite: 5] |
| **PA-PA (Regionales)**[cite: 5] | Nómina y Personal Localizado (AR, BR, US, VE)[cite: 5] | `Reportes` `Ampliaciones` (Desarrollo adaptado a normativas legales de cada país)[cite: 5] |
| **EHS / EHS-IHS**[cite: 5] | Gestión de Salud, Higiene y Seguridad Laboral[cite: 5] | `Reportes` `Interfaces` `Ampliaciones` `Web Dynpro` `Fiori` `OData`[cite: 5] |

---

## 🚀 4. Soluciones Sectoriales y Módulos de Extensión Avanzada (Industries / Cross)

| Módulo / Submódulo | Descripción Breve | Tipos de Objetos Técnicos Desarrollados |
| :--- | :--- | :--- |
| **IS-OIL**[cite: 5] | Solución de Industria para Petróleo y Gas[cite: 5] | `Interfaces` `Ampliaciones` (Implementaciones críticas para refinerías y flotas de distribución)[cite: 2, 5] |
| **PPM**[cite: 2] | Project and Portfolio Management[cite: 2] | `Reportes` `Ampliaciones` `Interfaces` (Mantenimiento evolutivo de portafolios corporativos)[cite: 2] |
| **MM-RE**[cite: 2] | Flexible Real Estate Management (Gestión Inmobiliaria)[cite: 2] | `Reportes` `Ampliaciones`[cite: 2] |

---
[⬅️ Volver al Perfil Principal](./README.md)
