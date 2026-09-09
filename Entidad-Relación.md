```mermaid
  erDiagram
  PRODUCTO{
    string ID_Producto
    string Nombre
    double Precio

}
  USUARIO{
    string ID_Usuario
    string Nombre
    string Direccion
}
  PEDIDO{
  string ID_Pedido
  string ID_Usuario
  string ID_Direccion
}
USUARIO ||--o{ PEDIDO:Compra
PRODUCTO }|--|{ Pedido : Proceso
```
