# Política de Privacidad — Guagua (nombre provisional)

> ⚠️ **Aviso:** plantilla lista para usar, ajustada a cómo funciona la app hoy. Antes de publicarla, revisa que los datos de contacto estén completos. No hace falta un abogado para un lanzamiento pequeño/personal — solo tenlo en cuenta si el proyecto crece a algo comercial con mucho tráfico.

**Última actualización:** 17 de julio de 2026
**Responsable:** [COMPLETAR: tu nombre o el de tu empresa]
**Contacto:** [COMPLETAR: email de contacto]

Para saber quién es exactamente el responsable de este servicio (identidad, NIF, domicilio),
consulta el [aviso legal](aviso-legal.md) — este documento trata solo de qué datos se usan y
para qué.

---

## 1. Resumen en una frase

**No recopilamos, almacenamos ni rastreamos tu ubicación.** La usamos únicamente, en el momento en que la pides, para calcular la parada de autobús más cercana o una ruta a pie — y solo mientras usas esa pantalla concreta.

## 2. Qué datos usa la app y por qué

| Dato | ¿Cuándo? | ¿Para qué? | ¿Se guarda? |
|---|---|---|---|
| Tu ubicación (GPS) | Solo si tú la activas al buscar "mi ubicación actual" o abrir el mapa | Calcular qué parada está más cerca de ti y la ruta a pie hasta ella | **No.** Se usa una sola vez y se descarta al momento; no se guarda en tu dispositivo ni se envía a ningún servidor nuestro |
| Direcciones que escribes | Al buscar una ruta o la parada más cercana | Convertir la dirección en coordenadas para calcular la ruta | No se guarda un historial |
| Idioma elegido | Al abrir la app por primera vez | Mostrar la interfaz en tu idioma | Solo en tu propio dispositivo, para recordarlo la próxima vez |

No pedimos tu ubicación en segundo plano, no la asociamos a tu identidad, y no la usamos para publicidad ni analítica. La app sí muestra anuncios en algunas pantallas (ver sección 4), pero no lo hace usando tu ubicación.

## 3. Con quién se comparte esa información (servicios de terceros)

Cuando pides una ruta a pie o buscas una dirección, esa consulta puntual se envía a servicios externos independientes de nosotros, necesarios para poder calcular el resultado:

- **OpenStreetMap Nominatim** — convierte la dirección que escribes en coordenadas.
- **OSRM / FOSSGIS o OpenRouteService** — calcula la ruta a pie hasta la parada.
- **OpenStreetMap** — sirve las imágenes del mapa.

Estos servicios pueden registrar la IP y la consulta según sus propias políticas:
- OpenStreetMap Foundation: https://osmfoundation.org/wiki/Privacy_Policy
- FOSSGIS e.V.: https://www.fossgis.de/datenschutz/

Esta consulta puntual no se comparte con nadie más, y no se usa con fines publicitarios: es un dato de geocodificación/ruta, no de anuncios.

## 4. Publicidad (AdMob)

La app muestra anuncios en banner (Google AdMob, de Google Ireland Ltd.) en las pantallas de Inicio, Favoritos, Cuenta y el listado de líneas. No se muestran anuncios en el mapa a pantalla completa, en la pantalla de construcción de ruta ni en la bienvenida inicial.

**Si estás en la Unión Europea, el Espacio Económico Europeo o el Reino Unido**, antes de pedir ningún anuncio la app te muestra primero la pantalla de consentimiento oficial de Google (su "UMP", Plataforma de Gestión de Consentimiento) — no se solicita ningún anuncio hasta que la resuelvas. Puedes cambiar tu elección cuando quieras desde Cuenta → Preferencias de anuncios (ese botón solo aparece si estás en una de esas regiones, porque fuera de ellas no existe tal pantalla).

Para poder mostrar y medir estos anuncios, Google AdMob (y su SDK, integrado en la app) puede recopilar y procesar automáticamente:
- Identificadores de publicidad del dispositivo (como el IDFA en iOS o el GAID en Android), salvo que los hayas desactivado en los ajustes de tu sistema operativo o hayas denegado el permiso de seguimiento cuando la app te lo solicite (en iOS, vía App Tracking Transparency).
- Dirección IP aproximada y datos técnicos del dispositivo (modelo, sistema operativo, idioma).
- Interacciones con los anuncios (impresiones, clics), para medir su rendimiento.

Estos datos los trata Google conforme a su propia política de privacidad, no la nuestra: https://policies.google.com/privacy — nosotros no tenemos acceso a esos identificadores ni los combinamos con tu cuenta o tus favoritos. Puedes gestionar la personalización de anuncios de Google desde https://adssettings.google.com y, en iOS, desde Ajustes → Privacidad → Seguimiento.

