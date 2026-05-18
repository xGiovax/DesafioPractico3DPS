# FinanzasApp

Aplicación móvil de finanzas personales desarrollada con React Native y Expo, con backend en Firebase. Permite llevar un registro completo de ingresos, gastos, 
cuentas múltiples y presupuestos mensuales.

---

## Tecnologías utilizadas

- React Native con Expo SDK 55
- Firebase Authentication
- Firebase Firestore
- React Navigation (Stack + Bottom Tabs)
- AsyncStorage (persistencia local)
- Expo Print / Sharing / FileSystem
- react-native-chart-kit (gráficas)

---

## Funcionalidades

### Core
-  Autenticación con email y contraseña (Login, Registro, Logout)
-  Gestión de cuentas múltiples con saldo dinámico
-  Registro de transacciones (ingresos y gastos) con filtros
- Presupuestos por categoría con alertas al 80% y 100%
- Dashboard con gráficas de barras, torta y desglose por categoría

### Extra
-  Exportación de reportes en PDF y CSV


---

## Requisitos previos

- Node.js instalado (versión 18 o superior)
- Expo Go instalado en tu celular o un emulador Android/iOS

---

## ⚙️ Instalación y configuración

### 1 — Clonar el repositorio

```bash
git clone https://github.com/xGiovax/DesafioPractico3DPS.git
cd FinanzasApp
```

### 2 — Instalar dependencias

```bash
npm install
```

### 3 — Ejecutar

```bash
npx expo start
```

