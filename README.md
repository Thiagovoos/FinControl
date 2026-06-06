# FinanceFlow

Sistema de Controle Financeiro Pessoal desenvolvido com HTML, CSS e JavaScript puro, permitindo o gerenciamento de salário, despesas fixas e variáveis, acompanhamento de saldo disponível e visualização gráfica dos gastos.

---

## Sobre o Projeto

O FinanceFlow é uma aplicação web criada para auxiliar usuários no controle de suas finanças pessoais de forma simples, intuitiva e eficiente.

A aplicação permite registrar receitas e despesas, acompanhar o saldo disponível, visualizar a distribuição dos gastos por categoria e armazenar todas as informações localmente no navegador.

Não há necessidade de cadastro, login ou banco de dados.

---

## Funcionalidades

### Controle de Salário

* Definição do salário mensal.
* Atualização automática dos indicadores financeiros.
* Armazenamento automático dos dados.

### Cadastro de Despesas

* Registro de gastos fixos.
* Registro de gastos variáveis.
* Definição de categoria.
* Seleção de data.
* Exclusão de despesas cadastradas.

### Resumo Financeiro

Exibição automática de:

* Salário total.
* Total gasto.
* Saldo disponível.
* Percentual comprometido da renda.

### Gráfico de Gastos

Visualização da distribuição dos gastos por categoria através de gráfico circular (Doughnut Chart) desenvolvido utilizando Canvas API.

### Categorias Disponíveis

* Moradia
* Alimentação
* Transporte
* Saúde
* Lazer
* Educação
* Vestuário
* Outros

### Personalização

Sistema de troca de temas com as seguintes opções:

* Verde Sálvia
* Azul Oceano
* Terracota
* Lavanda
* Dourado

### Armazenamento Local

Todos os dados são armazenados utilizando Local Storage, permitindo que as informações permaneçam salvas mesmo após fechar ou atualizar o navegador.

### Sistema de Notificações

Mensagens automáticas para:

* Confirmação de ações.
* Avisos de preenchimento incorreto.
* Erros de validação.

---

## Tecnologias Utilizadas

### Front-end

* HTML5
* CSS3
* JavaScript

### APIs Utilizadas

* Local Storage API
* Canvas API

### Fontes

* Syne
* DM Sans

---

## Estrutura do Projeto

```text
FinanceFlow/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## Layout Responsivo

O sistema foi desenvolvido utilizando CSS Grid, Flexbox e Media Queries para garantir compatibilidade com diferentes dispositivos.

Compatível com:

* Computadores
* Notebooks
* Tablets
* Smartphones

---

## Funcionamento dos Cálculos

### Saldo Disponível

```text
Saldo = Salário - Total de Gastos
```

### Percentual de Gastos

```text
Percentual = (Total de Gastos / Salário) × 100
```

### Indicadores Visuais

| Faixa de Gasto | Cor      |
| -------------- | -------- |
| 0% até 49%     | Verde    |
| 50% até 79%    | Amarelo  |
| 80% ou mais    | Vermelho |

---

## Armazenamento de Dados

As informações são armazenadas exclusivamente no navegador do usuário através do Local Storage.

Nenhum dado é enviado para servidores externos ou serviços de terceiros.

Exemplo de chave utilizada:

```javascript
financeflow_state
```

---

## Recursos da Interface

* Design moderno e minimalista.
* Sistema de temas.
* Cartões informativos.
* Gráfico de distribuição financeira.
* Tabelas organizadas.
* Feedback visual através de notificações.
* Animações suaves.
* Interface responsiva.

---

## Como Executar o Projeto

### Método 1

Abra o arquivo:

```text
index.html
```

diretamente em qualquer navegador moderno.

### Método 2

Utilize a extensão Live Server no Visual Studio Code:

1. Instale a extensão Live Server.
2. Abra a pasta do projeto.
3. Clique com o botão direito em `index.html`.
4. Selecione **Open with Live Server**.

---

## Melhorias Futuras

* Exportação para PDF.
* Exportação para Excel.
* Relatórios mensais.
* Comparação de períodos.
* Metas financeiras.
* Dashboard avançado.
* Sistema de login.
* Integração com banco de dados.
* Backup em nuvem.

---

## Objetivo do Projeto

Este projeto foi desenvolvido com foco em aprendizado e prática dos seguintes conceitos:

* Estruturação de páginas com HTML.
* Estilização avançada com CSS.
* Manipulação do DOM com JavaScript.
* Persistência de dados com Local Storage.
* Criação de gráficos utilizando Canvas API.
* Desenvolvimento de interfaces responsivas.

---

## Autor

Desenvolvido por Japa para fins de estudo, prática e aprimoramento de conhecimentos em desenvolvimento web.

---

## Licença

Este projeto é disponibilizado para fins educacionais e de aprendizado. Seu uso pode ser livremente adaptado para estudos e projetos pessoais.
