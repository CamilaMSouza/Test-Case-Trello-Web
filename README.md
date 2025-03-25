# Portfólio de Testes Funcionais - Trello Web

## 📌 Sobre este Repositório
Este repositório contém **casos de teste funcionais** para o **Trello Web**, abordando cenários essenciais para validação de funcionalidades relacionadas à organização de tarefas e fluxos de trabalho. 

## 🎯 Objetivo
Demonstrar minha experiência como **Tester Funcional** através da criação de **casos de teste bem estruturados**, baseados em boas práticas de QA. Estes testes podem ser executados manualmente ou servir de base para automação.

---

## 🔍 Funcionalidades Testadas

1. **Criação de um Quadro**
2. **Criação de Listas dentro de um Quadro**
3. **Criação e Edição de Cartões**
4. **Movimentação de Cartões entre Listas**
5. **Adição de Etiquetas aos Cartões**
6. **Comentários em Cartões**
7. **Arquivamento e Exclusão de Cartões**

---

## 📋 Casos de Teste

### 📝 CT001 - Criar um Quadro no Trello

**Descrição:** Verificar se o usuário consegue criar um novo quadro no Trello Web corretamente.  

**Pré-condições:** O usuário deve estar logado no Trello.

**Passos:**  
1. Acessar o Trello Web.
2. Clicar no botão **"Criar novo quadro"**.
3. Inserir um nome para o quadro.
4. Escolher uma cor de fundo (opcional).
5. Clicar no botão **"Criar"**.

**Resultado Esperado:** O novo quadro deve ser criado e exibido na tela inicial do usuário.

---

### 📝 CT002 - Criar uma Lista dentro de um Quadro

**Descrição:** Validar se o usuário consegue adicionar listas dentro de um quadro no Trello Web.

**Pré-condições:** O usuário deve estar logado e ter um quadro criado.

**Passos:**  
1. Acessar o Trello Web e abrir um quadro existente.
2. Clicar na opção **"Adicionar uma lista"**.
3. Digitar um nome para a lista.
4. Clicar no botão **"Adicionar lista"**.

**Resultado Esperado:** A nova lista deve ser adicionada ao quadro e visível para o usuário.

---

### 📝 CT003 - Criar e Editar um Cartão

**Descrição:** Validar a criação e edição de um cartão dentro de uma lista no Trello Web.

**Pré-condições:** O usuário deve ter um quadro e uma lista criados.

**Passos:**  
1. Acessar um quadro existente no Trello.
2. Clicar em **"Adicionar um cartão"** dentro de uma lista.
3. Digitar um título para o cartão.
4. Clicar em **"Adicionar cartão"**.
5. Clicar no cartão recém-criado.
6. Adicionar uma descrição e um comentário.
7. Clicar em **"Salvar"**.

**Resultado Esperado:** O cartão deve ser criado e atualizado corretamente com as novas informações.

---

### 📝 CT004 - Movimentação de Cartões entre Listas

**Descrição:** Testar se o usuário consegue mover cartões entre listas diferentes dentro de um quadro.

**Pré-condições:** O usuário deve ter pelo menos duas listas criadas em um quadro e um cartão dentro de uma delas.

**Passos:**  
1. Acessar um quadro no Trello Web.
2. Arrastar um cartão de uma lista para outra.
3. Soltar o cartão na lista de destino.

**Resultado Esperado:** O cartão deve ser movido para a nova lista e aparecer corretamente.

---

### 📝 CT005 - Adicionar Etiquetas aos Cartões

**Descrição:** Verificar se o usuário consegue adicionar etiquetas a um cartão no Trello Web.

**Pré-condições:** O usuário deve ter um cartão criado.

**Passos:**  
1. Acessar um quadro no Trello Web.
2. Clicar no cartão desejado.
3. Selecionar a opção **"Etiquetas"**.
4. Escolher uma cor de etiqueta.
5. Clicar em **"Salvar"**.

**Resultado Esperado:** O cartão deve exibir a etiqueta escolhida.

---

### 📝 CT006 - Comentar em um Cartão

**Descrição:** Testar a funcionalidade de adicionar comentários a um cartão.

**Pré-condições:** O usuário deve estar logado e ter um cartão criado.

**Passos:**  
1. Acessar um quadro no Trello Web.
2. Clicar em um cartão.
3. Digitar um comentário na área de comentários.
4. Clicar no botão **"Salvar"** ou pressionar **Enter**.

**Resultado Esperado:** O comentário deve ser salvo e visível no cartão.

---

### 📝 CT007 - Arquivar e Excluir Cartões

**Descrição:** Validar a funcionalidade de arquivamento e exclusão de cartões.

**Pré-condições:** O usuário deve ter um cartão criado em um quadro.

**Passos:**  
1. Acessar um quadro no Trello Web.
2. Clicar no cartão desejado.
3. Selecionar a opção **"Arquivar"**.
4. Clicar em **"Excluir"** e confirmar a exclusão.

**Resultado Esperado:** O cartão deve ser removido do quadro permanentemente.
