# 🔄 Atualização de Preços com Java (Consumer & Method Reference)

Este é um pequeno projeto Java que demonstra o uso da interface funcional `Consumer` e referências de métodos para aplicar 
um aumento percentual nos preços de uma lista de produtos.
## 🧠 Objetivo

- Aplicar um aumento de 10% nos preços de produtos usando:
  - Referência de método estático
  - Interface funcional `Consumer`
- Praticar conceitos de programação funcional introduzidos no Java 22.0.2.

- ## 📦 Estrutura do Projeto
- src/
├── app/
│ └── Program.java // Classe principal
├── entities/
│ └── Product.java // Classe do produto
└── util/
└── PriceUpdate.java // Implementa Consumer<Product>

## ▶️ Como funciona

1. Uma lista de produtos é criada no `Program.java`.
2. Um método estático (`Product::staticPriceUpdate`) é usado como referência funcional para aumentar o preço em 10%.
3. Os produtos atualizados são exibidos no console.

   
### 💡 Exemplo de Saída

Tv, 990.00
Mouse, 55.00
Tablet, 385.55
HD Case, 89.00


## 📚 Conceitos Utilizados

- Programação funcional com Java
- Interface `Consumer<T>`
- Referência de métodos (`ClassName::methodName`)
- `forEach` para percorrer listas

## 🛠️ Requisitos

- JDK 8 ou superior
- IDE como Eclipse, IntelliJ ou uso de terminal/linha de comando

## 🚀 Como executar

Compile e execute a classe `Program`:

```bash
javac app/Program.java
java app.Program

Ou execute via sua IDE favorita.





