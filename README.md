# Servidor HTTP Simples em C#

Este projeto consiste em um servidor HTTP simples desenvolvido em C# que permite hospedar e servir páginas estáticas e dinâmicas. Ele é capaz de processar requisições GET e POST e pode servir conteúdos estáticos como HTML, CSS, JavaScript e imagens, além de suportar a execução de páginas dinâmicas.

## Funcionalidades Principais

- **Serviço de Páginas Estáticas:** O servidor pode fornecer arquivos estáticos, como HTML, CSS, JavaScript, imagens etc.
- **Páginas Dinâmicas:** Permite a execução de páginas dinâmicas, como aquelas que processam requisições POST.
- **Tratamento de Requisições GET e POST:** Processa tanto requisições GET quanto POST para servir conteúdos dinâmicos.
- **Exemplo de Uso de Classes e Herança:** Utiliza classes e herança para criar páginas dinâmicas e estáticas.

## Componentes Principais

1. **Servidor HTTP (`ServidorHttp.cs`):** Este arquivo contém a lógica principal do servidor HTTP. Ele trata requisições, serve conteúdos estáticos e dinâmicos e gerencia a comunicação com os clientes.
2. **Páginas Dinâmicas (`PaginaCadastroProduto.cs`, `PaginaProdutos.cs`):** São exemplos de páginas dinâmicas que podem ser executadas pelo servidor. Elas processam requisições POST e GET, respectivamente, para realizar operações como cadastrar produtos e exibir uma lista de produtos.
3. **Modelo de Dados (`Produto.cs`):** Define a estrutura de dados de um produto e armazena uma lista de produtos como exemplo inicial.

## Como Usar

1. **Execução do Servidor:** O servidor pode ser iniciado executando o arquivo `Program.cs` que instancia a classe `ServidorHttp`.
2. **Adição de Novas Páginas Dinâmicas:** Para criar novas páginas dinâmicas, crie uma classe que herde da classe `PaginaDinamica` e implemente os métodos `Get` ou `Post` conforme a necessidade.
3. **Atualização das Páginas Estáticas:** As páginas estáticas podem ser adicionadas ou atualizadas no diretório correspondente dentro da estrutura de diretórios do servidor. Certifique-se de atualizar os caminhos corretamente.

## Requisitos

Para executar este servidor, é necessário ter o ambiente do .NET Framework configurado na sua máquina. Certifique-se de ter o SDK do .NET instalado para compilar e executar o código.

## Observações

Este servidor é um exemplo simples e pode não ser adequado para ambientes de produção. Não foi projetado para lidar com cargas de tráfego pesadas e pode não incluir todos os recursos de segurança necessários para aplicações web robustas. Este projeto serve principalmente como uma introdução ao desenvolvimento de servidores HTTP em C# e como um ponto de partida para implementações mais complexas e seguras.

Sinta-se à vontade para contribuir, fazer melhorias ou adaptar este código de acordo com suas necessidades!
