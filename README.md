# TOP SECRET - Cuenta atrás

> **ACCESO RESTRINGIDO**
>
> Aplicación web interactiva de cuenta atrás con estética de archivo clasificado.

## Descripción

**TOP SECRET - Cuenta atrás** es una página web diseñada para consultar el tiempo restante hasta diferentes momentos importantes del curso.

El proyecto está dividido en tres categorías:

* **NAVIDAD**
* **SEMANA SANTA**
* **FINAL DE CURSO**

Cada categoría contiene tres apartados:

* **DÍAS RESTANTES**
* **SEMANAS RESTANTES**
* **MESES RESTANTES**

La información se encuentra inicialmente oculta y debe ser revelada para poder consultarla.

---

## Sistema de bloqueo

El proyecto incluye un sistema automático de bloqueo durante determinados periodos de vacaciones.

Cuando comienza uno de los periodos configurados, el acceso queda bloqueado y se muestra una pantalla de aviso junto con una cuenta atrás hasta el final del periodo.

Una vez finalizado el periodo de bloqueo, el acceso vuelve a estar disponible automáticamente.

---

## Características

* Interfaz oscura con estética de archivo clasificado.
* Tres categorías principales.
* Sistema de carpetas interactivas.
* Información oculta hasta su revelación.
* Cuenta atrás en días, semanas y meses.
* Reloj en tiempo real.
* Sistema automático de bloqueo durante vacaciones.
* Diseño adaptable a diferentes tamaños de pantalla.
* Efectos de sonido mediante Web Audio API.
* No requiere instalación.
* No requiere conexión a Internet para funcionar.
* No utiliza librerías externas.
* Todo el proyecto está contenido en un único archivo HTML.

---

## Cómo utilizarlo

Para utilizar la aplicación, simplemente abre el archivo:

```text
index.html
```

con un navegador compatible, como Microsoft Edge, Google Chrome o Mozilla Firefox.

No es necesario instalar ningún programa adicional.

---

## Cómo descargar y guardar la página

Si estás viendo la página directamente desde un navegador y quieres guardar una copia para utilizarla posteriormente:

1. Haz **clic derecho** en cualquier parte de la página.
2. Selecciona **"Guardar como..."**.
3. Elige la ubicación donde quieres guardar el archivo.
4. En el tipo de archivo, selecciona **"Página web, completa"** si está disponible.
5. Guarda el archivo.
6. Abre el archivo HTML guardado para utilizar la página.

Para mantener el proyecto completamente independiente, se recomienda conservar todos los archivos generados por el navegador en la misma carpeta.

Si el proyecto está formado únicamente por `index.html` y no contiene recursos externos, también puedes guardar directamente ese archivo y abrirlo posteriormente sin conexión a Internet.

---

## Modificación de las fechas

Las fechas principales se encuentran al principio del código JavaScript para facilitar su modificación:

```js
const FECHA_NAVIDAD = "2026-12-23T14:00:00";
const FECHA_SEMANA_SANTA = "2027-03-27T14:00:00";
const FECHA_FINAL_CURSO = "2027-06-22T14:00:00";

const FIN_NAVIDAD = "2027-01-10T23:59:59";
const FIN_SEMANA_SANTA = "2027-04-05T23:59:59";
const FIN_FINAL_CURSO = "2027-09-07T23:59:59";
```

### Formato de las fechas

Las fechas utilizan el siguiente formato:

```text
AAAA-MM-DDTHH:MM:SS
```

Por ejemplo:

```text
2027-06-22T14:00:00
```

corresponde al **22 de junio de 2027 a las 14:00:00**.

---

## Estructura del proyecto

```text
TOP-SECRET/
│
├── index.html
└── README.md
```

El archivo `index.html` contiene todo el funcionamiento de la aplicación.

El archivo `README.md` contiene la documentación del proyecto.

---

## Requisitos

No se requiere ningún software especial.

Únicamente es necesario disponer de:

* Un navegador web moderno.
* El archivo `index.html`.

La aplicación puede ejecutarse localmente y funcionar sin conexión a Internet.

---

## Privacidad

La aplicación no necesita una cuenta de usuario, servidor ni base de datos.

Los cálculos de las cuentas atrás se realizan directamente en el navegador.

No se requiere enviar información a ningún servidor externo.

---

## Licencia

Proyecto personal y experimental.

El código puede modificarse y adaptarse para proyectos personales.

---

## Estado del proyecto

**ESTADO:** ACTIVO

**VERSIÓN:** 1.0

**NIVEL DE ACCESO:** RESTRINGIDO

**AUTORIZACIÓN:** NECESARIA

---

## Archivo clasificado

Este documento forma parte del proyecto **TOP SECRET - Cuenta atrás**.

El acceso y modificación del contenido queda bajo responsabilidad del usuario.
