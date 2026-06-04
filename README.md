# Guia de CodeAcademy Backend

Este es el motor de una pagina de cursos de programacion. Aqui explicamos como hacerlo funcionar de forma muy facil.

## Requisitos Necesarios
Para usar este proyecto, necesitas tener instalado:
1. Python (el lenguaje en el que esta escrito).
2. Docker (una herramienta que ayuda a que el programa funcione igual en cualquier computadora).

## Como hacerlo funcionar en tu propia computadora

Sigue estos pasos uno por uno:

1. **Bajar el codigo**:
   Copia y pega esto en tu terminal para traer el proyecto desde internet:
   ```bash
   git clone https://github.com/sergio001g/CodeAcademy-bakend.git
   ```
2. **Entrar a la carpeta**:
   ```bash
   cd CodeAcademy-bakend
   ```
3. **Encender todo**:
   Escribe este comando y espera a que termine. El hara todo el trabajo dificil por ti:
   ```bash
   docker-compose up -d --build
   ```
4. **Listo**:
   Ahora puedes entrar a la direccion `http://localhost/api/` en tu navegador para ver que funciona.

## Como usar la aplicacion

### Registrarse y Entrar
- Para crear una cuenta: Usa el comando de Registro.
- Para entrar: Usa el comando de Login y recibiras una "llave" (token) para poder comprar cursos.

### Cursos
- Puedes ver todos los cursos disponibles sin tener que entrar con una cuenta.
- Si quieres crear un curso nuevo, debes ser un Profesor.
- Si quieres comprar un curso, debes ser un Estudiante.

## Secciones de la aplicacion
- **Categorias**: Son los grupos de cursos (ejemplo: Web, Movil).
- **Cursos**: Son los titulos de los cursos y sus precios.
- **Lecciones**: Son las clases que hay dentro de cada curso.
- **Inscripciones**: Es la lista de quien ha comprado cada curso.

## Archivos Importantes
- **postman_collection.json**: Es un archivo que puedes meter en un programa llamado Postman para probar todos los botones de la aplicacion facilmente.
- **requirements.txt**: Es una lista de las piezas que Python necesita para que todo funcione.

-url : http://2.25.166.103/api/ o http://codeacademy-api.ddns.net/api/
