# ⏰ Reloj Fullscreen para Movistar Home (Revivido)

Este es un proyecto personal para crear un reloj digital minimalista, personalizable y de pantalla completa.

Originalmente, este proyecto nació con la idea de tener un reloj siempre visible y estético en mi dispositivo **Movistar Home (Aura)**. Como muchos sabrán, Movistar descontinuó el soporte para este dispositivo, dejándolo esencialmente como un pisapapeles digital.

Este repositorio contiene el código HTML, CSS y JavaScript de ese reloj (el cual ahora utilizo para darle una segunda vida al dispositivo) en un único `index.html` para así poder descargarlo y meterlo directamente en el dispositivo o también tener la opción de abrirlo con su URL (<a href="https://jmlopez-pruebas.github.io/reloj" target="_blank">https://jmlopez-pruebas.github.io/reloj/</a>) desde un navegador web en el Movistar Aura.

*Idea original de @josemaalopez para su uso en Movistar Home, u otros dispositivos con pantalla grande.*

## El Hack: Reviviendo el Movistar Home

El corazón de este proyecto no es solo el reloj, sino la capacidad de volver a usar el hardware abandonado. Esto fue posible gracias al increíble trabajo documentado en el repositorio:

➡️ <a href="https://github.com/zry98/movistar-home-hacks" target="_blank">github.com/zry98/movistar-home-hacks</a>

Siguiendo las instrucciones de ese repositorio, pude "liberar" el dispositivo y obtener la capacidad de cargar páginas web personalizadas (como este reloj) en lugar del software obsoleto de Movistar.

## 🚀 Características del Reloj (V2)

Este no es un simple reloj. He integrado un panel de configuración completo con una estética "Liquid Glass" moderna, fluida y altamente cuidada:

* **Reloj Digital Limpio:** Muestra la fecha, la hora (12/24H) y los segundos con centrado matemático perfecto sin importar a qué tamaño lo escales.
* **Fondo Atenuado y Dinámico:** 
    * **Carrusel Predeterminado:** Una selección de paisajes urbanos de alta calidad.
    * **Fondo Manual:** Establece un fondo estático subiendo un archivo o pegando una URL.
    * **Carrusel Personalizado:** Añade hasta 10 imágenes (mezclando URLs y archivos locales) que rotan automáticamente cada 10 minutos con transiciones suaves. Cualquier imagen se oscurece automáticamente para garantizar que la interfaz siempre sea legible.
* **Clima Inteligente:** Buscador integrado con autocompletado en tiempo real que muestra la temperatura y un icono minimalista según la condición meteorológica de tu ciudad.
* **Temporizador Pomodoro Avanzado:** 
    * Gestión independiente de tiempos de "Trabajo" y "Descanso".
    * Modo "Mini Widget" flotante inteligente si lo minimizas mientras sigue corriendo.
    * Alertas sonoras personalizables (usa la integrada o pega tu propia URL mp3 desde plataformas como tstore.ouim.me).
    * Edición de tiempo intuitiva mediante botones (+ / -) o clicando para escribir directamente el número.
* **Panel de Configuración Completo:**
    * Modifica el tamaño individual del Reloj, Clima, Botones y del Mini Pomodoro.
    * Personaliza la tipografía (Inter, Oswald, Bebas Neue, Montserrat, etc.) y el color del texto.
* **Enlaces Rápidos:** Accesos directos centrales para abrir Spotify o Radio FM (ideal para tablets).
* **Persistencia Total:** Toda tu configuración se guarda de forma local en el navegador (`localStorage`) para que todo esté tal y como lo dejaste al volver a abrir la página.

He recopilado también una serie de imágenes que pueden servir para poner de fondo en el reloj ➡️ <a href="https://drive.google.com/drive/folders/1LaHrwe_a2oZrQL4t407ekUbcMjhS_daU?usp=sharing" target="_blank">Google Drive</a>

## ✨ Agradecimientos

* A **zry98** y a todos los contribuidores del repositorio <a href="https://github.com/zry98/movistar-home-hacks" target="_blank">movistar-home-hacks</a> por hacer posible que recuperemos nuestros dispositivos.
* A **Gemini de Google**, por su inestimable ayuda en la generación, depuración y refactorización del código de este proyecto.
