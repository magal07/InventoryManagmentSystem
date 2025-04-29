# 📦 Inventory Management System

Sistema de gerenciamento de ordens de produção e controle de estoque, desenvolvido em C# com .NET e SQL Server. Ideal para empresas que desejam organizar e automatizar o fluxo de produção, com validações completas e uma interface amigável.

---

## 🧾 Descrição do Projeto

O **Inventory Management System** permite:

- Cadastrar, atualizar, listar e excluir ordens de produção.
- Validar dados como código da ordem, data de apontamento, quantidade, material e tempo de ciclo.
- Acompanhar o status das ordens com visualização via interface gráfica.

---

## ⚙️ Tecnologias Utilizadas

### 🖥️ Back-End
- **C#**
- **.NET Core 3.0** (API)
- **.NET Framework (Windows Forms)** – Interface desktop
- **Arquitetura MVC**
- **Validações lógica C#**

### 🗄️ Banco de Dados
- **Microsoft SQL Server**
- Conexão com ADO.NET
- Tabelas: `[tbCategory, tbCustomer, tbOrder, tbProduct, tbUser].`
- String de conexão segura e autenticada

### 🛠️ Ferramentas de Desenvolvimento
- **Visual Studio 19**
- **SQL Server Management Studio (SSMS)**
- **Postman** (testes de API)

---

## ✅ Funcionalidades

- [x] Cadastro de ordens com validações
- [x] Listagem de ordens em `DataGridView`
- [x] Edição e exclusão de ordens
- [x] Validações:
  - Código da ordem único
  - Quantidade e tempo de ciclo positivos
  - Data de apontamento válida
- [x] Interface intuitiva para usuários não técnicos

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
- Visual Studio instalado
- SQL Server LocalDB ou versão completa
- Clonar este repositório

bash
`git clone git@github.com:magal07/InventoryManagmentSystem.git` 


Configuração do Banco
Abra o SQL Server Management Studio

Execute o script database.sql (caso você tenha um)
`Vou deixar o backup do banco anexado ao repositório`

Ajuste a connectionString no projeto com suas credenciais:
"Data Source=localhost;Initial Catalog=""

Executar a aplicação
Abra o .sln no Visual Studio

Compile e execute o projeto

Use a interface para inserir, editar ou consultar ordens de produção

🧠 Autor
Magal
Desenvolvedor Back-End | Dev. Backend | C# e JS


