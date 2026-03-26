# 📊 Monitor de Contexto Chihuahua

Una plataforma independiente de **análisis de contexto** orientada al estudio integral del entorno en el estado de Chihuahua. Transformamos información pública en análisis estructurados para comprender la dinámica completa del estado.

[![Hugo](https://img.shields.io/badge/Built%20with-Hugo-FF4088?style=flat-square&logo=hugo)](https://gohugo.io)
[![Stack Theme](https://img.shields.io/badge/Theme-Stack-blue?style=flat-square)](https://github.com/CaiJimmy/hugo-theme-stack)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)]()

---

## 📋 Tabla de Contenidos

- [Descripción](#-descripción)
- [Características](#-características)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Requisitos](#-requisitos)
- [Instalación](#-instalación)
- [Uso](#-uso)
- [Categorías](#-categorías)
- [Contribuir](#-contribuir)
- [Licencia](#-licencia)

---

## 🎯 Descripción

**Monitor de Contexto Chihuahua** es una iniciativa de análisis que:

- 🔍 **Integra múltiples dimensiones**: seguridad, economía, política y factores sociales
- 📰 **Recopila información pública**: noticias y reportes abiertos de fuentes verificadas
- 🤖 **Utiliza procesamiento automatizado**: herramientas tecnológicas y modelos de lenguaje
- 📊 **Genera análisis consolidados**: síntesis de múltiples fuentes en un solo documento
- 🎯 **Proporciona visión estratégica**: útil para tomadores de decisiones, analistas e investigadores
- 🔓 **Transparencia total**: basado únicamente en fuentes abiertas y públicas

---

## ✨ Características

| Característica | Descripción |
|---|---|
| 📁 **Análisis por Categorías** | 10 categorías temáticas para organizar el contexto |
| 🏷️ **Etiquetado Flexible** | Sistema de tags para clasificación cruzada |
| 🔎 **Búsqueda Integrada** | Motor de búsqueda de artículos y análisis |
| 📅 **Archivo Temporal** | Vista de análisis organizados por fecha |
| 📱 **Diseño Responsivo** | Acceso desde cualquier dispositivo |
| ⚡ **Generación Estática** | Sitio rápido y seguro con Hugo |

---

## 📦 Estructura del Proyecto

```
monitor-contexto-cuu/
├── content/
│   ├── analisis/              # Artículos de análisis
│   ├── categories/            # Páginas de categorías
│   ├── page/                  # Páginas estáticas
│   │   ├── about/             # Acerca de
│   │   ├── archives/          # Archivo temporal
│   │   ├── search/            # Búsqueda
│   │   └── links/             # Enlaces externos
│   └── _index.md              # Página de inicio
├── static/
│   └── images/                # Imágenes (avatar, etc.)
├── layouts/
│   └── _partials/             # Plantillas personalizadas
├── themes/
│   └── stack/                 # Tema Stack
├── hugo.toml                  # Configuración principal
└── README.md                  # Este archivo
```

---

## 🔧 Requisitos

- **Hugo** v0.159.0 o superior (Extended)
- **Git** para control de versiones
- Un navegador moderno para visualización

### Software Recomendado

- VS Code o editor de texto similar
- Git Bash o terminal PowerShell

---

## 🚀 Instalación

### 1. Clonar el Repositorio

```bash
git clone https://github.com/contextocuu/monitor-contexto-cuu.git
cd monitor-contexto-cuu
```

### 2. Verificar Hugo Instalado

```bash
hugo version
```

Si no está instalado, descárgalo desde: https://gohugo.io/installation/

### 3. Descargar Dependencias del Tema

```bash
git submodule update --init --recursive
```

---

## 📝 Uso

### Ver el Sitio Localmente

```bash
hugo server -D
```

Accede a: `http://localhost:1313`

El servidor automáticamente recargará los cambios.

### Crear un Nuevo Artículo

```bash
hugo new analisis/nombre-del-articulo.md
```

Luego edita el archivo en `content/analisis/` con:

```yaml
---
date: 2026-03-26T12:00:00-06:00
draft: false  # Cambiar a false para publicar
title: "Título del análisis"
description: "Resumen breve"
categories:
  - Categoría
tags:
  - tag1
  - tag2
---

Contenido del análisis aquí...
```

### Compilar para Producción

```bash
hugo -D
```

Los archivos se generarán en la carpeta `public/`.

---

## 📚 Categorías

El proyecto incluye 10 categorías temáticas:

| Icono | Categoría | Descripción |
|---|---|---|
| 💰 | **Economía** | Indicadores económicos y tendencias |
| 💼 | **Empleo y Empresas** | Mercado laboral y sector empresarial |
| 🚗 | **Movilidad y Transporte** | Infraestructura y sistemas de transporte |
| 🏥 | **Salud** | Situación sanitaria y servicios médicos |
| 📚 | **Educación** | Sistemas educativos y capacitación |
| ✈️ | **Migración** | Movimientos poblacionales y flujos migratorios |
| ⚖️ | **Derechos Humanos** | Derechos fundamentales y protecciones |
| 🌱 | **Medio Ambiente** | Sostenibilidad y recursos naturales |
| 🏗️ | **Infraestructura y Obra Pública** | Proyectos y desarrollo urbano |
| 👥 | **Sociedad y Comunidad** | Tejido social y organizaciones comunitarias |

---

## 🤝 Contribuir

### Reportar Problemas

Si encuentras errores o tienes sugerencias, por favor abre un **Issue** en el repositorio.

### Enviar Mejoras

1. Fork el proyecto
2. Crea una rama: `git checkout -b feature/mejora`
3. Realiza tus cambios
4. Haz commit: `git commit -m 'Agregada mejora'`
5. Push a la rama: `git push origin feature/mejora`
6. Abre un Pull Request

---

## 📄 Licencia

Este proyecto está bajo licencia **MIT**. Ver archivo [LICENSE](LICENSE) para más detalles.

---

## 📞 Contacto

- **GitHub**: [@contextocuu](https://github.com/contextocuu)
- **X (Twitter)**: [@contextocuu](https://twitter.com/contextocuu)
- **Sitio Web**: https://contextocuu.github.io

---

## 📊 Stack Tecnológico

- **Hugo** - Generador de sitios estáticos
- **Stack Theme** - Tema profesional para blogs
- **GitHub Pages** - Hosting
- **GitHub Actions** - CI/CD para despliegue automático

---

**Última actualización**: 26 de Marzo de 2026

*Monitor de Contexto Chihuahua es un proyecto en desarrollo continuo, consolidándose como una plataforma de referencia en el análisis de contexto a partir de fuentes abiertas.*
