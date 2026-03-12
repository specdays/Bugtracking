# 📋 Plano de Teste - Swag Labs

![SwagLabs](image.png)

Este documento apresenta o **Plano de Teste utilizado nas práticas de Bug Tracking**, realizadas durante o curso da plataforma **Qualiters Club**.

O objetivo deste plano é definir a **estratégia de testes**, escopo, critérios de aceite e organização da suíte de testes aplicada à aplicação **Swag Labs**.

---

# 📊 Ferramenta utilizada

O plano de teste foi desenvolvido utilizando **Google Planilhas**, permitindo organizar de forma estruturada:

- Casos de teste
- Critérios de aceite
- Prioridade e severidade
- Resultados obtidos
- Registro de defeitos
- Indicadores de status

---

# 📖 Introdução do Plano

A introdução do plano de testes apresenta o contexto geral do projeto, incluindo objetivos, escopo inicial e organização da execução dos testes.

![Introdução](image-2.png)

![Introdução](image-3.png)

---

# 📌 Escopo dos Testes

Na aba **Escopo** da planilha são apresentados:

- Levantamento de requisitos
- Critérios de aceite
- Tipos de testes executados
- Classificação de prioridade
- Classificação de severidade
- Meta de execução dos testes
- Progresso da execução

![Escopo](image-5.png)

---

# 🧪 Estrutura da Suíte de Testes

A planilha contém diferentes abas organizadas por **funcionalidade do sistema**, permitindo melhor controle e rastreabilidade dos testes.

Cada linha representa um **Caso de Teste (CT)**.

---

# 🧾 Campos da Suíte de Testes

## ID

Cada ID representa um **Caso de Teste (CT)**, identificando de forma única cada cenário de validação.

---

## Critérios de Aceite

Os critérios de aceite são descritos utilizando **linguagem Gherkin**, permitindo descrever de forma clara o comportamento esperado do sistema.

---

## Prioridade

A prioridade define **a ordem de correção de um defeito**, considerando impacto no negócio e urgência da resolução.

---

## Severidade

A severidade representa **o impacto do defeito no funcionamento do sistema**, avaliando o nível de comprometimento da funcionalidade.

---

## Resultado Esperado

Descrição do comportamento esperado do sistema ao executar o caso de teste.

---

## Resultado Obtido

Indica o resultado real da execução do teste:

- **OK** - teste executado com sucesso
- **NOK** - falha identificada durante a execução

---

## Registro de Defeito

Quando um defeito é identificado, ele é registrado em uma planilha de **Controle de Bugs**, contendo:

- ID do bug
- Descrição
- Evidência
- Story relacionada

Cada bug recebe um **ID sequencial**, iniciando em `BUG-001`.

---

## Indicador de Status

Campo visual utilizado para indicar o status do teste executado.

Exemplo:

- 🟢 Passou
- 🔴 Falhou

---

# 📚 Suítes de Teste

As suítes de teste foram organizadas por funcionalidade da aplicação.

---

# 🔐 Suite - Login

A aba **suite_login** tem como objetivo validar a funcionalidade de **login na aplicação**.

Os testes verificam:

- autenticação com credenciais válidas
- comportamento com credenciais inválidas
- acesso ao sistema após login

![Suite Login](image-6.png)

---

# 📂 Suite - Menu

A aba **suite_validar_menu** valida a funcionalidade do **menu da aplicação**, garantindo que os elementos estejam acessíveis e funcionando corretamente.

![Suite Menu](image-7.png)

---

# ➕ Suite- Adicionar Itens

A aba **suite_adicionar_itens** valida a funcionalidade de **adicionar produtos ao carrinho**.

Os testes verificam:

- adição correta de itens
- atualização do carrinho
- comportamento da interface após a ação

![Adicionar Itens](image-8.png)

---

# ➖ Suite - Remover Itens

A aba **suite_remover_itens** valida a funcionalidade de **remoção de produtos do carrinho**.

![Remover Itens](image-9.png)

---

# 🔎 Suite - Filtrar Itens

A aba **suite_filtrar_itens** valida a funcionalidade de **filtro de produtos**, garantindo que os resultados apresentados estejam de acordo com os critérios selecionados.

![Filtrar Itens](image-10.png)

---

# 🎯 Objetivo da Suíte de Testes

A suíte de testes foi criada para garantir:

- validação das principais funcionalidades da aplicação
- rastreabilidade entre casos de teste e defeitos
- organização da execução dos testes
- registro estruturado de evidências

---

💡 Este plano de teste foi desenvolvido com fins educacionais para prática de **planejamento e execução de testes de software**.