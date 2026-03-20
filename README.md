# MotoTracker Web App 🏍️

MotoTracker es una aplicación web progresiva (PWA) diseñada para motociclistas que desean llevar un control detallado y fácil de los gastos, mantenimientos y el consumo de combustible de su vehículo. Todo el procesamiento y almacenamiento de datos se realiza de forma local en tu dispositivo, garantizando privacidad y rapidez, y además cuenta con capacidades de uso sin conexión (offline).

## 🌟 Características Principales

- **Dashboard Interactivo:** Visualiza de un vistazo tus KPIs más importantes, como el kilometraje total, rendimiento global (km/L) y el rendimiento del último tanque. Además, incluye un gráfico interactivo con la evolución de tu kilometraje.
- **Registro de Mantenimientos:** Lleva un historial completo de los servicios realizados a tu moto (cambios de aceite, lubricación de cadena, cambio de neumáticos, etc.) junto con sus costos asociados.
- **Control de Combustible:** Registra tus cargas de combustible (parciales o de tanque lleno) para calcular automáticamente el rendimiento y el gasto por día/kilómetro.
- **Simulador de Viajes:** Una calculadora integrada que estima cuánto te costará un viaje basándose en el rendimiento real histórico de tu moto y el precio actual del combustible.
- **Soporte PWA (Progressive Web App):** Instala la aplicación directamente en tu teléfono móvil (Android/iOS) o en tu escritorio para acceder a ella como si fuera una aplicación nativa, pudiendo utilizarla incluso sin conexión a internet.
- **Privacidad y Backups:** Los datos se guardan estrictamente en el `localStorage` del navegador. Puedes exportar un archivo `.json` de seguridad e importarlo en cualquier otro dispositivo.
- **Temas Personalizables:** Incluye soporte para modo claro y oscuro, con temas integrados (Vercel by default y tema Cute).

## 🚀 Cómo usar

1. **Acceso web:** Simplemente abre el archivo `index.html` en tu navegador o visita la URL donde esté alojada la aplicación.
2. **Instalación:** Desde tu navegador móvil o de escritorio (como Chrome o Edge), busca la opción "Instalar aplicación" o "Añadir a la pantalla de inicio".
3. **Primeros Pasos:** 
   - Dirígete a la pestaña de **Mantenimientos** para añadir el registro inicial de tu vehículo o los servicios recientes.
   - Usa la pestaña de **Combustible** cada vez que pases por la gasolinera. 
   - Revisa el **Dashboard** para ver cómo evolucionan tus métricas.
4. **Sincronización:** Si necesitas trasladar tus datos, ve al panel de *Ajustes*, exporta tu `.json` y luego impórtalo en el dispositivo destino.

## 🛠️ Tecnologías Utilizadas

- **HTML5 & Vanilla JavaScript:** Sin frameworks pesados para garantizar la máxima velocidad.
- **Tailwind CSS:** Vía CDN para un estilizado rápido, moderno y completamente responsive.
- **Lucide Icons:** Conjunto de iconos limpios y livianos.
- **Service Workers:** Para la gestión de caché y funcionamiento sin conexión (offline mode).

## 📝 Descripción Breve

**MotoTracker Web App** es una aplicación PWA ligera y offline-first que permite a los motociclistas llevar un registro preciso del rendimiento de combustible, mantenimientos y costos de su vehículo, todo desde un panel interactivo, privado y fácil de usar en cualquier dispositivo.
