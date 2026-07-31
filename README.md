# testpuml
```plantuml
@startuml

class Usuario {
  - String nombre
  - String email
  + registrarse()
}

class Pedido {
  - String id
  + calcularTotal()
}

Usuario "1" -- "0..*" Pedido

@enduml
```
![Diagrama de Clases](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/marvinbarrera2024/testpuml/refs/heads/main/test.puml)
