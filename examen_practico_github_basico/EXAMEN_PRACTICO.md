# EXAMEN PRÁCTICO — GITHUB BÁSICO

## Tiempo sugerido
45–60 minutos.

## Situación
El proyecto **Campus Digital** necesita incorporar información de un nuevo integrante del equipo.

Cada estudiante trabajará sobre una rama propia.

## Parte 1 — Preparación

Clona este repositorio:

```bash
git clone URL_DEL_REPOSITORIO
cd examen-practico-github-basico
```

Verifica la rama actual:

```bash
git branch
```

Actualiza la información de `main`:

```bash
git checkout main
git pull origin main
```

## Parte 2 — Crear la rama

Crea una rama con este formato:

```bash
git checkout -b feature/nombre-apellido
```

Ejemplo:

```bash
git checkout -b feature/cindy-esquivel
```

Comprueba que estás en la rama correcta:

```bash
git branch
```

## Parte 3 — Realizar el cambio

Abre:

```text
participantes/plantilla.md
```

Copia el archivo y cambia su nombre a:

```text
participantes/nombre-apellido.md
```

Completa:

- Nombre:
- Carrera/curso:
- Rol:
- Una herramienta tecnológica que utilizas:
- Una meta de aprendizaje:

También modifica `web/index.html` para agregar tu nombre en la sección **Equipo**.

### Condición
Debes realizar al menos **dos cambios reales**:
1. Crear tu ficha en `participantes/`.
2. Modificar `web/index.html`.

## Parte 4 — Revisar los cambios

Ejecuta:

```bash
git status
```

Y:

```bash
git diff
```

## Parte 5 — Add

Agrega los cambios:

```bash
git add .
```

Verifica:

```bash
git status
```

## Parte 6 — Commit

Realiza un commit descriptivo:

```bash
git commit -m "feat: agrega perfil de nombre apellido"
```

Verifica el historial:

```bash
git log --oneline -5
```

## Parte 7 — Push

Publica la rama:

```bash
git push -u origin feature/nombre-apellido
```

## Parte 8 — Pull Request

En GitHub:

1. Entra al repositorio.
2. Abre la opción **Pull requests**.
3. Selecciona **New pull request**.
4. Base: `main`.
5. Compare: `feature/nombre-apellido`.
6. Título: `feat: agrega perfil de Nombre Apellido`.
7. En la descripción explica brevemente qué cambiaste.
8. Crea el Pull Request.

## Parte 9 — Revisión y Merge

El docente revisará:

- rama correcta;
- archivos modificados;
- commit;
- descripción;
- ausencia de cambios directos innecesarios en `main`.

Después de la revisión, se realizará el **Merge Pull Request**.

## Parte 10 — Pull final

Después del merge, actualiza tu copia local:

```bash
git checkout main
git pull origin main
```

Comprueba que el cambio integrado está presente:

```bash
git log --oneline -5
```

Opcionalmente elimina la rama local:

```bash
git branch -d feature/nombre-apellido
```

## Evidencias que debe entregar el estudiante

Entregar capturas o enlaces donde se observe:

1. Rama creada.
2. `git status` mostrando el trabajo.
3. Commit realizado.
4. Push de la rama.
5. Pull Request.
6. Pull Request aprobado/revisado.
7. Merge realizado.
8. `git pull` posterior al merge.
9. Resultado final del proyecto.

## Importante
No se evalúa únicamente que el archivo final exista. Se evalúa que el estudiante demuestre el flujo Git/GitHub completo.
