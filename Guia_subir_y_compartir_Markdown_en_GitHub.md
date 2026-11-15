# Guía práctica: subir y compartir un documento Markdown en GitHub

> **Objetivo:** crear un repositorio en GitHub, subir un archivo `.md` y compartir con otra persona el enlace directo al documento.
>
> **Nivel:** principiante. Todo se realiza desde el navegador, sin instalar programas ni escribir comandos.

## 1. Antes de empezar: tres conceptos

| Concepto | Significado sencillo |
|---|---|
| **GitHub** | Plataforma donde puedes almacenar y compartir archivos y proyectos. |
| **Repositorio** | Carpeta de un proyecto en GitHub, con sus archivos y el historial de cambios. |
| **Markdown (`.md`)** | Archivo de texto que permite crear títulos, listas, enlaces y otros formatos con una sintaxis sencilla. |

**Idea clave:** el repositorio es el contenedor; el archivo Markdown es el documento que vamos a guardar dentro.

## 2. Crear un repositorio nuevo

1. Entra en [GitHub](https://github.com/) e inicia sesión en tu cuenta.
2. Accede a [Crear un nuevo repositorio](https://github.com/new). También puedes pulsar el botón **+** (arriba a la derecha) y elegir **New repository**.
3. Completa los campos:

   | Campo de GitHub | Qué poner en este ejercicio |
   |---|---|
   | **Owner** (propietario) | Tu cuenta de GitHub. |
   | **Repository name** (nombre) | `guia-markdown-github` (nombre propuesto, porque no se oye el nombre exacto en el fragmento de clase). |
   | **Description** (descripción) | `Demostración para compartir documento Markdown` |
   | **Visibility** (visibilidad) | **Public** (público). |
   | **Add README** | **Activado**. |
   | **.gitignore / License y demás opciones** | Mantener los valores predeterminados para esta práctica. |

4. Pulsa **Create repository**.

✅ **Resultado esperado:** estarás dentro de tu repositorio. Verás, entre sus archivos, `README.md`.

> **Importante:** un repositorio **público** puede ser consultado por cualquier persona, no solo por quien reciba tu enlace. No subas datos de pacientes, contraseñas, información privada ni documentos que no tengas permiso para publicar.

## 3. Subir el documento Markdown

1. Dentro del repositorio, busca el botón **Add file** (encima de la lista de archivos).
2. Selecciona **Upload files**.
3. Pulsa **choose your files** o arrastra el archivo `.md` desde tu ordenador.
4. Selecciona el documento que quieres subir, por ejemplo, `Guia_subir_y_compartir_Markdown_en_GitHub.md`.
5. Comprueba que el archivo aparezca en la lista de elementos que vas a subir.
6. En el campo **Commit message** (mensaje del cambio), escribe:

   `Añadir primera guía Markdown`

7. Confirma la operación. Según la interfaz y el flujo, el botón puede decir **Commit changes**, **Commit changes...** o **Propose changes**; en algunos casos hay que elegir entre confirmar directamente en la rama o crear una propuesta de cambio.
8. Una vez confirmada la subida, regresa a la lista de archivos y comprueba que el documento aparece allí.

✅ **Resultado esperado:** tu archivo `.md` ya está guardado en GitHub.

### ¿Qué significa «commit»?

Un **commit** es un registro de un cambio en el repositorio. El mensaje *Añadir primera guía Markdown* explica qué has incorporado. **Subir el archivo** y **registrar el cambio** forman parte del proceso.

## 4. Compartir el documento con otra persona

1. Abre tu repositorio en GitHub.
2. **Haz clic en el nombre del archivo `.md`**, no te quedes solo en la página principal del repositorio.
3. Cuando veas el contenido del documento, copia la dirección completa de la barra del navegador (`Ctrl + L` y después `Ctrl + C` en Windows).
4. Pega ese enlace (`Ctrl + V`) en el correo, mensaje o documento donde quieras compartirlo.

**Ejemplo ficticio de enlace directo al archivo:**

`https://github.com/TU_USUARIO/guia-markdown-github/blob/main/Guia_subir_y_compartir_Markdown_en_GitHub.md`

> Sustituye `TU_USUARIO` por tu usuario real. La dirección exacta depende de tu cuenta, el repositorio, la rama y el nombre del archivo. **No copies este ejemplo como si fuera un enlace real.**

### Ojo: compartir el repositorio no es igual que compartir el archivo

- **Enlace al repositorio:** lleva a la carpeta principal y muestra todos los archivos públicos de ese proyecto.
- **Enlace al archivo:** lleva directamente al documento `.md` seleccionado.

Para este ejercicio, **comparte el enlace al archivo**, que es lo que quieres enseñar.

## 5. Mapa visual de los pasos

```text
GITHUB (iniciar sesión)
        ↓
NEW REPOSITORY
        ↓
Nombre + descripción + Public + README activado
        ↓
CREATE REPOSITORY
        ↓
ADD FILE → UPLOAD FILES → CHOOSE YOUR FILES
        ↓
Seleccionar documento .md
        ↓
Commit message: «Añadir primera guía Markdown»
        ↓
Confirmar el commit / cambio
        ↓
Abrir el archivo .md dentro del repositorio
        ↓
Copiar URL de la barra del navegador
        ↓
COMPARTIR ✅
```

## 6. Errores habituales (trampas de examen)

| Error | Qué debes recordar |
|---|---|
| Pensar que el README es el archivo que obligatoriamente debes subir | El `README.md` es la presentación del repositorio; puedes subir **otro `.md`** distinto. |
| Pensar que «Public» significa que solo accede quien recibe el enlace | **Público** significa accesible en general. |
| Seleccionar el archivo pero no confirmar los cambios | **Hay que completar el commit** para guardar la subida. |
| Copiar la dirección del repositorio cuando se pide la del documento | Abre **el archivo concreto** y copia su URL. |
| Creer que Markdown es un programa | Markdown es un formato de texto; `.md` es una extensión habitual de esos archivos. |

## 7. Preguntas tipo examen (con respuesta)

**1. ¿Qué es un repositorio?**  
Un espacio de GitHub donde se guardan los archivos de un proyecto y su historial de cambios.

**2. ¿Qué extensión tiene un documento Markdown?**  
`.md`.

**3. ¿Qué opción debes seleccionar para subir un archivo desde el navegador?**  
**Add file → Upload files → choose your files**.

**4. ¿Qué significa marcar «Public»?**  
Que el repositorio es público y otras personas pueden acceder a su contenido.

**5. ¿Qué opción activa un documento de presentación del repositorio?**  
**Add README**.

**6. ¿Para qué sirve el «Commit message»?**  
Para describir brevemente el cambio que se registra.

**7. ¿Cómo compartes directamente un Markdown subido a GitHub?**  
Abres el archivo `.md` dentro del repositorio y copias su URL.

## 8. Ficha de memoria rápida

**CREAR → SUBIR → GUARDAR → COMPARTIR**

- **Crear:** GitHub → New repository → nombre y descripción → Public → README activado → Create repository.
- **Subir:** Add file → Upload files → choose your files → elegir `.md`.
- **Guardar:** mensaje del commit → confirmar cambios.
- **Compartir:** abrir el `.md` → copiar la URL → enviarla.

**Una frase para recordar:** *Creo la carpeta, meto el documento, registro el cambio y comparto su dirección.*

---

## Fuentes para comprobar los pasos

- [GitHub Docs: crear un repositorio](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)
- [GitHub Docs: añadir un archivo a un repositorio](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
- [GitHub Docs: inicio rápido con repositorios](https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories)

*Guía elaborada a partir de la explicación compartida en clase, con aclaraciones y comprobación frente a la documentación de GitHub. Noviembre de 2026.*