## 5. Cuentas de usuario y favoritos

Si creas una cuenta para guardar tus paradas y rutas favoritas, guardamos: tu email (para el login) y las paradas/rutas que marques como favoritas, en una base de datos gestionada por Supabase (Supabase Inc., alojada en la UE si eliges esa región de proyecto). Nada más — no guardamos tu historial de ubicaciones ni de búsquedas pasadas, ni tu posición en ningún momento.

## 6. Cuánto tiempo conservamos tus datos

- **Email y favoritos:** mientras tu cuenta exista. Se borran de forma permanente e inmediata en cuanto pulsas Cuenta → Eliminar cuenta (ver sección 7) — no guardamos copia aparte.
- **Idioma y tema (claro/oscuro):** solo en tu propio dispositivo, hasta que borres los datos de la app o la desinstales; nunca llega a nuestros servidores.
- **Ubicación GPS y direcciones buscadas:** no se guardan en ningún momento, ni en el dispositivo ni en servidor — se descartan en cuanto se calcula el resultado.
- **Identificadores de publicidad (AdMob):** los retiene Google según sus propios plazos, no los nuestros — ver su política de privacidad enlazada en la sección 4.

## 7. Base legal (para usuarios en la Unión Europea / RGPD)

- El acceso puntual a tu ubicación se basa en tu **consentimiento explícito** (el permiso que concede tu sistema operativo en el momento).
- El resto de procesamiento se basa en la **ejecución del servicio que solicitas** (mostrarte una ruta, guardar un favorito).
- Los anuncios personalizados y el uso de identificadores de publicidad se basan en tu **consentimiento**, recogido mediante la pantalla de consentimiento de Google (sección 4) si estás en la UE/EEE/Reino Unido, o en los ajustes de anuncios de tu sistema operativo fuera de esas regiones.

## 8. Tus derechos

Tienes derecho a acceder, rectificar, eliminar, limitar u oponerte al tratamiento de tus datos, y a la portabilidad de los mismos, escribiendo a [COMPLETAR email]. En concreto, y sin necesidad de escribirnos:
- **Acceso y portabilidad:** Cuenta → Descargar mis datos, te descarga un fichero con tu email y tus favoritos.
- **Supresión:** Cuenta → Eliminar cuenta, borra tu email y tus favoritos de forma permanente e inmediata.
- **Retirar el consentimiento de anuncios:** Cuenta → Preferencias de anuncios (UE/EEE/Reino Unido) o los ajustes de anuncios de tu sistema operativo.

Para los datos que trata Google/AdMob, ejerce tus derechos directamente con Google. También tienes derecho a reclamar ante tu autoridad de protección de datos — en España, la Agencia Española de Protección de Datos (aepd.es).

## 9. Menores de edad

La app no está dirigida específicamente a menores de edad y no recopilamos intencionadamente datos de menores. Los anuncios de AdMob se sirven en modo no personalizado por defecto en cuentas identificadas como de menores, conforme a las políticas de Google.

## 10. Cambios en esta política

Podemos actualizar esta política si cambia cómo funciona la app. Publicaremos la nueva versión con fecha de actualización.

## 11. Contacto

Para cualquier duda sobre esta política: [COMPLETAR email]

---

### 📌 Notas técnicas (para ti, no para publicar)
- Cuando actives el geocodificador/router de pago (OpenRouteService u otro), actualiza el nombre del proveedor en la sección 3.
- Si Supabase almacena datos fuera de la UE (revisa la región elegida al crear el proyecto), esta política necesita mencionar la transferencia internacional de datos.
- Revisa esta política cada vez que añadas una función nueva que toque datos personales (por ejemplo, notificaciones push, analítica, pagos).
- Si más adelante añades anuncios intersticiales, de recompensa, o AdMob "personalizados" (no solo banner), amplía la sección 4 en consecuencia.
- Antes de publicar: sube este documento y `aviso-legal.md` a algún sitio con URL pública (GitHub Pages, por ejemplo) y rellena `PRIVACY_POLICY_URL` / `LEGAL_NOTICE_URL` en `index.html` con esas URLs — si no, los botones de Cuenta → Política de privacidad / Aviso legal no funcionan.
- En el panel de AdMob (admob.google.com → Privacy & messaging → GDPR), tienes que crear el mensaje de consentimiento una vez — el código ya está listo para mostrarlo, pero el propio mensaje (textos, enlaces) se configura ahí, no en el código.

