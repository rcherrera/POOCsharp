```mermaid
classDiagram
    direction LR

    class IImprimible {
      <<interface>>
      +Imprimir() void
    }

    class IConImpuesto {
      <<interface>>
      +CalcularImpuesto(baseGravable: decimal) decimal
    }

    class ClienteBase {
      <<abstract>>
      +Nombre: string
      +CalcularDescuento(subtotal: decimal) decimal*
      +Imprimir() void
    }

    class ClienteRegular {
      +CalcularDescuento(subtotal: decimal) decimal
    }

    class ClienteCorporativo {
      +CalcularDescuento(subtotal: decimal) decimal
    }

    class ClienteVIP {
      +CalcularDescuento(subtotal: decimal) decimal
    }

    class Vendedor {
      +Id: int
      +Nombre: string
      +Zona: string
      +Imprimir() void
    }

    class Producto {
      +Nombre: string
      +Descripcion: string
      +Precio: decimal
      +Categoria: CategoriaProducto
      +CalcularPrecio() decimal
      +Imprimir() void
    }

    class Electronico {
      +GarantiaMeses: int
      +CalcularPrecio() decimal
      +CalcularImpuesto(baseGravable: decimal) decimal
      +Imprimir() void
    }

    class ServicioInstalacion {
      +Horas: int
      +TarifaHora: decimal
      +CalcularPrecio() decimal
      +CalcularImpuesto(baseGravable: decimal) decimal
      +Imprimir() void
    }

    class Venta {
      +IdVenta: int
      +Fecha: DateTime
      +Subtotal: decimal
      +Impuestos: decimal
      +Descuento: decimal
      +Total: decimal
      +AgregarProducto(p: Producto) void
      +RecalcularTotales() void
      +Imprimir() void
      -_productosVendidos: List<Producto>
      +ProductosVendidos: IReadOnlyList<Producto>
    }

    %% Herencia
    ClienteRegular --|> ClienteBase
    ClienteCorporativo --|> ClienteBase
    ClienteVIP --|> ClienteBase

    Electronico --|> Producto
    ServicioInstalacion --|> Producto

    %% Interfaces
    ClienteBase ..|> IImprimible
    Vendedor ..|> IImprimible
    Producto ..|> IImprimible
    Electronico ..|> IConImpuesto
    ServicioInstalacion ..|> IConImpuesto

    %% Asociaciones / Composición
    Venta o-- "1" ClienteBase : cliente
    Venta o-- "1" Vendedor : vendedor
    Venta *-- "0..*" Producto : productos

