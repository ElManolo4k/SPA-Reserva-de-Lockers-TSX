----------------------------------------------------------------------------------------------------------------------
Instalacion y ejecucion del proyecto
----------------------------------------------------------------------------------------------------------------------
1) Instalar dependencias
    npm install
2) Correr Proyecto
    npm run dev
----------------------------------------------------------------------------------------------------------------------
Contexto del Proyecto
----------------------------------------------------------------------------------------------------------------------
Es una SPA en React+TS para gestionar reserva de lockers con 5 vistas: dashboard (KPIs + próximas reservas), reservar (formularios + validación de solapamientos), mis reservas (listar/cancelar), lockers (CRUD con sede/edificio/piso) y config (exportar/importar JSON + reset). Los datos se guardan en localStorage, y valida horarios, disponibilidad y conflictos antes de crear una reserva.
----------------------------------------------------------------------------------------------------------------------