# Investigación sobre Markdown

## ¿Qué es Markdown y por qué se utiliza en proyectos de software?

**Markdown** es un lenguaje de marcado ligero creado por John Gruber en 2004. Utiliza una sintaxis simple y fácil de leer que se convierte a HTML válido.

### Razones para usar Markdown en proyectos de software:

- **Documentación clara y mantenible**: Permite escribir documentación técnica sin distracciones de formato complejo
- **Control de versiones amigable**: Los archivos .md son de texto plano, perfectos para Git y GitHub
- **Multiplataforma**: Se visualiza igual en cualquier sistema operativo
- **Integración con herramientas de desarrollo**: Muchos IDEs y editores tienen soporte nativo
- **Colaboración simplificada**: Los equipos pueden colaborar fácilmente en documentación
- **Legibilidad**: El código fuente es fácil de entender incluso sin renderizar

## Ejemplo práctico de uso de Markdown

### Encabezados
# Título Principal (H1)
## Subtítulo (H2)
### Sección (H3)
#### Subsección (H4)

### Listas
Lista ordenada:
1. Primer elemento
2. Segundo elemento
3. Tercer elemento
Lista no ordenada:
- Elemento A
- Elemento B
  - Subelemento B1
  - Subelemento B2
### Tablas
| Nombre | Edad | Ciudad     |
|--------|------|------------|
| Juan   | 25   | Madrid     |
| María  | 30   | Barcelona  |
| Pedro  | 28   | Valencia   |

### Enlaces e Imágenes
**Enlace simple:**
[Texto del enlace](https://ejemplo.com)

**Imagen:**
![Texto alternativo](https://ejemplo.com/imagen.jpg)

**Enlace con referencia:**
[Mi documento][doc1]

[doc1]: https://enlace-al-documento.md

### Código
**Código en línea:**
Usa `console.log()` para imprimir mensajes.

**Bloque de código:**
```javascript
function saludar() {
    console.log("¡Hola Mundo!");
}
```
## Ventajas de utilizar Markdown en combinación con GitHub
1. README.md como carta de presentación
-Portada automática del repositorio
-Documentación visible inmediatamente al visitar el repo
-Instrucciones claras para colaboradores

2. GitHub Flavored Markdown
-Sintaxis extendida con características adicionales
-Tablas mejoradas con alineación
Task lists interactivas:
markdown
- [x] Tarea completada
- [ ] Tarea pendiente
- [ ] Otra tarea
3. GitHub Pages integrado
-Sitios web estáticos directamente desde archivos .md
-Hosting gratuito para documentación
-Temas predefinidos para personalización fácil

4. Colaboración eficiente
-Pull Requests con comentarios en formato Markdown
-Issues y Discussions con formato rico
-Wiki del proyecto basada en Markdown

5. Integración con flujos de trabajo
-GitHub Actions puede procesar archivos .md
-Automátización de generación de documentación
-Previsualización en tiempo real mientras editas
