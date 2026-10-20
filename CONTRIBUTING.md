# Cómo contribuir

Gracias por querer colaborar en **BiblioApp**.

## Preparar el entorno

Sigue los pasos de instalación del [README](README.md#instalación).

## Ramas

- `main`: versión estable.
- `feature/nombre`: nuevas funcionalidades.
- `fix/nombre`: corrección de errores.

## Mensajes de commit

Usa el formato `tipo: descripción`, por ejemplo:

```text
feat: añadir búsqueda por ISBN
fix: corregir fecha de devolución
docs: actualizar README
```

## Estilo

- Código PHP según el estándar PSR-12.
- Los archivos Markdown deben pasar `npx markdownlint-cli2 "**/*.md"` sin avisos.

## Pull Requests

1. Crea una rama desde `main`.
2. Haz tus cambios y comprueba que todo funciona.
3. Abre una Pull Request explicando qué has cambiado y por qué.
