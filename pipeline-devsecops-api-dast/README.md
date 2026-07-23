# 🛡️ Pipeline Automatizado de DevSecOps & Seguridad de APIs

Un framework de **Pruebas de Seguridad de Aplicaciones Dinámicas (DAST)** de nivel empresarial, integrado con **GitHub Actions** y potenciado por **OWASP ZAP**. Este pipeline está diseñado para aplicar el concepto de *Shift-Left Security*, escaneando automáticamente las APIs REST contra vulnerabilidades críticas y alineándose con el **OWASP API Security Top 10** y los estándares globales de cumplimiento web.

---

## 🎨 Arquitectura del Framework & Vista Previa del Portafolio

A continuación se presenta la descripción técnica de la configuración del framework, las métricas de integración en la nube y los reportes de auditoría de cumplimiento:

### 🟡 Portada del Servicio
![Portada del Servicio](assets/capa-amarela.png)

### 🟣 Reporte Técnico Completado (3 Bloques)
![Framework de Seguridad de APIs](assets/portfolio-ingles.png)

---

## 🚀 Características Clave

- **Escaneo DAST Automatizado:** Análisis dinámico de seguridad activado automáticamente con cada `push` y `pull_request` utilizando el motor optimizado OWASP ZAP Baseline.
- **Auditoría de Cumplimiento Multi-Herramienta:** Verificación integrada de doble capa que rastrea fallas en el código de la aplicación y la configuración de encabezados de seguridad HTTP en el servidor.
- **Generación de Artefactos en la Nube:** Compilación automática de métricas de riesgo técnico (alertas de severidad Alta, Media y Baja) con descarga directa de reportes interactivos en HTML/PDF.
- **Flujo de Trabajo DevSecOps Empresarial:** Ejecución 100% automatizada gestionada a través de entornos virtuales (runners) de GitHub en menos de 7 minutos.

---

## 📂 Estructura del Repositorio

```text
├── .github/
│   └── workflows/
│       └── security.yml       # Configuración del pipeline DevSecOps en GitHub Actions
├── assets/
│   ├── capa-amarela.png       # Imagen de portada del servicio
│   └── portfolio-ingles.png   # Imagen del reporte técnico de 3 bloques
└── README.md                  # Documentación completa del framework en español
```

---

## 🛠️ Stack Tecnológico & Dependencias

- **Motor de Automatización:** OWASP ZAP (Zed Attack Proxy)
- **Plataforma de CI/CD:** GitHub Actions (Runner de Ubuntu-latest)
- **Entorno Objetivo de Pruebas:** OWASP crAPI (Completely Ridiculous API)
- **Estándar de Cumplimiento:** Auditoría de Encabezados de Seguridad HTTP (Security Headers)

---

## 🔧 Configuración del Workflow (`security.yml`)

El pipeline de automatización está configurado explícitamente para otorgar permisos de escritura de artefactos de seguridad, garantizando el almacenamiento estable de los reportes:

```yaml
# Disparadores principales para el escáner de seguridad
on:
  push:
    branches: [ main, develop ]
  pull_request:
    branches: [ main, develop ]
```

---

## 📊 Entregables & Resultados Técnicos

1. **Integración Continua de Seguridad:** Tasa de éxito del 100% en los pipelines de automatización del servidor, garantizando escaneos sin bloqueos en los despliegues.
2. **Robustecimiento del Servidor:** Protocolos de validación que logran la **Calificación Máxima "A" de Cumplimiento Internacional** en cifrado de transporte web y protección contra secuestro de clics (clickjacking).
3. **Reportes de Mitigación Accionables:** Accesibilidad inmediata a logs interactivos en formato `.html`, localizando configuraciones incorrectas y proporcionando guías técnicas de remediación para los equipos de desarrollo.

---
_Desarrollado con enfoque en la ingeniería de calidad premium y la excelencia técnica._
