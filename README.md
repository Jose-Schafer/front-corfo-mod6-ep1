# How to start
Install packages
```sh
nvm use 23
npm install
```

Start dev server
```sh
npm run dev
```

open `http://localhost:5173`

# Preguntas
## 1. Consumo de APIs usando Fetch API o Axios (2 puntos)
El callback `get`es definido en `src/api/requests.js` y es usado en varias partes del código para consumir la API

## 2. Integración de TypeScript en Componentes Clave (2 puntos)
Ver `src/components/doctor-card` para el uso de interfaces y la clase de doctor

## 3. Mejoras en la Seguridad del Front-End (2 puntos)
Para XSS ver configuración en `vite.config.ts`. 
Ver `src/mocks/login.js` para la simulación de una api que retorna un JWT. Ver `src/providers/authContext.tsx` para ver como se parsea el JWT para obtener el rol del usuario. Ver `src/config/protected-route.tsx` para ver como se usa el rol para acceder a una ruta.

## 4. Optimización con Hooks y Manejo de Errores (1 punto)
Multiples componentes implementan el useEffect
