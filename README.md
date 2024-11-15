# Guía de comandos Git 

En este documento encontrarás los **comandos básicos** de `git` con diferentes estilos de texto para que puedas aprender tanto los comandos como el uso de archivos `.md`.

## 1. **`git init`**

- **Descripción:**  
  Este comando inicializa un nuevo repositorio de Git.  
  **Ejemplo de uso:**  
  ```bash
  git init
  ```

## 2. *`git clone`*

> **Descripción:**  
> Este comando se usa para clonar un repositorio existente desde un servidor remoto.

 **Ejemplo de uso:**
```bash
git clone https://github.com/usuario/repo.git
```

## 3. `git status`

`git status` muestra el estado actual del repositorio, incluyendo archivos modificados y cambios no confirmados.

 **Ejemplo de uso:**
```bash
git status
```

## 4. `git add`

Este comando agrega cambios al área de preparación (_staging area_).

```diff
+ git add .
```

## 5. `git commit`

`git commit` guarda los cambios agregados al área de preparación en el historial del repositorio.

```bash
git commit -m "Mensaje del commit"
```

## 6. **_`git push`_**

Envía los cambios locales al repositorio remoto.

```bash
git push origin main
```

## 7. ***`git pull`***

Actualiza el repositorio local con los últimos cambios del remoto.

```bash
git pull origin main
```

## 8. `git branch`

Muestra las ramas actuales del repositorio.

```css
git branch
```

## 9. `git merge`

Une los cambios de una rama a otra.

```bash
git merge nombre-de-la-rama
```

## 10. `git checkout`

Cambia de una rama a otra o restaura archivos.

```bash
git checkout nombre-de-la-rama
```

## 11. **Tablas en Markdown para Git**

| Comando       | Descripción                          |
|---------------|--------------------------------------|
| `git log`     | Muestra el historial de commits      |
| `git diff`    | Muestra las diferencias entre commits|
| `git reset`   | Deshace cambios                      |

---




---

# Tipos de Texto en archivo .md

Markdown (md) permite utilizar diferentes estilos de texto y elementos visuales para mejorar la legibilidad y presentación de los documentos. Aquí tienes algunos ejemplos:

## 1. **Encabezados**

Usa `#` para crear encabezados:

```markdown
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
```

# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6

## 2. **Negrita y Cursiva**

- **Negrita:** Usa `**texto**` o `__texto__`.
- *Cursiva:* Usa `*texto*` o `_texto_`.
- **_Negrita y Cursiva:_** Usa `**_texto_**`.

Ejemplo:
```markdown
**Texto en negrita**
*Texto en cursiva*
**_Texto en negrita y cursiva_**
```

## 3. **Listas**

- **Lista ordenada:** Usa números.
  ```markdown
  1. Primer elemento
  2. Segundo elemento
  3. Tercer elemento
  ```

- **Lista desordenada:** Usa `-`, `*` o `+`.
  ```markdown
  - Elemento uno
  - Elemento dos
  - Elemento tres
  ```

## 4. **Citas**

Para incluir citas, usa `>`.
```markdown
> Esta es una cita en Markdown.
```

> Esta es una cita en Markdown.

## 5. **Código**

- **Código en línea:** Usa `` `código` ``.
- **Bloques de código:**
  ```markdown

   ```python
  print("Hola, mundo!") ```
   
  ```

Ejemplo:
```python
print("Hola, mundo!")
```

## 6. **Enlaces e Imágenes**

- **Enlace:**
  ```markdown
  [Texto del enlace](https://github.com/OmarRoano/practica_form_html)
  ```

  [Visita GitHub](https://github.com/OmarRoano/practica_form_html)

- **Imagen:**
  ```markdown
  ![Nombre de la imagen](https://images.unsplash.com/photo-1726853546098-380e29da9e31?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)
  ```

  ![Ejemplo de imagen](https://images.unsplash.com/photo-1726853546098-380e29da9e31?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

## 7. **Tablas**

Puedes crear tablas con el siguiente formato:

```markdown
| Encabezado 1 | Encabezado 2 |
|--------------|--------------|
| Celda 1     | Celda 2      |
| Celda 3     | Celda 4      |
```

| Encabezado 1 | Encabezado 2 |
|--------------|--------------|
| Celda 1     | Celda 2      |
| Celda 3     | Celda 4      |

## 8. **Separadores**

Usa `---`, `***` o `___` para añadir líneas horizontales.

Ejemplo:
```markdown
---
***
___
```

---

## 9. **Emojis**

Puedes agregar emojis usando su código:

```markdown
:smile: :rocket: :+1:
```

😄 🚀 👍

## 10. **Tareas**

Puedes crear listas de tareas:

```markdown
- [x] Tarea completada
- [ ] Tarea pendiente
```

- [x] Tarea completada
- [ ] Tarea pendiente

---


