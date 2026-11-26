# Alfa y Omega Logistics: app Android de clientes (archivo histórico)

![Estado: archivo histórico](https://img.shields.io/badge/Estado-archivo%20hist%C3%B3rico-lightgrey) ![Java](https://img.shields.io/badge/Java-orange) ![Android SDK 23](https://img.shields.io/badge/Android%20SDK%2023-3DDC84) ![Google Maps](https://img.shields.io/badge/Google%20Maps-4285F4)

> [!NOTE]
> Código original de la app Android con la que los clientes de Alfa y Omega Logistics solicitaban servicios de mensajería urbana en 2018. El producto continúa en **[android-logistics-fleet-dispatch-platform](https://github.com/KevinAndrey96/android-logistics-fleet-dispatch-platform)**, que reúne todos sus componentes con documentación actualizada.

## Qué contiene

- Registro, inicio de sesión y cambio de contraseña (`Login`, `Registro`, `CambiarContrasena`).
- Solicitud de servicios con origen y destino marcados en Google Maps (`MapsActivity`, `SolicituddeServicio`).
- Servicios específicos y especiales con sus características y datos del mensajero asignado.
- Historial de servicios solicitados y realizados.
- Cliente HTTP propio sobre `JSONParser` contra la API REST del backend.

## Stack original

| Componente | Tecnología |
| :--- | :--- |
| Lenguaje | Java |
| Plataforma | Android SDK 23 (mínimo 14) |
| Mapas | Google Play Services 8.4 |
| Build | Gradle con Android Gradle Plugin 2.3 |

## Ejecutarlo localmente

Importa el proyecto en Android Studio. Usa Android Gradle Plugin 2.3, `compileSdkVersion 23` y Google Play Services 8.4, por lo que necesita un JDK 8 y un Gradle antiguo para compilar. Las llaves de Google Maps se reemplazaron por `YOUR_GOOGLE_MAPS_API_KEY`.

## Estado del repositorio

- Se conserva sin cambios funcionales como referencia del código original (2018).
- No recibe actualizaciones de dependencias; el mantenimiento ocurre en [android-logistics-fleet-dispatch-platform](https://github.com/KevinAndrey96/android-logistics-fleet-dispatch-platform).
- En noviembre de 2026 se depuró el historial completo: se retiraron 42 APK compilados, la carpeta `.idea/` y la llave de Google Maps. Todos los commits conservan su fecha original.

## Autoría

Kevin Andrey Herrera Silva ([@KevinAndrey96](https://github.com/KevinAndrey96)).

## Licencia

Código desarrollado para un cliente y publicado como muestra de portafolio. No incluye licencia de código abierto: todos los derechos reservados.
