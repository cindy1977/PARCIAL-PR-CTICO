INSTRUCCIONES
EXAMEN PRÁCTICO DE GITHUB BÁSICO CON CODESPACES

Objetivo

Demostrar el dominio del flujo básico de trabajo con Git y GitHub utilizando **GitHub Codespaces**.

Durante el examen deberás demostrar:

**Fork → Codespace → Branch → Edit → Add → Commit → Push → Pull Request → Merge → Pull**

# PARTE 1. Crear tu FORK

El docente proporcionará la URL del repositorio original. ENVIADO AL WHATSAPP


### 1. Ingresa al repositorio

Abre el enlace proporcionado por el docente.

### 2. Haz clic en:

**Fork**

### 3. Selecciona tu cuenta de GitHub

En **Owner**, selecciona tu usuario.

Puedes conservar el nombre del repositorio.

Luego selecciona:

**Create fork**

Ahora tendrás tu propia copia:

```text
Repositorio original
        ↓
      FORK
        ↓
Tu repositorio
```

---

# PARTE 2. Abrir GitHub Codespaces

Entra a **TU FORK**.

No debes trabajar en el repositorio original del docente.

En tu Fork:

1. Selecciona el botón **Code**.
2. Selecciona **Codespaces**.
3. Selecciona **Create codespace on main**.

Espera mientras GitHub prepara el entorno.

Se abrirá **Visual Studio Code en el navegador**.

---

# PARTE 3. Verificar el repositorio

Cuando se abra Codespaces, encontrarás:

* Explorador de archivos.
* Editor.
* Terminal.
* Control de código fuente.

Abre la terminal:

**Terminal → New Terminal**

Ejecuta:  VER EL ESTADO DEL REPOSITORIO

Debes observar que estás trabajando sobre: DONDE ESTAS UBICADO


# PARTE 4. Crear tu BRANCH
 **NO debes realizar el examen directamente sobre `main`.**

Crea una rama 
Comprueba la rama
```text
* feature/juan-perez
  main
```

El `*` indica la rama en la que estás trabajando.

---

# PARTE 5. Realizar el cambio

Ahora trabaja en tu rama.

## Cambio 1

Ve a:

```text
participantes/plantilla.md
```

Copia el archivo y crea:

```text
participantes/nombre-apellido.md
```

Ejemplo:

```text
participantes/juan-perez.md
```

Completa:

```text
Nombre:
Carrera/curso:
Rol:
Herramienta tecnológica:
Meta de aprendizaje:
```

---

## Cambio 2

Abre:

```text
web/index.html
```

Busca:

```html
<h2>Equipo</h2>
```

Agrega tu nombre.

Ejemplo:

```html
<li>Juan Pérez — Estudiante</li>
```

---

# PARTE 6. Revisar los cambios



Debes revisar que solamente hayas realizado los cambios solicitados.

---

# PARTE 7. Agrega los cambios


Los archivos deberán aparecer como preparados para realizar el commit.

---

# PARTE 8. CONTINUA CON LO QUE YA SABES HACER



# PARTE 9. REVISIÓN DEL DOCENTE

El docente revisará tu Pull Request.

Se comprobará:

* Tu nombre.
* Tu rama.
* Los archivos modificados.
* El commit.
* El contenido.
* El historial.
* El destino del Pull Request.

Si el docente solicita una corrección:

### NO debes crear otro Pull Request.

Regresa a tu Codespace.

Comprueba que estás en tu rama:


Realiza la corrección.


## Lo que se evaluará

El objetivo no es solamente que el cambio aparezca en GitHub.

Se evaluará que el estudiante pueda demostrar el flujo completo:

**Fork → Codespace → Branch → Edit → Add → Commit → Push → Pull Request → Review → Merge → Pull**
