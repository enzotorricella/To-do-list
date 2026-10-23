# Listas de tareas — JavaScript

Aplicación frontend de demostración para organizar tareas en múltiples listas. Implementada con **HTML, JavaScript, Bootstrap 4 y localStorage**, sin servidor ni cuenta de usuario.

## Funciones

- Crear listas con nombres únicos.
- Seleccionar una lista y agregar tareas.
- Marcar o desmarcar tareas como completadas **sin eliminarlas**.
- Eliminar tareas individualmente y eliminar listas completas.
- Conservar cambios en el almacenamiento local del navegador.
- Mostrar los textos ingresados como texto, sin interpretarlos como HTML.

## Ejecutar

No hace falta instalar dependencias. Abrí `index.html` en el navegador o serví los archivos con:

```bash
python -m http.server 8000
```

Después abrí `http://localhost:8000`.

## Pruebas manuales recomendadas

1. Crear dos listas y agregar tareas en ambas.
2. Marcar y desmarcar una tarea; verificar que no desaparezca.
3. Eliminar una tarea sin afectar las restantes.
4. Recargar la página y verificar la persistencia de las listas.
5. Intentar crear una lista duplicada.
6. Ingresar texto como `<script>alert(1)</script>` y verificar que se muestre literalmente.

## Limitaciones

- Los datos permanecen únicamente en el navegador y origen usados; no existe sincronización entre dispositivos.
- Borrar los datos del sitio puede eliminar las listas.
- No tiene usuarios, autenticación ni backend.
- Es un ejercicio frontend, no una aplicación de gestión multiusuario.

## Portfolio

Este repositorio demuestra manipulación del DOM, eventos, estado local, persistencia y tratamiento seguro de entradas. Para proyectos de software empresarial: [etorri.com.ar](https://etorri.com.ar/).
