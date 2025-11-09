# ⏰ Reloj Fullscreen para Movistar Home (Revivido)

Este es un proyecto personal para crear un reloj digital minimalista, personalizable y de pantalla completa.

Originalmente, este proyecto nació con la idea de tener un reloj siempre visible y estético en mi dispositivo **Movistar Home (Aura)**. Como muchos sabrán, Movistar descontinuó el soporte para este dispositivo, dejándolo esencialmente como un pisapapeles digital.

Este repositorio contiene el código HTML, CSS y JavaScript de ese reloj (el cual ahora utilizo para darle una segunda vida al dispositivo) en un único `index.html` para así poder descargarlo y meterlo directamente en el dispositivo.

## El Hack: Reviviendo el Movistar Home

El corazón de este proyecto no es solo el reloj, sino la capacidad de volver a usar el hardware abandonado. Esto fue posible gracias al increíble trabajo documentado en el repositorio:

➡️ **[https://github.com/zry98/movistar-home-hacks](https://github.com/zry98/movistar-home-hacks)**

Siguiendo las instrucciones de ese repositorio, pude "liberar" el dispositivo y obtener la capacidad de cargar páginas web personalizadas (como este reloj) en lugar del software obsoleto de Movistar.

## 🚀 Características del Reloj

Este no es un simple reloj. Gracias a la asistencia de **Gemini de Google** durante el desarrollo, he podido integrar un panel de configuración completo:

* **Reloj Digital Limpio:** Muestra la fecha, la hora (HH:MM) y los segundos.
* **Fondo Atenuado:** Cualquier imagen de fondo se oscurece automáticamente para garantizar que la hora siempre sea legible con su opacidad original.
* **Panel de Configuración (Oculto):**
    * **Formato de Hora:** Cambiar entre formato 12/24 horas.
    * **Segundos:** Ocultar o mostrar los segundos.
    * **Color del Texto:** Selector de color para personalizar la fuente.
    * **Tipografía:** Múltiples fuentes modernas para elegir (Inter, Oswald, Bebas Neue, etc.).
* **Gestión de Fondos:**
    * **Fondo Manual:** Establece un fondo estático subiendo un archivo o pegando una URL.
    * **Fondos Alternos:** Activa un carrusel de hasta 10 imágenes (mezclando URLs y archivos subidos) que rotan cada 10 minutos.
* **Enlaces Rápidos:** Acceso directo para abrir Spotify o Radio FM (pensado para la tablet).
* **Modo Pantalla Completa:** Botón para ocultar la interfaz del navegador.
* **Persistencia:** Toda tu configuración (color, fuente, fondos, etc.) se guarda en el `localStorage` del navegador para que esté lista la próxima vez que cargues la página.

He recopilado también una serie de imágenes que pueden servir para poner de fondo en el reloj ➡️ **[Google Drive](https://drive.google.com/drive/folders/1LaHrwe_a2oZrQL4t407ekUbcMjhS_daU?usp=sharing)**

## ✨ Agradecimientos

* A **zry98** y a todos los contribuidores del repositorio [movistar-home-hacks](https://github.com/zry98/movistar-home-hacks) por hacer posible que recuperemos nuestros dispositivos.
* A **Gemini de Google**, por su inestimable ayuda en la generación, depuración y refactorización del código de este proyecto.
