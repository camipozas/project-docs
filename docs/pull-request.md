# Pull Request
> Lo que se presente a continuación va a depender de cada organización, esto es solo una de las prácticas.

## Quien sube el PR

Cuando realizamos un PR en GitHub es necesario que en este se incluya lo siguiente:

1. Al menos un revisor.
2. Asignación a uno mismo (opcional)
3. Label: A revisar.
4. Detalles de los cambios.

### Detalles del PR

Los cambios que podemos realizar generalmente son 4, los cuales se mencionan y se muestran sus respectivos templates a continuación:

1. **Feature:** Nuevas características o mejoras que tienen impacto en el usuario.

```textplain
## Feature description
De forma clara y concisa describe esta funcionalidad.

## Contexto
Explica por qué fue creada esta funcionalidad. Incluir a qué tarjeta hace alusión.

## Solución
Describe los cambios realizados en el código, con detalle de tal forma que quien revise entienda a cabalidad.

## Output screenshots
Adjunta screenshots de ser necesario y en caso de que aplique.

## Ejecución en local
Indica los pasos correspondientes junto con los comandos para poder realizar la ejecución en local.

## ¿Hay algún cambio de comportamiento existente de otras características debido a este cambio de código?
Menciona si o no. Si la respuesta fue si, explique los cambios.

## Otros
Indica si queda deuda técnica, otras consideraciones, etc. Si no aplica, borrar.
```

1. **Fix:** Correcciones a bugs.

```markdown
## Bug description
De forma clara y concisa explica el problema. Incluir a qué tarjeta hace alusión.

## Causa principal
Brevemente describe la causa principal del problema junto con el análsis de este.

## Solución
Describe los cambios en detalle para los revisores. Explica la solución técnica del problema y cómo esta la resuelve.

## Output screenshots
Adjunta screenshots de ser necesario y en caso de que aplique.

## Ejecución en local
Indica los pasos correspondientes junto con los comandos para poder realizar la ejecución en local.
```

1. **Docs:** Mejoras a la documentación.

```markdown
## Documentation description
Indica los cambios en la documentación del proyecto. 
Incluir a qué tarjeta hace alusión en caso de que aplique.
```

1. **Refactor:** Cambios internos en el código de una funcionalidad que no tienen impacto para el usuario.

```markdown
## Refactor description
De forma clara y concisa describe el refactor realizado. 
Incluir a qué tarjeta hace alusión en caso de que aplique.

## Resumen de cambios
Indica claramente los cambios realizados para los revisores.

## ¿Hay algún cambio de comportamiento existente de otras características debido a este cambio de código?
Menciona si o no. Si la respuesta fue si, explique los cambios.
```

> Cabe destacar que estos templates ayudan y facilitan la revisión.

> También, esto se puede dejar guardado en GitHub realizando los siguientes pasos: Settings → Saved replies → Add a saved reply. Después, para poder utilizarlo, en nuestro PR debemos hacer click en `Add saved reply` o último botón de la derecha, ahí están nuestros templates.
