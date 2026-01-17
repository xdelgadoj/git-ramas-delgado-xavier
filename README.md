# Práctica Git: Creación y uso de ramas

Repositorio de práctica para fortalecer el flujo básico de trabajo con Git:
- Crear ramas (feature)
- Hacer commits
- Subir ramas al remoto (push)
- Fusionar cambios a `main` (merge)
- (Opcional) Provocar y resolver conflictos

## Datos del estudiante
- **Nombre:** Angel Xavier Delgado Jara
- **Repositorio:** git-ramas-delgado-xavier
- **Fecha:** 2026-01-17

## Estructura del proyecto

.
├── README.md
├── app.txt
└── web
└── login.html

## Archivos principales
- **app.txt**: checklist simple de funcionalidades (login, perfil, etc.).
- **web/login.html**: página HTML para evidenciar el desarrollo de la rama `feature/login-xdelgado`.

## Flujo de trabajo realizado

### 1) Rama principal (`main`)
1. Creación del repositorio remoto y clonación en local.
2. Creación de `README.md`, `app.txt` y carpeta `web/`.
3. Primer commit y push a `main`.

### 2) Rama `feature/login-xdelgado`
- Se marcó la funcionalidad **Login** como completada en `app.txt`.
- Se añadió/actualizó la página `web/login.html`.
- Commit y push de la rama.

### 3) Rama `feature/perfil-xdelgado`
- Se actualizó este `README.md` con la documentación del flujo.
- Commit y push de la rama.

### 4) Merge a `main`
- Se fusionaron las ramas:
  - `feature/login-xdelgado`
  - `feature/perfil-xdelgado`
- Se subieron los cambios finales al remoto.

## Cómo ver la página de Login
Abrir el archivo en el navegador:
- `web/login.html`

## Evidencias (comandos)
Para evidenciar ramas y merges se ejecutaron:

```bash
git branch -a
git log --oneline --graph --decorate --all
