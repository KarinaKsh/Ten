# Aviso Legal — Guagua (nombre provisional)

> ⚠️ **Por qué existe este documento:** en España (y, en general, en toda la UE por la
> Directiva de Comercio Electrónico 2000/31/CE), cualquier servicio de la sociedad de la
> información — y una app con anuncios y cuentas de usuario lo es — tiene que identificar
> claramente quién está detrás, por ley (LSSI-CE, art. 10). Esto es distinto de la política
> de privacidad: la política de privacidad dice **qué datos se tratan**; el aviso legal dice
> **quién eres tú como responsable del servicio**. Rellena los `[COMPLETAR...]` antes de
> publicar la app.

**Titular del servicio:** [COMPLETAR: tu nombre completo, o razón social si operas como empresa]
**NIF/CIF:** [COMPLETAR]
**Domicilio:** [COMPLETAR: dirección postal — puede ser la de tu domicilio si publicas como autónomo/particular]
**Email de contacto:** [COMPLETAR]
**Nombre de la app:** Guagua — Transporte Tenerife
**Última actualización:** 17 de julio de 2026

## 1. Objeto

Guagua es una aplicación gratuita, con publicidad, que ofrece información de horarios,
paradas y rutas del transporte público de Tenerife (TITSA), a partir de datos GTFS
públicos. No es una app oficial de TITSA ni está afiliada a TITSA — ver sección 4.

## 2. Condiciones de uso

- La app se ofrece "tal cual", sin garantía de disponibilidad continua ni de ausencia de
  errores en los horarios mostrados (ver sección 4 sobre el origen de los datos).
- El uso de la app implica la aceptación de este aviso legal y de la
  [política de privacidad](politica-privacidad.md).
- No está permitido descompilar, realizar ingeniería inversa con fines de suplantación del
  servicio, ni usar la app para fines distintos de la consulta de información de transporte
  público.

## 3. Cuentas de usuario

Crear una cuenta es opcional y solo hace falta para guardar paradas y rutas favoritas.
Eres responsable de mantener la confidencialidad de tu contraseña. Puedes eliminar tu
cuenta en cualquier momento desde Cuenta → Eliminar cuenta — ver la política de privacidad
para el detalle de qué se borra.

## 4. Exactitud de los datos de transporte

Los horarios y paradas provienen de los ficheros GTFS que TITSA publica públicamente,
actualizados automáticamente (ver `gtfs_auto_update.py`). TITSA puede modificar sus
horarios reales sin que se reflejen aún en estos ficheros (obras, desvíos, festivos, huelgas,
etc.). **La app es una ayuda informativa, no una fuente oficial** — en caso de duda,
consulta siempre titsa.com o los paneles físicos en la parada.

## 5. Propiedad intelectual

- El código y diseño propios de la app son de [COMPLETAR: tu nombre/empresa].
- Los datos de paradas/horarios son de TITSA, publicados como datos abiertos.
- Los mapas y el cálculo de rutas a pie usan OpenStreetMap (© colaboradores de
  OpenStreetMap, licencia ODbL) y las bibliotecas de terceros listadas en Cuenta → Datos y
  atribuciones dentro de la propia app.

## 6. Publicidad

La app muestra anuncios de Google AdMob. Ver la sección 4 de la
[política de privacidad](politica-privacidad.md) para el detalle de qué datos trata AdMob
y cómo gestionar tus preferencias de anuncios (Cuenta → Preferencias de anuncios, visible
si estás en la Unión Europea o el Reino Unido).

## 7. Enlaces a terceros

La app enlaza o hace peticiones a servicios de terceros independientes (OpenStreetMap,
Nominatim, OpenRouteService, Supabase, Google AdMob) — no somos responsables de sus
propios contenidos, disponibilidad o políticas, listadas en la política de privacidad.

## 8. Ley aplicable y jurisdicción

Este aviso legal se rige por la legislación española. Para cualquier controversia, y sin
perjuicio de los derechos que como consumidor residente en la UE puedas tener a acudir a
los tribunales o a la [plataforma europea de resolución de litigios en línea](https://ec.europa.eu/consumers/odr/),
las partes se someten a los juzgados y tribunales que correspondan según la normativa de
protección de consumidores aplicable.

## 9. Modificaciones

Este aviso legal puede actualizarse si cambian las condiciones del servicio; la versión
vigente es siempre la publicada dentro de la app o en su repositorio.

---

### 📌 Notas técnicas (para ti, no para publicar)
- Si en algún momento cobras por la app o por funciones dentro de ella (compras integradas,
  suscripción sin anuncios, etc.), este documento necesita una sección adicional sobre
  condiciones de contratación, precios, IVA y derecho de desistimiento (14 días, Directiva
  2011/83/UE) — hoy no aplica porque la app es gratuita y solo se financia con anuncios.
- Si registras la app como actividad económica (autónomo/empresa), añade aquí también el
  número de registro mercantil si aplica.
