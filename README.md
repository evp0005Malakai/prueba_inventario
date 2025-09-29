# prueba_inventario
# 📦 Inventario de Farmacia (TypeScript)

Este repositorio contiene un sistema básico de inventario para una farmacia, desarrollado en **TypeScript**.

---

## 🚀 Requisitos previos
- [Node.js](https://nodejs.org/) instalado en tu ordenador.
- [Git](https://git-scm.com/) para clonar y gestionar el repositorio.

---

## 📂 Instalación del proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/evp0005Malakai/prueba_inventario.git
   cd prueba_inventario
2. Instala las dependencias necesarias:
    ```bash
    npm init -y
    npm install typescript ts-node @types/node --save-dev
3. Inicializa TypeScript:
   ```bash
   npx tsc --init

---
   
##▶️ Ejecución del programa
- Para ejecutar el archivo inventario.ts, usa el siguiente comando:
   ```bash
   npx ts-node inventario.ts

---

##📖 Funcionalidades principales
1. Mostrar inventario: Lista todos los medicamentos disponibles.
2. Agregar medicamento: Permite añadir un nuevo medicamento al inventario.
3. Vender medicamento: Reduce la cantidad de un medicamento en caso de venta.

---

##📜 Ejemplo de salida
- Al ejecutar el programa verás algo como:
  ```yaml
  📋 Inventario de la farmacia:
  Paracetamol: 50 unidades - 1.5€ c/u
  Ibuprofeno: 30 unidades - 2€ c/u
  Omeprazol: 20 unidades - 3€ c/u
  ✅ Amoxicilina agregado al inventario.
  💊 Venta realizada: 5 unidades de Paracetamol
  📋 Inventario de la farmacia:
  Paracetamol: 45 unidades - 1.5€ c/u
  Ibuprofeno: 30 unidades - 2€ c/u
  Omeprazol: 20 unidades - 3€ c/u
  Amoxicilina: 15 unidades - 4.5€ c/u
