# Notas de aula da disciplina

# Governança de TI, Ética e Privacidade de Dados

## 1. O que é Governança de TI (COBIT e ITIL)?

A Governança de TI garante que a tecnologia apoie os objetivos da empresa com segurança e eficiência.

* **COBIT:** framework voltado para governança, controle e gestão de riscos.
* **ITIL:** conjunto de boas práticas para gerenciamento dos serviços de TI.

---

## 2. Princípios da LGPD para Desenvolvedores

Os principais princípios são:

* Finalidade (usar dados para um objetivo específico);
* Necessidade (coletar apenas o necessário);
* Segurança (proteger os dados);
* Transparência (informar como os dados serão usados);
* Prevenção (evitar incidentes).

---

## 3. O que é Privacidade por Design?

É desenvolver sistemas com a proteção de dados desde o início do projeto, utilizando práticas como criptografia, controle de acesso e coleta mínima de informações.

---

## 4. O que são Dados Sensíveis?

São dados que exigem maior proteção, como:

* Dados de saúde;
* Biometria;
* Religião;
* Opinião política;
* Origem racial ou étnica.

---

# Caso MedAgenda

### 1. Identificação

**Dados expostos:**

* Nome;
* CPF;
* Histórico clínico;
* Diagnósticos.

**Princípios violados:**

* Segurança;
* Prevenção;
* Necessidade;
* Privacidade por Design.

---

### 2. Mitigação Tecnológica

O problema poderia ser evitado com:

* Uso de ambientes separados (Docker);
* Banco exclusivo para testes;
* Anonimização ou mascaramento dos dados;
* Criptografia das informações.

---

### 3. Governança

A empresa deveria implementar:

* Controle de acesso por função (cada usuário acessa apenas o necessário);
* Autenticação em dois fatores;
* Registro de acessos (logs);
* Proibição de usar dados reais em ambientes de teste.

## Conclusão

A LGPD exige que empresas protejam os dados pessoais. Com boas práticas de governança, ambientes separados, controle de acesso e anonimização dos dados, seria possível evitar um incidente como o da MedAgenda.


## Aula 14

- Virtualização de Máquinas
- VENV ou PYENV (Virtual Enviroment)
- DOCKER

- # Aula 13

## Sistema Web e gerenciamento de usuário

- CRM
- CRUD

### Sistema gestão pizzaria
- gestão de usuários
- gestão de insumo
- gestão de fornecedor
- gestão cliente (**Importante!!!**)

---

# Aula 8

## Boas práticas de desenvolvimento de software em GRUPO e EQUIPE

### Sistema de Versionamento de código
- Git + GitHub
- controla versões
- controla backups
- controla equipes de desenvolvimento coletivo

### Sistema Kanban
METODOLOGIA DE GERENCIAMENTO DE TAREFAS/ATIVIDADES: TRELLO

- foi criado pela Toyota com post-it
- coluna 1 (a fazer ou TO DO)
- coluna 2 (fazendo ou DOING)
- coluna 3 (feito ou DONE)

## ATIVIDADE

Pesquisar e colocar no glossário pessoal:
- os conceitos de técnica versus metodologia
- pesquisar como integrar (se existe) Trello com GitHub

---

# Aula 7

## Nuvem

- IoT: todo lugar, todo o momento e conectada
- Sistema Pervasivo
- Sistema Ubíquo

---

# Aula 6

## Debate sobre tipos de sistemas de informação

- CRUD
- ERP
- CRM
- entre outros

---

# Aula 5

## Tarefa avaliativa

### Assunto:
Tipos de Sistemas de Informação

### Atividade:
Pesquisar, escrever e dar exemplos dos diferentes tipos de Sistemas de Informação.

O resultado da pesquisa deve ser colocado no arquivo `glossario.md` do repositório de cada aluno.

Enviar para:
`alexz@ufn.edu.br`

### Assunto da mensagem:
"Trabalho Fundamentos SI"

### Data:
19/03/2026

### Hora:
20:00

### Curiosidades:
Os sistemas abaixo são de que tipo de SI?

- gov.br
- Netflix
- Minha Agenda UFN
- Sistema de Imposto de Renda do Governo Brasileiro

---

# Aula 4

## Conceitos de Cloud Computing (Computação em Nuvem)

### IoT
Internet of Things (Internet das Coisas)

## Vantagens
- flexibilidade
- autonomia
- agilidade
- integração de tecnologias

## Desvantagens
- segurança
- dependência

## Arquitetura
- cliente-servidor
- ponto-a-ponto

## Modelos arquiteturais de serviços
- IaaS
- PaaS
- SaaS

---

# Aula 3

## Oficina de Git

- apresentação da oficina de Git
- apresentação, discussão e 1° trabalho avaliado

### Trabalho
Cada aluno deve criar no seu repositório da disciplina um arquivo chamado `02-glossario.md`.

Nesse arquivo será criado um vocabulário de palavras e/ou expressões estudadas na disciplina.

---

# Aula 2

## GitHub

### Apresentação e discussão da ferramenta e ambiente GitHub

- criação de conta
- criação de repositório

## Objetivos
- controle de versão
- armazenamento de backup de códigos-fonte

---

# Aula 1

## Apresentação do plano de aula

### Conceitos básicos

#### Sistema
- o que é
- para que serve
- quando usar

### Elementos que compõem um sistema

#### Aspectos estruturais
Características ou propriedades de um sistema.

#### Aspectos funcionais
Comportamento ou funcionalidades que um sistema oferece.

#### Arquiteturas de sistema
- cliente-servidor
