# 📦 Sistema de Controle de Estoque e Pedidos

Disciplina: Programação para Dispositivos Móveis

Curso: Sistemas de Informação

Instituição: Instituto Federal Goiano - Câmpus Urutaí

---
## 📝 Resumo
Aplicativo mobile para gerenciamento de estoque e acompanhamento de pedidos, desenvolvido com o objetivo de facilitar a organização e o controle de produtos em pequenos negócios.

O projeto faz parte da disciplina de Programação para Dispositivos Móveis, do curso de Bacharelado em Sistemas de Informação do IF Goiano – Campus Urutaí.

---

## 👥 Equipe
- Letícia Inácio Pereira Vaz
- Marcus Augusto Correa Bernardo
  
--- 

## 🎯 Objetivo
O objetivo do Sistema de Controle de Estoque para Pequenos Negócios é organizar, registrar e acompanhar as movimentações de produtos de uma empresa, permitindo um controle eficiente das entradas, saídas e quantidades disponíveis no estoque.

A proposta é oferecer uma solução simples e prática, facilitando o gerenciamento dos produtos e pedidos por meio de um aplicativo mobile integrado a uma API.

---

## 🏪 Público Alvo
O público-alvo são pequenos empreendedores e empresas de pequeno porte que precisam organizar e controlar seus produtos de maneira simples e eficiente.

Entre os principais usuários estão:

* Donos de pequenas lojas;
* Microempreendedores individuais (MEI);
* Comerciantes;
* Lojas de roupas;
* Mercearias;
* Pequenas empresas familiares;
* Lojas online.

---

## ⚙️ Requisitos

## Requisitos Funcionais

- **RF-01**: O aplicativo deve permitir o cadastro de novos clientes com validação de formato de campos obrigatórios como nome, e-mail, CPF/CNPJ e endereço antes da submissão.
- **RF-02**: O aplicativo deve exibir o catálogo de produtos com funcionalidade de busca por texto e filtragem por categorias em barra horizontal.
- **RF-03**: O aplicativo deve exibir os detalhes do produto, incluindo descrição, preço unitário, categoria, fornecedor e quantidade disponível em estoque.
- **RF-04**: O aplicativo deve permitir adicionar, alterar a quantidade e remover produtos do carrinho de compras local antes de prosseguir para a finalização.
- **RF-05**: O aplicativo deve validar a quantidade solicitada em relação ao estoque disponível na tela e desabilitar o incremento caso atinja o limite.
- **RF-06**: O aplicativo deve permitir a seleção do método de pagamento (PIX, Cartão de Crédito e Boleto) e submeter a criação do pedido para o backend.
- **RF-07**: O aplicativo deve apresentar uma tela de confirmação do pedido com o resumo dos itens, valor total calculated e código de acompanhamento.
- **RF-08**: O aplicativo deve listar o histórico de pedidos do cliente com o status atual (`PENDENTE`, `PAGO`, `CANCELADO`) e permitir a visualização detalhada.

---

## Requisitos Não Funcionais

- **RNF-01 — Feedback Visual**: Sempre que o aplicativo estiver buscando dados da internet, ele deve mostrar uma animação de carregamento (ex: *um círculo girando*) para que o usuário saiba que a aplicação está processando e não travou.
- **RNF-02 — Tratamento de Erros**: Exibir mensagens de erro claras e amigáveis. Caso ocorra uma falha (como tentar comprar um produto sem estoque), a aplicação não deve fechar inesperadamente nem exibir códigos internos. Deve-se exibir um aviso simples explicando o problema.
- **RNF-03 — Segurança**: Guardar logins e dados com segurança , o aplicativo deve salvar o acesso do usuário de forma protegida no celular. Com isso, a pessoa não precisa digitar e-mail e senha toda vez que abrir o app, mantendo os dados seguros.
- **RNF-04 — Usabilidade**: A interface deve apresentar visual organizado, navegação intuitiva, elementos interativos (botões) com área de toque adequada, tipografia legível e contraste de cores conforme diretrizes de acessibilidade.
- **RNF-05 — Desempenho**: A navegação e a renderização de listas (como catálogo de produtos e histórico de pedidos) devem ser otimizadas, garantindo rolagens *smooth* e sem quedas de taxa de quadros (*stuttering*).

---

## 📊 Diagramas
- **Arquitetura de Camadas**
  
<img width="1092" height="362" alt="Demonstra a organização do código Flutter, desacoplamento e gerenciamento de estado drawio" src="https://github.com/user-attachments/assets/dbec3405-3341-4908-9fc6-6f275b0740be" />

*Demonstra a organização do código Flutter, desacoplamento e gerenciamento de estado.*

---  

- **Fluxo de Navegação**
  
<img width="1016" height="762" alt="Define a experiência de usuário (UX) e o mapeamento de rotas do app móvel drawio" src="https://github.com/user-attachments/assets/c442d9bb-eb3e-49f2-b776-dba35d1d71a0" />

*Define a experiência de usuário (UX) e o mapeamento de rotas do app móvel.*

---
- **Diagrama de Sequência**
  
<img width="1282" height="863" alt="Valida a integração completa entre a interface móvel e a API REST Spring Boot" src="https://github.com/user-attachments/assets/d8283b77-c84b-4716-98cd-bcdcb2d5580c" />

*Valida a integração completa entre a interface móvel e a API REST Spring Boot.*

---

## Organização da Equipe para Desenvolvimento
O desenvolvimento será realizado de forma colaborativa, com a participação dos dois integrantes em todas as etapas do projeto.

As atividades serão compartilhadas, incluindo:

- Desenvolvimento das interfaces mobile;
- Implementação das funcionalidades;
- Integração do aplicativo com a API;
- Realização de testes;
- Correções e melhorias;
- Documentação do projeto.

A equipe utilizará o GitHub para versionamento do código e acompanhamento do desenvolvimento.
