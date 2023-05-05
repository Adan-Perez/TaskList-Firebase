## CRUD simple de Firebase con JavaScript

---

**Para poder ejecutar el proyecto es necesario tener una cuenta en Firebase, crear un proyecto y en este mismo, crear una aplicación (Cloud Firestore)**

### Crear un fichero de configuración de Firebase en la raíz del proyecto con el nombre de config.js con el siguiente contenido:

```javascript {.line-numbers}
export const firebaseConfig = {
  apiKey: 'TuApikey',
  authDomain: 'example.firebaseapp.com',
  projectId: 'example',
  storageBucket: 'example.appspot.com',
  messagingSenderId: '123456789',
  appId: '1:123456789:web:abcdef1234567890',
};
```

_Estos datos se pueden obtener en la consola de Firebase, en la sección de configuración del proyecto._