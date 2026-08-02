# Servidor Estático vs Contenedor Dinámico

## Servidor estático (puerto 3000)
Sirve un archivo HTML que ya existe en disco (`public/index.html`).
El contenido no depende de quién pregunta ni de cuándo pregunta.

## Servidor dinámico (puerto 3001)
Genera el HTML en el momento de la petición, usando:
- La hora actual del servidor.
- El nombre recibido por query string (`?nombre=...`).

## Regla práctica para distinguirlos
Si dos usuarios distintos (o el mismo usuario en momentos distintos)
piden lo mismo y reciben una respuesta idéntica → es estático.
Si la respuesta puede variar según quién pregunta o cuándo → es dinámico.

## Clasificación de situaciones reales

Usando la regla práctica: ¿la respuesta cambia si la piden dos personas
distintas, o la misma persona en dos momentos distintos?

| Situación | ¿Cambia según usuario/hora? | Clasificación |
|---|---|---|
| Página de "Términos y condiciones" de una empresa | No | Estática |
| Muro de noticias de una red social | Sí | Dinámica |
| Catálogo con precios y stock en tiempo real | Sí | Dinámica |
| Imagen de logo de una empresa | No | Estática |
| Panel de "quién está conectado ahora" | Sí | Dinámica |
