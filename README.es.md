🌍 [English](README.md) | [Türkçe](README.tr.md) | [Español](README.es.md)

# 🔓 OpenCode — Guía General de Usuario

> **El agente de codificación de IA de código abierto nativo de terminal que ejecuta tareas en su shell.**

<div align="center">

![Versión](https://img.shields.io/badge/version-latest-blue)
![Licencia](https://img.shields.io/badge/license-MIT-green)

</div>

---

## 📚 Tabla de Contenidos

- [¿Qué es OpenCode?](#qué-es-opencode)
- [Instalación](#instalación)
- [Inicio Rápido](#inicio-rápido)
- [Modo Interactivo (TUI)](#modo-interactivo-tui)
- [Configuración](#configuración)
- [Comandos de Barra Diagonal](#comandos-de-barra-diagonal)
- [Atajos de Teclado Esenciales](#atajos-de-teclado-esenciales)
- [Consejos y Trucos](#consejos-y-trucos)
- [Recursos](#recursos)
- [Tarjeta de Referencia Rápida](#tarjeta-de-referencia-rápida)

---

## ¿Qué es OpenCode?

**OpenCode** es un agente de IA de código abierto nativo de terminal diseñado para automatizar las modificaciones de código, interactuar con LLM y gestionar tareas de desarrollador.

---

## Instalación

### 🪟 Windows (WinGet)
```powershell
winget install SST.opencode
```

### 🍎 macOS / 🐧 Linux (Homebrew)
```bash
brew install anomalyco/tap/opencode
```

### 🪟 Windows (Scoop)
```powershell
scoop install opencode
```

---

## Tarjeta de Referencia Rápida

```
┌──────────────────────────────────────────────────────────┐
│               🔓 Referencia Rápida de OpenCode           │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  INICIAR                   GESTIONAR                     │
│  opencode        .......  Iniciar TUI     /new           │
│  opencode run    .......  Una respuesta   /clear         │
│  opencode agent  .......  Gestionar agts  /compact       │
│                                           /quit          │
│                                                          │
│  EDITOR                    ATAJOS                        │
│  @archivo        .......  Ref. archivo    Ctrl+C         │
│  !comando        .......  Ejecutar shell  Ctrl+D         │
│  Shift+Enter     .......  Nueva línea     Ctrl+O         │
│                                           Ctrl+L         │
│                                                          │
│  CONFIGURACIÓN                                           │
│  /config         .......  Panel de Ajustes               │
│  /model          .......  Cambiar modelo                 │
│                                                          │
└──────────────────────────────────────────────────────────┘
```
