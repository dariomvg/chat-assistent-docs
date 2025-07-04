# Chat assistent
## Chat asistente y guía para tus aplicaciones

Puede ser: 
- Guía de tu aplicación 
- Preguntas frecuentes
- Funcionalidad o fín de la misma
- etc...


### Pasos

1. Instalación

```js
npm i kit-components-ui
```

2. Configuración

```jsx

import { ChatAssistent } from "kit-components-ui"

export default function App() {

    const options = [
        {
            id: 0,
            option: "",
            content: "",
            path: ""
        },...
    ]

    return (
        <ChatAssistent options={options} messageMain="" theme="dark" width="400px" height="400px" />
    )
}

```
3. Objeto *options*

```js
[
    {
        id: 0, // identificador único
        option: "", // Pregunta partícular sobre tu aplicación
        content: "", // Una descripción, detalle o respuesta a la pregunta seleccionada
        path: "" // La ruta para redirrecionar al usuario a una sección específica de tu aplicación. Esta opción es opcional
     }
]
```
