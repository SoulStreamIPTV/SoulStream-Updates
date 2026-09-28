{
  "version": 1,
  // Versión interna del archivo de configuración.
  // Cada cambio importante puede aumentar este número.


  "maintenance": false,
  // Controla si la aplicación entra en modo mantenimiento.
  // false = aplicación funcionando normalmente.
  // true = muestra pantalla de mantenimiento y bloquea acceso.


  "maintenanceMessage": "",
  // Mensaje personalizado mostrado al usuario cuando maintenance=true.
  // Ejemplo:
  // "Estamos realizando mejoras. Volveremos pronto."


  "features": {

    "sportsZone": true,
    // Activa o desactiva la Zona Deportiva.
    // true = muestra eventos deportivos.
    // false = oculta la sección deportiva.


    "homeBanners": true,
    // Controla los banners remotos del Home.
    // false = no carga contenido promocional desde GitHub.


    "catalogSync": true,
    // Controla la sincronización del catálogo IPTV.
    // Puede utilizarse para detener temporalmente cargas remotas.


    "search": true
    // Activa o desactiva la función de búsqueda.
  },


  "messages": {

    "announcement": "",
    // Mensaje global que puede mostrarse dentro de la aplicación.
    // Ejemplo:
    // "Nuevo contenido disponible."


    "showAnnouncement": false
    // Controla si el mensaje anterior debe mostrarse.
  },


  "minimumSupportedVersion": 1,
  // Versión mínima de la aplicación permitida.
  // Permite obligar a actualizar versiones antiguas.


  "appBehavior": {

    "forceUpdateCheck": true,
    // Define si la app debe consultar update.json al iniciar.


    "allowOfflineCache": true
    // Permite utilizar datos guardados localmente cuando no hay internet.
  }
}
