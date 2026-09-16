# Ficha de Play Store — Agroreg

## Descripción corta (máx. 80 caracteres)

Registrá labores agrícolas, dosis y costos de tu campo, simple y offline.

## Descripción completa (máx. 4000 caracteres)

Agroreg es la app para llevar el registro de labores agrícolas de tu campo o de los campos que atendés como contratista — siembras, fumigaciones, fertilizaciones, cortes, cosechas y más — con sus productos, dosis y costos.

FUNCIONA SIN INTERNET
Toda tu información queda guardada en tu propio celular o computadora. No necesitás conexión para cargar ni consultar tus registros.

PARA PRODUCTORES Y CONTRATISTAS
Organizá tus lotes por establecimiento (si sos productor) o por cliente (si sos contratista) — sin que uno dependa del otro.

CARGA RÁPIDA POR LOTE
Elegí uno o varios lotes, el tipo de labor y los productos aplicados con su dosis. Si varios lotes comparten la misma labor, se cargan todos juntos en una sola pasada.

COSTOS EN DÓLARES Y PESOS
Cada producto tiene su precio en U$D; la app calcula el costo total en dólares y en pesos según el tipo de cambio que vos cargues, por hectárea y total.

INFORMES CLAROS
- Costos totales por lote o por establecimiento/cliente, con filtro de fechas.
- Labores sin insumo (mano de obra) agrupadas por titular, para saber qué facturarle a cada cliente.

EXCEL: RESPALDO E IMPORTACIÓN
Exportá toda tu base a un Excel con una hoja por tabla — te sirve de respaldo y también como plantilla: completala o corregila a mano y volvé a importarla para agregar registros o maestros nuevos, sin perder nada de lo que ya tenías cargado.

RECALCULAR COSTOS
Si actualizaste el precio de un producto, podés recalcular de una todos los registros afectados con el precio nuevo, o solo completar los que quedaron sin costo cargado.

Agroreg es para quien lleva sus cuentas de campo hoy en una planilla o a mano, y quiere algo más simple, rápido y siempre a mano en el celular.

## Categoría sugerida

**Productividad** (alternativa: Negocios) — no hay una categoría específica de "agro" en Play Store.

---

# Formulario de Seguridad de los datos

Basado en lo que Agroreg realmente hace: solo junta nombre y email para el login
(Supabase Auth) — el registro de tu operación (lotes, labores, costos) nunca sale
del dispositivo.

## Preguntas generales

- **¿Tu app recopila o comparte alguno de los tipos de datos de usuario requeridos?** Sí.
- **¿Toda esta información se transmite de forma cifrada?** Sí (todo el tráfico con Supabase va por HTTPS).
- **¿Ofrecés una forma de que los usuarios pidan que se borren sus datos?** Sí → enlace: `https://reivax78.github.io/agroreg-web/eliminar-cuenta.html`

## Tipos de datos a declarar

Solo dos, dentro de "Información personal":

| Tipo de dato | ¿Se recopila? | ¿Se comparte con terceros? | ¿Obligatorio? | Para qué se usa |
|---|---|---|---|---|
| Nombre | Sí | No* | Sí | Gestión de la cuenta |
| Dirección de email | Sí | No* | Sí | Gestión de la cuenta, funcionalidad de la app |

*Supabase es el proveedor de infraestructura que aloja tu propio backend de
login (no un tercero comercial que recibe tus datos para sus propios fines) —
por eso se marca "No" en "compartir con terceros". Es tu decisión final, pero
es el criterio estándar para este tipo de proveedor.

**Todo lo demás en el formulario** (ubicación, info financiera, fotos, contactos,
salud, mensajes, actividad de navegación, etc.) → **no se recopila**, se deja
sin tildar. Los montos/costos que cargás en la app son datos de tu negocio que
quedan en tu dispositivo, no datos que la app "recopile" hacia un servidor.

## Cuestionario de clasificación de contenido (IARC)

Es un formulario de preguntas sí/no sobre violencia, contenido sexual, apuestas,
drogas/alcohol, contenido generado por usuarios, ubicación compartida, etc.
Para Agroreg, la respuesta es **"No" a todo** — no tiene ninguno de esos
elementos. Que la app mencione productos agroquímicos (herbicidas, etc.) no
cuenta como "contenido de drogas" en este cuestionario (eso se refiere a
alcohol/tabaco/drogas recreativas). El resultado te va a dar la clasificación
más baja disponible (apta para todo público).

## Público objetivo

**18 años o más** — es una herramienta de gestión profesional, no está
dirigida a chicos. Cuando te pregunte "¿la app está diseñada principalmente
para niños?" → No.

## Anuncios

**No, mi app no contiene anuncios.**

## Otras declaraciones (todas "No" / no aplica para Agroreg)

- App gubernamental: No.
- App de noticias: No.
- Funciones financieras (crédito, préstamos, cripto): No — llevar costos de tu
  propia producción no entra en esta categoría regulada.
- Rastreo de contactos COVID-19: No.
