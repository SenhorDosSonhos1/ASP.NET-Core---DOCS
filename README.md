# 📚 ASP.NET Core MVC - Guia Básico

> Documentação oficial: [ASP.NET Core MVC - Microsoft Learn](https://learn.microsoft.com/pt-br/aspnet/core/mvc/overview?view=aspnetcore-9.0)

---

## 🚀 O que é o ASP.NET Core MVC?

O **ASP.NET Core MVC** é uma estrutura avançada para criação de **aplicativos Web e APIs** utilizando o padrão de design **Model-View-Controller (MVC)**.

---

## 🧱 Padrão de Arquitetura MVC

O padrão **MVC** separa a aplicação em três componentes principais:

- **Model**: Representa os dados e a lógica do banco de dados.
- **View**: Responsável por apresentar a interface ao usuário (frontend), usando Razor Syntax no HTML.
- **Controller**: Contém a **lógica de negócio**. Ele manipula as entradas do usuário, interage com o Model e define qual View será exibida.

### 🧭 Fluxo Resumido:
1. O usuário faz uma requisição.
2. A requisição vai para o **Controller**.
3. O Controller usa o **Model** para processar os dados.
4. O Controller escolhe a **View** e envia os dados para exibição.

---

## 🛠️ Instalação e Configuração

### 📥 Instalar o .NET SDK
Acesse: [https://dotnet.microsoft.com/pt-br/download](https://dotnet.microsoft.com/pt-br/download)

### 🚧 Criar um novo projeto MVC
```bash
dotnet new mvc -n NomeDoProjeto
