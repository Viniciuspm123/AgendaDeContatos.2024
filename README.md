## Projeto - Agenda de Contatos (Console Java)

Este projeto implementa um **sistema básico de agenda de contatos** em Java, utilizando interação via **Console (Terminal)**. O aplicativo permite adicionar novos contatos e exibir a lista completa de contatos cadastrados.

### 🚀 Sobre o Projeto

O aplicativo é estruturado nas classes **(Contato)** e **(AgendaContatos)**. A classe `Contato` modela a informação de cada pessoa (nome, telefone, e-mail). A classe `AgendaContatos` contém o *loop* principal do menu, gerencia a lista de contatos através de um `ArrayList` e processa as requisições do usuário (adicionar e listar). O foco é demonstrar a **programação orientada a objetos (POO)**, a manipulação de coleções e a interação básica com o usuário via console.

### 🛠️ Tecnologias e Conceitos Abordados

**Estrutura de Classes (POO):**

* **Classe (Contato):** Implementa o objeto de dados (POJO) para o contato. Possui atributos privados (`nome`, `telefone`, `email`) e métodos públicos (`get`s) para **encapsulamento**.
* **Método `(toString)`:** Sobrescrito na classe (Contato) para fornecer uma representação textual completa e formatada do objeto quando ele é impresso no console.

**Coleções e Estruturas de Dados:**
Uso de `(ArrayList<Contato>)` para armazenar dinamicamente e gerenciar a lista de objetos `Contato` na memória durante a execução do programa.

**Interação via Console:**
Utilização da classe `(Scanner)` para ler a entrada de dados do usuário (opções do menu e informações de cadastro).

**Controle de Fluxo e Loop:**
Uso de um *loop* `(while (true))` para manter o menu principal do sistema ativo e rodando continuamente até que o usuário escolha a opção **Sair**.

**Lógica de Negócios:**

* **Adicionar Contato:** Solicita os três dados ao usuário, cria uma nova instância de (Contato) com esses dados e adiciona o objeto à `ArrayList`.
* **Listar Contatos:** Itera sobre a `ArrayList` e exibe o resultado do método `toString()` de cada objeto `Contato`.

### 💻 Como Executar

Clone este repositório.

Este projeto deve ser compilado e executado através de um ambiente de desenvolvimento Java (IDE), como Eclipse ou IntelliJ, ou via terminal, sendo totalmente interativo via **console**.
