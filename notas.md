# Guía rápida de Markdown

Markdown permite escribir documentos con formato usando texto plano. Esta guía recoge las opciones compatibles con GitHub.

## Índice

- [Encabezados](#encabezados)
- [Énfasis](#énfasis)
- [Listas](#listas)
- [Enlaces e imágenes](#enlaces-e-imágenes)
- [Citas y separadores](#citas-y-separadores)
- [Código](#código)
- [Tablas](#tablas)
- [Casillas de tareas](#casillas-de-tareas)
- [Avisos de GitHub](#avisos-de-github)
- [Consejos](#consejos)

## Encabezados

Los encabezados se crean con uno a seis simbolos `#`, seguidos de un espacio.

```markdown
# Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3
#### Encabezado nivel 4
##### Encabezado nivel 5
###### Encabezado nivel 6
```

## Énfasis

| Resultado | Sintaxis Markdown |
| --- | --- |
| **Texto en negrita** | `**Texto en negrita**` |
| *Texto en cursiva* | `*Texto en cursiva*` |
| ***Texto en negrita y cursiva*** | `***Texto en negrita y cursiva***` |
| ~~Texto tachado~~ | `~~Texto tachado~~` |
| `Código en línea` | `` `Código en línea` `` |

> Recomendación: usa negrita para destacar información importante y cursiva con moderación.

## Listas

### Lista con viñetas

```markdown
- Primer elemento
- Segundo elemento
  - Elemento anidado
  - Otro elemento anidado
- Tercer elemento
```

- Primer elemento
- Segundo elemento
  - Elemento anidado
  - Otro elemento anidado
- Tercer elemento

### Lista numerada

```markdown
1. Preparar el documento
2. Revisar el contenido
3. Publicar los cambios
```

1. Preparar el documento
2. Revisar el contenido
3. Publicar los cambios

GitHub renumera automaticamente los elementos de una lista numerada.

## Casillas de tareas

```markdown
- [ ] Tarea pendiente
- [ ] Otra tarea pendiente
- [x] Tarea completada
```

- [ ] Tarea pendiente
- [ ] Otra tarea pendiente
- [x] Tarea completada

Las casillas pueden seleccionarse directamente en issues y pull requests de GitHub.

## Enlaces e imágenes

### Enlaces

```markdown
[Texto visible](https://www.devtalles.com/)
```

Enlace de ejemplo: [DevTalles](https://www.devtalles.com/)

Puedes crear tambien enlaces dentro del documento:

```markdown
[Ir a consejos](#consejos)
```

### Imágenes

```markdown
![Texto alternativo](imagen.png)
```

El texto alternativo describe la imagen y mejora su accesibilidad.

## Citas y separadores

### Cita

```markdown
> Markdown permite presentar citas o notas destacadas.
```

> Markdown permite presentar citas o notas destacadas.

### Línea horizontal

Usa tres o mas guiones para separar secciones:

```markdown
---
```

---

## Código

### Código en línea

```markdown
Usa el comando `git status` para ver los cambios actuales.
```

Usa el comando `git status` para ver los cambios actuales.

### Bloque de código

Especifica el lenguaje después de las tres comillas invertidas para activar el resaltado de sintaxis:

````markdown
```javascript
const suma = (a, b) => a + b;
console.log(suma(2, 3));
```
````

```javascript
const suma = (a, b) => a + b;
console.log(suma(2, 3));
```

## Tablas

```markdown
| Comando | Descripción |
| :------ | :---------- |
| `git add` | Prepara los cambios |
| `git commit` | Guarda una revisión |
| `git push` | Sube los cambios al remoto |
```

| Comando | Descripción |
| :------ | :---------- |
| `git add` | Prepara los cambios |
| `git commit` | Guarda una revision |
| `git push` | Sube los cambios al remoto |

Los dos puntos permiten controlar la alineación:

| Sintaxis | Alineación |
| --- | --- |
| `:---` | Izquierda |
| `:---:` | Centrada |
| `---:` | Derecha |

## Avisos de GitHub

GitHub admite bloques de aviso especiales para destacar información.

```markdown
> [!NOTE]
> Información complementaria para el lector.

> [!TIP]
> Una recomendación que puede facilitar el trabajo.

> [!IMPORTANT]
> Información necesaria para continuar correctamente.

> [!WARNING]
> Algo que requiere precaución.

> [!CAUTION]
> Una acción que podría causar consecuencias negativas.
```

> [!NOTE]
> Informacion complementaria para el lector.

> [!TIP]
> Una recomendación que puede facilitar el trabajo.

> [!IMPORTANT]
> Informacion necesaria para continuar correctamente.

> [!WARNING]
> Algo que requiere precaución.

> [!CAUTION]
> Una acción que podría causar consecuencias negativas.

## Consejos

- Deja una línea en blanco entre párrafos y bloques; de lo contrario, pueden mostrarse juntos.
- Termina una línea con dos espacios para forzar un salto de línea sin comenzar un párrafo nuevo.
- Usa una barra invertida (`\`) para mostrar un caracter Markdown como texto literal:
  - `\*` muestra `*`
  - `\#` muestra `#`
- Previsualiza el documento con la pestaña **Preview** antes de guardarlo.
- Usa un lenguaje descriptivo para el texto alternativo de las imágenes.

## Aprende más

¿Quieres profundizar en Git, GitHub y desarrollo web? Explora los cursos completos en español de [DevTalles](https://cursos.devtalles.com).
