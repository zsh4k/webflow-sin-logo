# webflow-sin-logo

Este codigo se creó especificamente para ocultar el logo de webflow mediante css

Solo copia el siguiente codigo y pegalo al inicio(justo despues de iniciar la etiqueta body) en tu sitio web Webflow 

```html
    <style>
        /*Quitar logo WebFlow*/
        .w-webflow-badge{
            display: none!important;
        }
    </style>
```