# 💼 POO aplicado al Sistema de Ventas

Este material resume los 4 pilares de la Programación Orientada a Objetos (POO) usando ejemplos de un sistema de ventas.

---

## 👨‍👩‍👦 Herencia
- Clase base **Persona**: Nombre, Email, Teléfono.  
- **Vendedor** hereda de Persona: Id, Zona, Activo.  
- **Cliente** hereda de Persona: Dirección, TipoCliente.  
- **Venta** relaciona Vendedor + Cliente + Productos.

---

## 🔐 Encapsulamiento
- Campos privados + **propiedades con `private set`**.  
- Validaciones en **constructor** y **setters**.  
- Colecciones expuestas como `IReadOnlyList`.  
- Métodos controlan cambios de estado (`DescontarStock`).

---

## 🧩 Abstracción
- Clase abstracta **MedioPago** define el contrato (`Pagar`).  
- **PagoTarjeta** y **PagoEfectivo** implementan los detalles.  
- Interface **ICalculaImpuesto** permite estrategias (IVA, Exento).  
- **ServicioCheckout** depende de contratos, no implementaciones.

---

## 🎭 Polimorfismo
- Una misma llamada se comporta distinto según el objeto real.  
- Ejemplo: `List<MedioPago>` con **PagoTarjeta, PagoEfectivo, PagoTransferencia**.  
- **Checkout** procesa con distintas estrategias de impuestos.  
- Extensible: agregar **PagoCrypto** sin tocar el cliente.

---

## ✨ Resumen Final
- **Herencia** → Reutilizamos código.  
- **Encapsulamiento** → Protegemos estado.  
- **Abstracción** → Definimos contratos.  
- **Polimorfismo** → Múltiples comportamientos.  

👉 Así modelamos sistemas **flexibles, claros y mantenibles**.
