# Sistema de cadastro de pessoas física e jurídica
Repositório criado com o objetivo de implementar melhorias no código do sistema de cadastro.
## Descrição
Nosso sistema de cadastro de pessoa é um projeto bem básico que tem como principal objetivo o cadastro de pessoas físicas e jurídicas, e a permanencia dos dados de cadastro dos clientes.

---
## Organizão do projeto
1. Tela de boas vindas: Essa tela foi estilizada a partir da tecnica conhecida como CSS de console;
2. Tela de principal de menus: Essa é a parte principal do projeto onde vai toda a lógica de cadastro, listagem, exclusão e permanêcia de dados. Dentro desta sessão se encontram as estruturas:
- Do While: Método que controla o acesso ao menu principal, é dentro desse loop que acontecem os cadastros, exclusões...
- Switch Case: Esta estrutura contém toda a lógica por trás de cada opção do menu.
+ Foreach: Estrutura condicinal muito importante e também muito presente no código. Uma espécie de loop condicional.
## Funcionalidades
+ Cadastro de Pessoas físicas e jurídicas;
+ Listagem de pessoas cadastradas;
+ Exclusão de pessoas cadastradas;
+ Armazenamento dos dados de cadastro.
---
## Tecnologias Utilizadas
Esse projeto foi criado utilizando as tecnologias:
- [C#](https://docs.microsoft.com/pt-br/dotnet/csharp/)
- [.NET](https://dotnet.microsoft.com/download)
### Editor
- [Visual Studio Code](https://code.visualstudio.com/)
### Extensões
- C#;
- C# Extensions;
- C# Snippets;
- C# XML Documentation.
---
### Pré-requisitos de instalação
- [x] Computador;
- [x] Mínimo 2 GB de memoria RAM;
- [x] Sistema operaçional Windows, Mac Os ou Linux;
---
## Como rodar o projeto
Clone o projeto com o comando abaixo:
```bash
# Clone o repositório
  >git clone https://github.com/FelipAra/encontroRemoto8.git
# Entre no diretório
  >cd Program.cs
# Execute o projeto
  >dotnet run
```  
---
## Erros Comuns
+ Omnisharp não funcionar: Para resolver é preciso que voçê siga os passos:
```bash
# Arquivo > Preferêcias > Configurações > Extensões > C# Configuration > Omnisharp: Use Global Mono
```
E mude de Always ou Never para Auto ou de Auto para Always ou Never e Novamente para Auto.

---
# Contribuidores
- [x] **FELIPE ARAUJO DEV**