# PMA_B4

## Descripción

PMA_B4 es un proyecto de ejemplo para centralizar y administrar la información operativa del negocio: permite registrar, consultar y actualizar los datos principales (usuarios, budgetary, reportes y configuración) desde un único lugar, con una interfaz web sencilla y accesible.

## Cómo usarlo

### Requisitos

- Git instalado
- Node.js 18 o superior
- npm

### Instalación

```bash
git clone https://github.com/ssantos-2025020/PMA_B4.git
cd PMA_B4
npm install
```

### Configuración

Crea un archivo `.env` en la raíz del proyecto con las variables necesarias:

```bash
PORT=3000
DATABASE_URL=postgresql://usuario:password@localhost:5432/pma_b4
SECRET_KEY=cambia-esta-clave
```

### Ejecución

```bash
npm start
```

La aplicación quedará disponible en `http://localhost:3000`.

### Ejemplo

```bash
curl http://localhost:3000/api/health
```

Respuesta esperada:

```json
{ "status": "ok" }
```

## Estructura

```
PMA_B4/
├── src/        # Código fuente
├── public/     # Archivos estáticos
├── tests/      # Pruebas
└── README.md
```

## Licencia

MIT
