# Proyecto de Diseño de Aplicaciones Web

## Datos Personales
- **Nombre completo:** Aleksei Habid Torruco Montesijno
- **Matrícula:** AL02968638
- **Carrera:** Ingeniería en Software
- **Semestre:** 6

## Datos de la Materia
- **Nombre de la asignatura:** Diseño de Aplicaciones Web
- **Nombre del profesor:** Maestro

## Descripción
### ¿Qué es Markdown?
Markdown es un lenguaje de marcado ligero que se utiliza para dar formato a texto de manera sencilla y legible. Fue creado por John Gruber en 2004 con el objetivo de permitir a las personas escribir contenido formateado utilizando texto plano que sea fácil de leer y escribir.

**Principales usos de Markdown:**
- Crear documentación técnica y archivos README en repositorios de GitHub
- Escribir contenido para blogs y sitios web
- Tomar notas y crear documentos con formato básico
- Generar presentaciones y libros electrónicos
- Redactar mensajes en foros y plataformas de comunicación

La ventaja principal de Markdown es su simplicidad: utiliza caracteres especiales como `#` para encabezados, `*` para énfasis, `-` para listas, entre otros, lo que permite crear documentos bien estructurados sin necesidad de editores complejos. Además, es fácilmente convertible a HTML y otros formatos.

---

## Opciones de Etiquetado en Markdown
Markdown ofrece varias opciones para dar formato al texto. A continuación se explican las más utilizadas:

### 1. Títulos y Subtítulos
Se utiliza el símbolo `#` para crear títulos y subtítulos. Cuantos más `#`, menor el nivel del título.
```markdown
# Título principal
## Subtítulo
### Título de tercer nivel
```

### 2. Texto en Negritas y Cursivas
Permite resaltar palabras o frases importantes.
- **Negritas:** Se usan dos asteriscos `**texto**` o dos guiones bajos `__texto__`.
- *Cursivas:* Se usan un asterisco `*texto*` o un guión bajo `_texto_`.
- ***Negrita y cursiva:*** Tres asteriscos `***texto***`.

### 3. Listas Ordenadas y No Ordenadas
- **Listas no ordenadas:** Se usan guiones `-`, asteriscos `*` o signos `+`.
- **Listas ordenadas:** Se usan números seguidos de punto.
```markdown
- Elemento 1
- Elemento 2

1. Primer elemento
2. Segundo elemento
```

### 4. Enlaces
Permite agregar hipervínculos a texto.
```markdown
[Texto del enlace](https://www.ejemplo.com)
```

### 5. Imágenes
Permite insertar imágenes usando una sintaxis similar a los enlaces.
```markdown
![Texto alternativo](https://www.ejemplo.com/imagen.png)
```

### 6. Bloques de Código
Permite mostrar fragmentos de código usando tres acentos graves (```) antes y después del bloque.
```markdown
```
print("Hola Mundo")
```
```

---

## Comandos Básicos de Git
A continuación se listan y explican los comandos más utilizados en Git para gestionar repositorios:

### 1. Ver el estado del repositorio local
```bash
git status
```
Muestra los archivos modificados, agregados y eliminados, así como el estado general del repositorio.

### 2. Agregar archivos al Stage
- **Archivos individuales:**
```bash
git add archivo.txt
```
Agrega un archivo específico al área de preparación (stage).
- **Todos los archivos:**
```bash
git add .
```
Agrega todos los archivos modificados al stage.

### 3. Agregar comentarios a un commit
```bash
git commit -m "Mensaje del commit"
```
Guarda los cambios preparados en el repositorio local con un mensaje descriptivo.

### 4. Subir cambios al repositorio remoto
```bash
git push origin main
```
Envía los commits locales a la rama principal del repositorio remoto.

### 5. Crear, listar, cambiar y eliminar ramas
- **Crear rama:**
```bash
git branch nombre-rama
```
Crea una nueva rama.
- **Listar ramas:**
```bash
git branch
```
Muestra todas las ramas existentes.
- **Cambiar de rama:**
```bash
git checkout nombre-rama
```
Cambia a la rama seleccionada.
- **Eliminar rama:**
```bash
git branch -d nombre-rama
```
Elimina la rama especificada.

### 6. Regresar el repositorio a un commit específico (rollback)
```bash
git checkout <id-del-commit>
```
Permite regresar el repositorio al estado de un commit anterior.

---

## Referencias y Recursos
- [Documentación oficial de Git](https://git-scm.com/doc)
- [Guía de Markdown](https://www.markdownguide.org/)
- [Repositorio oficial de Laravel](https://github.com/laravel/laravel#readme)

---

> Este archivo README.md sirve como guía personal y referencia futura para el uso de Git y Markdown en proyectos de desarrollo.
