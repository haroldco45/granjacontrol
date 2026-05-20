# 🐔 GranjaControl — 50 Gallinas Ponedoras
### PWA de gestión avícola · Vibras Positivas HM

---

## 📱 Descripción

Sistema de gestión integral para proyecto de 50 gallinas ponedoras. PWA (Progressive Web App) que funciona **offline** y puede instalarse en el celular como una app nativa.

---

## ✅ Módulos incluidos

| Módulo | Funciones |
|--------|-----------|
| 📊 Dashboard | KPIs en tiempo real, gráficas, alertas automáticas, tareas pendientes |
| 🥚 Producción | Registro diario de huevos, % postura, inventario, historial |
| 🌾 Alimentación | Control de stock (kg), entradas/consumos, alertas de agotamiento |
| 💉 Sanidad | Vacunaciones, tratamientos, calendario sanitario, mortalidad |
| 🐣 Lotes | Registro de lotes, razas, edades, estado, mortalidad detallada |
| 💰 Finanzas | Ingresos, gastos, utilidad neta, análisis de rentabilidad |
| 📋 Informes | Generación de informes, exportación CSV y backup JSON |

---

## 🕐 Fecha y hora

- Usa hora real de Colombia (UTC-5 / America/Bogota) en todas las pantallas y registros.

---

## ⚙️ Requisitos técnicos

- HTML5 / CSS3 / JavaScript vanilla
- Sin frameworks externos
- localStorage para persistencia de datos
- PWA: manifest.json + Service Worker (sw.js)
- Funciona 100% offline una vez cacheado

---

## 📦 Archivos

```
index.html      → App principal (todo en un solo archivo)
manifest.json   → Configuración PWA
sw.js           → Service Worker (offline + cache)
icons/          → Íconos 192x192 y 512x512 (debes crear/colocar)
README.md       → Este archivo
```

---

## 🚀 Despliegue

### GitHub Pages
```bash
git init
git add .
git commit -m "GranjaControl PWA v1.0"
git remote add origin https://github.com/haroldco45/granjacontrol.git
git push -u origin main
# Activar GitHub Pages en Settings > Pages > main branch
```

### Netlify
Arrastra la carpeta al panel de Netlify. URL automática.

---

## 🎨 Colores y branding

- Verde principal: `#2d5a1b`
- Amarillo acento: `#f5c800`
- Tipografías: Nunito + Oswald (Google Fonts)

---

## 📝 Notas legales

> Desarrollada por **Vibras Positivas HM** — Derechos de Autor Reservados © 2026  
> Desarrollador: Harold Marín · haroldco45@gmail.com · WhatsApp 311 770 0431
