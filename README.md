# CIP-CMED

## Sistema de Controle, Inventário e Patrimônio — Centro Médico da PMESP

O **CIP-CMED** é um sistema desenvolvido para auxiliar no **controle patrimonial, inventário, auditoria e gestão logística de materiais** do Centro Médico da Polícia Militar do Estado de São Paulo (CMED).

A aplicação foi desenvolvida com o objetivo de centralizar as informações relacionadas aos materiais patrimoniados, permitindo maior organização, rastreabilidade e controle das movimentações realizadas pelas diferentes divisões e pelos respectivos detentores.

O sistema busca substituir processos excessivamente manuais por um ambiente centralizado, facilitando a consulta das informações, a realização de inventários e o acompanhamento da situação dos materiais.

## Objetivos

O CIP-CMED tem como principais objetivos:

* Centralizar as informações dos materiais patrimoniados;
* Facilitar a realização e o acompanhamento de inventários;
* Permitir o controle dos materiais por divisão e detentor;
* Registrar e acompanhar movimentações patrimoniais;
* Auxiliar nos processos de conferência e auditoria;
* Reduzir inconsistências e retrabalho nos controles administrativos;
* Facilitar a consulta das informações patrimoniais pelas equipes autorizadas;
* Proporcionar maior organização ao gerenciamento logístico do CMED.

## Principais funcionalidades

### Controle Patrimonial

Permite o cadastro, consulta e acompanhamento dos materiais e bens patrimoniados, mantendo suas informações organizadas em uma base centralizada.

### Inventário

Possibilita a realização de conferências dos materiais, permitindo comparar as informações registradas no sistema com a situação encontrada durante os processos de inventário.

### Divisões e Detentores

O sistema permite organizar os materiais de acordo com suas respectivas divisões e detentores, facilitando a identificação de onde os bens estão vinculados e quem é responsável por sua guarda.

### Movimentações

Permite acompanhar movimentações relacionadas aos materiais, contribuindo para a rastreabilidade do patrimônio dentro da estrutura administrativa.

### Auditoria e Controle

O sistema foi desenvolvido para auxiliar os processos de auditoria e conferência patrimonial, proporcionando uma visão centralizada das informações necessárias para análise e fiscalização dos registros.

### Acesso dos Usuários

As diferentes divisões e seus respectivos usuários poderão acessar o sistema de acordo com as permissões definidas para cada perfil.

## Tecnologias utilizadas

* **Frontend:** React
* **Estilização:** Tailwind CSS
* **Backend e Banco de Dados:** Supabase
* **Hospedagem e Deploy:** Vercel
* **Automação e ferramentas auxiliares:** Java e Playwright
* **Ambiente de desenvolvimento:** Visual Studio Code
* **Controle de versão:** Git / GitHub

## Arquitetura

O CIP-CMED utiliza uma arquitetura baseada em uma aplicação web desenvolvida com React, integrada ao Supabase para gerenciamento de dados e serviços de backend.

A aplicação é disponibilizada através da Vercel, permitindo o acesso ao sistema por meio de navegador.

De forma simplificada:

**Usuário → Aplicação React → Supabase → Banco de Dados**

Ferramentas desenvolvidas em Java e Playwright também podem ser utilizadas como apoio em processos de inspeção, automação e auditoria do sistema.

## Controle e segurança

O sistema possui mecanismos de autenticação e controle de acesso destinados a restringir a utilização às pessoas autorizadas.

As informações relacionadas ao patrimônio e aos inventários devem ser acessadas somente por usuários devidamente autorizados, respeitando as permissões estabelecidas para cada perfil.

> **Importante:** informações de acesso, chaves de API, credenciais do Supabase e outras variáveis sensíveis não devem ser armazenadas diretamente no código-fonte ou no repositório.

## Execução em ambiente de desenvolvimento

Para executar o projeto localmente:

### 1. Clonar o repositório

```bash
git clone [URL_DO_REPOSITORIO]
```

### 2. Acessar o diretório

```bash
cd [DIRETORIO_DO_PROJETO]
```

### 3. Instalar as dependências

```bash
npm install
```

### 4. Configurar as variáveis de ambiente

Criar o arquivo de variáveis de ambiente utilizado pelo projeto e configurar as credenciais necessárias para conexão com o Supabase.

As credenciais reais não devem ser incluídas no repositório.

### 5. Iniciar o ambiente de desenvolvimento

```bash
npm run dev
```

Após a inicialização, acessar o endereço local informado pelo Vite/servidor de desenvolvimento.

## Organização do projeto

A estrutura interna do projeto pode variar conforme a versão atual da aplicação. De forma geral, o sistema é dividido entre:

* Interface e componentes do frontend;
* Regras e funcionalidades da aplicação;
* Integração com o Supabase;
* Autenticação e controle de usuários;
* Rotinas relacionadas ao patrimônio e inventário;
* Ferramentas e scripts auxiliares de automação e auditoria.

## Público de utilização

O CIP-CMED é destinado à utilização interna pelas equipes autorizadas envolvidas nas atividades de:

* Patrimônio;
* Logística;
* Inventário;
* Administração;
* Divisões do CMED;
* Detentores de materiais.

## Status do projeto

**Em desenvolvimento / utilização interna.**

O sistema encontra-se em evolução contínua, recebendo melhorias, correções e novas funcionalidades de acordo com as necessidades identificadas nos processos de controle patrimonial, inventário, auditoria e logística.

## Observação

O CIP-CMED é uma aplicação desenvolvida para apoiar os processos administrativos e patrimoniais do Centro Médico da Polícia Militar do Estado de São Paulo, não substituindo as normas, procedimentos e responsabilidades administrativas estabelecidas pela instituição.
