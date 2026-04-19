# 🦁 Brave Optimal Config

<p align="center">
  <img src="brave_config_banner.png" alt="Brave Optimal Config Banner" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Brave-Optimal-orange?style=for-the-badge&logo=brave" alt="Brave Badge">
  <img src="https://img.shields.io/badge/Privacy-Enhanced-brightgreen?style=for-the-badge" alt="Privacy Badge">
  <img src="https://img.shields.io/badge/Performance-Boost-blue?style=for-the-badge" alt="Performance Badge">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License Badge">
</p>

---

**Brave Optimal Config** es la unión definitiva de configuraciones optimizadas para **Brave Browser**. Este proyecto combina las mejores listas de filtros y las flags experimentales más eficientes para transformar tu navegación en una experiencia más rápida, privada y limpia.

> [!TIP]
> Esta configuración busca el equilibrio perfecto entre **privacidad extrema** y **funcionalidad total**, eliminando lo molesto sin romper los sitios web que visitas.

---

## 🛡️ 1. Filtros de Escudos (Shields)
Maximiza el bloqueo de rastreadores, anuncios y contenido innecesario configurando tus filtros regionales y globales.

### 📋 Listas Recomendadas
Para una experiencia óptima, activa las siguientes listas en tu navegador:

#### **Privacidad y Rastreo**
*   ✅ **Cookie notice blocker** - *EasyList Cookie*
*   ✅ **Tracking URL blocker** - *AdGuard URL Tracking Protection Filters*

#### **Bloqueo de Molestias (Annoyances)**
*   ✅ **Annoying distractions blocker** - *Fanboy's Annoyances + uBO Annoyances*
*   ✅ **Mobile app promo blocker** - *Fanboy's Mobile Notifications*
*   ✅ **Social media blocker** - *Fanboy's Social*

#### **YouTube Optimizado**
*   ✅ **YouTube Shorts blocker** - *YouTube Anti-Shorts*
*   ✅ **YouTube end video elements blocker** - *Remove Youtube End video elements*

#### **Seguridad y Regional**
*   ✅ **Porn blocker** - *BlockLists Anti-Porn*
*   ✅ **AdGuard Spanish/Portuguese** - *Filtros específicos para navegación en español*

### 🚀 Cómo Instalar Filtros
1.  Copia y pega este enlace en tu barra de direcciones:
    ```bash
    brave://settings/shields/filters
    ```
2.  Busca y activa los filtros mencionados arriba.
3.  Haz clic en **"Listas actualizadas"** para asegurar la protección más reciente.

---

## ⚡ 2. Flags Experimentales
Optimiza el rendimiento del motor Chromium y mejora la aceleración por hardware para una navegación mucho más fluida.

### ⚙️ Flags de Rendimiento y GPU
| Flag ID | Acción | Beneficio |
| :--- | :--- | :--- |
| `#ignore-gpu-blocklist` | Enable | Fuerza la aceleración GPU en hardware no soportado |
| `#enable-quic` | Enable | Protocolo de red más rápido y eficiente |
| `#enable-gpu-rasterization` | Enable | Mejora el renderizado de imágenes y SVG |
| `#enable-zero-copy` | Enable | Reduce el uso de memoria en el renderizado |
| `#enable-parallel-downloading` | Enable | Acelera las descargas dividiéndolas en partes |
| `#ui-disable-partial-swap` | Enable | Optimización visual en la interfaz |

### 🛠️ Configuración de Video y JS
*   **Decodificación/Codificación de Hardware**: Asegúrate de tener `#disable-accelerated-video-decode` y `#disable-accelerated-video-encode` en **Disabled** (o según su nombre actual para habilitarlas) para máxima fluidez en streaming.
*   **JS Estabilidad**: `#disable-javascript-harmony-shipping` para evitar conflictos con scripts legacy.

> [!CAUTION]
> Las Flags son experimentales. Si experimentas parpadeos visuales o errores extraños, restablece los valores por defecto.

### 🚀 Cómo Configurar Flags
1.  Copia y pega este enlace:
    ```bash
    brave://flags
    ```
2.  Usa el buscador para encontrar cada ID.
3.  Cambia el estado a **Enabled** (o según se indique).
4.  Reinicia Brave haciendo clic en el botón **Relaunch**.

---

## ✨ Beneficios Principales
*   🚀 **Velocidad Extrema**: Carga de páginas hasta un 30% más rápida gracias a QUIC y descargas paralelas.
*   🧹 **Limpieza Visual**: Adiós a los avisos de cookies, Shorts de YouTube y distracciones sociales.
*   🔒 **Privacidad Total**: Bloqueo agresivo de parámetros de rastreo en URLs y cookies de terceros.
*   🎬 **Streaming Fluido**: Aprovechamiento total del hardware para video en 4K.

---

## 📝 Licencia
Distribuido bajo la Licencia **MIT**. Consulta el archivo `LICENSE` para más detalles.

---
<p align="center">
Hecho con ❤️ para la comunidad de Brave.
</p>
