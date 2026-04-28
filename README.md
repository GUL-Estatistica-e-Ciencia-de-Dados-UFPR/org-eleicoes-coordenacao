# 🗳️ GULECD/UFPR – Eleições da Coordenação

Repositório oficial para **inscrição, documentação e acompanhamento do processo eleitoral** da coordenação do GULECD/UFPR.

Este repositório implementa, na prática, o fluxo definido no Regulamento Eleitoral, garantindo:

- transparência  
- rastreabilidade  
- padronização das candidaturas  
- arquivamento histórico permanente  

---

## 📌 Objetivo

Centralizar todo o processo de registro de chapas da coordenação do GULECD/UFPR, utilizando GitHub como:

- mecanismo formal de inscrição  
- sistema de auditoria aberta  
- base de documentação eleitoral  

A abertura de um Pull Request neste repositório **constitui formalmente a inscrição da chapa**.

---

## 🧠 Estrutura do Repositório

Cada processo eleitoral ocorre em um diretório próprio:

    eleicao-gestao-XX/

Dentro de cada eleição, cada chapa deve possuir seu próprio diretório:

    eleicao-gestao-XX/
    └── chapaXX/

---

## 🧾 Como Inscrever uma Chapa

### 1. Clonar o repositório

    git clone https://github.com/<org>/org-eleicoes-coordenacao.git

---

### 2. Acessar a eleição vigente

    cd eleicao-gestao-XX

---

### 3. Criar diretório da chapa

    chapaXX/

Onde `XX` é o número identificador da chapa.

---

### 4. Adicionar os documentos obrigatórios

A chapa deve incluir **obrigatoriamente** os seguintes documentos:

#### 📄 1. Plano de Gestão – ChapaXX

- Estratégia de atuação  
- Propostas e projetos  
- Diretrizes organizacionais  
- Visão de crescimento do grupo  

---

#### 👥 2. Composição – ChapaXX

- Lista completa dos membros  
- Cargo de cada membro  
- Mini-biografia de cada integrante  

---

#### 📜 3. Declaração de Conhecimento – ChapaXX

Documento declarando que a chapa:

- conhece o Manifesto  
- conhece a Carta de Fundação  
- conhece o Código de Conduta  
- está alinhada com os princípios do grupo  

---

### 📐 Formato dos Arquivos

Todos os documentos devem ser:

- escritos em **LaTeX (.tex)**  
- acompanhados das versões:
  - `.pdf`  
  - `.md`  
  - `.html`  

---

### 🔐 Assinatura

Os documentos devem ser:

- assinados digitalmente via **PGP** pelo candidato a Coordenador Representativo 
- o coordenador representativo é responsável por garantir concordância dos demais membros  

---

### 5. Submissão

Após organizar os arquivos:

    git add .
    git commit -m "Inscrição da chapa XX"
    git push

Abrir um **Pull Request (PR)**.

---

## 📌 Importante

A abertura do Pull Request:

- formaliza a inscrição  
- define a **data oficial da candidatura**  
- torna pública toda a documentação  

---

## 🔍 Validação

A comissão eleitoral (coordenação vigente) irá:

- verificar estrutura dos arquivos  
- confirmar presença de todos os documentos  
- validar a elegibilidade da chapa  

Caso haja inconsistências, a chapa poderá ser solicitada a corrigir dentro do prazo de inscrição.

---

## 🧾 Transparência

Este repositório garante:

- acesso público às chapas  
- histórico completo das eleições  
- auditoria aberta por qualquer membro  

Todos os registros:

- permanecem permanentemente disponíveis  
- constituem o histórico institucional do grupo  

---

## ⚠️ Observações Importantes

- Este repositório é o **canal oficial de registro de chapas**  
- Inscrições feitas por outros meios devem ser replicadas aqui  
- A ausência de submissão neste repositório invalida a candidatura  

---

## 🏛️ Princípios

Este processo está fundamentado nos princípios do GULECD/UFPR:

- abertura  
- participação  
- transparência  
- responsabilidade coletiva  

---
