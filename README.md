# 🐾 Sistema de Adoção Responsável de Cães

Uma aplicação web que conecta abrigos de cães com pessoas interessadas em adotar, promovendo um processo de adoção mais seguro, organizado e com responsabilidade.

## 👥 Perfis de Usuário (Identificações)

### 1. Abrigo
- Cadastrar animais.
- Acompanhar processos de adoção.
- Aprovar ou negar candidatos.

### 2. Adotante
- Ver lista de animais disponíveis.
- Iniciar pedido de adoção.
- Acompanhar status da solicitação.

---

## 🔄 Fluxo dos Processos

| Estado      | Descrição                                                        |
|-------------|------------------------------------------------------------------|
| Disponível  | O animal está apto para adoção e visível no sistema.            |
| Iniciado    | Um adotante iniciou o processo de adoção.                       |
| Finalizado  | A adoção foi concluída.                                         |

---

## 🗃️ Estrutura de Dados Inicial (Entidades Principais)

### 1. Usuário
- ID
- Nome
- E-mail
- Senha
- Tipo (Abrigo ou Adotante)
- Endereço
- Telefone

### 2. Animal
- ID
- Nome
- Espécie
- Raça
- Idade
- Descrição
- Foto
- Status (Disponível, Reservado, Adotado)
- ID do Abrigo

### 3. Solicitação de Adoção
- ID
- ID do Adotante
- ID do Animal
- Data da Solicitação
- Status (Iniciada, Aprovada, Rejeitada)

---

## ⚙️ Funcionalidades Principais

### Para Adotantes:
- Listar animais por filtros (espécie, idade, localização).
- Ver detalhes do animal.
- Solicitar adoção.
- Acompanhar andamento.

### Para Abrigos:
- Cadastrar e editar perfis dos animais.
- Confirmar ou recusar adoção.
- Marcar animal como adotado.

---

## 📱 Tecnologias

- **Frontend:** .NET MAUI Blazor Hybrid  
- **Backend:** ASP.NET Core  
- **Banco de Dados:** SQL Server (local)
