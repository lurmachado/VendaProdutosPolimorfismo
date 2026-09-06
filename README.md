# Sistema de Venda de Produtos - Polimorfismo

Este é um projeto desenvolvido em **C#** (Console Application) com o objetivo de demonstrar os conceitos de **Programação Orientada a Objetos (POO)**, especificamente **Herança**, **Polimorfismo** e **Encapsulamento**.

## 💻 Sobre o Projeto

O sistema simula o cadastro e a geração de etiquetas de preço para diferentes tipos de produtos em uma loja. Os produtos podem ser de três tipos:
- **Comum:** Produto padrão com nome e preço.
- **Usado:** Produto que possui uma data de fabricação. Na etiqueta, é exibida a data de fabricação e a indicação de que é usado.
- **Importado:** Produto que possui uma taxa de alfândega. Na etiqueta, o preço final (preço + taxa) é exibido juntamente com o valor da taxa de alfândega.

O programa solicita ao usuário a quantidade de produtos a serem cadastrados, lê os dados de cada um (instanciando a classe correspondente) e, ao final, utiliza o **polimorfismo** para imprimir a etiqueta de preço (`PriceTag()`) de todos os produtos de forma simples.

## 🛠️ Tecnologias e Conceitos Utilizados

- **C# / .NET**
- **Programação Orientada a Objetos (POO):**
  - **Classes e Objetos**
  - **Herança:** Classes `UsedProduct` e `ImportedProduct` herdam da classe base `Product`.
  - **Polimorfismo:** Sobrescrita do método `PriceTag()` (com `virtual` e `override`) para comportamentos específicos em cada tipo de produto.
  - **Encapsulamento**
- Listas (`List<T>`)

## 🚀 Como Executar

1. Certifique-se de ter o [.NET SDK](https://dotnet.microsoft.com/download) instalado em sua máquina.
2. Clone este repositório:
   ```bash
   git clone https://github.com/lurmachado/VendaProdutosPolimorfismo.git
