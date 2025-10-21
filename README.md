# 💰 Aplicativo de Controle Financeiro Pessoal

## 👤 Nome do Aluno
**Arthur Henrique Pereira**

## 💻 Unidade Curricular
**Codificar Aplicações para Dispositivos Móveis**

---

## 📱 Descrição do Funcionamento do Aplicativo

O aplicativo de **Controle Financeiro Pessoal** foi desenvolvido com o objetivo de ajudar o usuário a **organizar suas finanças** de forma simples e prática.  
Ele permite **registrar receitas e despesas**, **anexar comprovantes**, e **acompanhar um resumo financeiro visual** através de gráficos dinâmicos.

As principais funcionalidades incluem:

- 🔐 **Login e cadastro de usuário** com autenticação via **Supabase**.  
- 📊 **Dashboard financeiro** exibindo:
  - Saldo atual (receitas - despesas)
  - Gráfico de receitas e despesas mensais
  - Destaques como “maior despesa” ou “categoria mais usada”
- 💸 **Cadastro de receitas e despesas** com valor, categoria, data, descrição e comprovante.
- 🗂️ **Gerenciamento de categorias** (ex: alimentação, lazer, salário, etc.)
- 📅 **Listagem de lançamentos** com filtros por data, tipo e categoria.
- 📱 **Design responsivo** e interface intuitiva, compatível com diferentes tamanhos de tela.

---

## 🖼️ Prints das Principais Telas

### Tela de Login
![Login](./assets/prints/login.png)

### Dashboard
![Dashboard](./assets/prints/dashboard.png)

### Cadastro de Receita
![Cadastro de Receita](./assets/prints/cadastro-receita.png)

### Cadastro de Despesa
![Cadastro de Despesa](./assets/prints/cadastro-despesa.png)

---

## ⚙️ Tecnologias Utilizadas

- **Expo** → Facilita o desenvolvimento e testes em dispositivos móveis.  
- **React Native** → Framework principal da aplicação.  
- **Supabase** → Autenticação e banco de dados.  
- **victory-native** → Exibição dos gráficos financeiros.

---

## 🚀 Instruções para Instalação e Execução

### Pré-requisitos
- Node.js instalado  
- Expo CLI instalada (`npm install -g expo-cli`)  
- Conta no Supabase com projeto configurado  
- Variáveis de ambiente com as chaves do Supabase (se aplicável)

### Passo a passo
1. **Clone o repositório**
   ```bash
   git clone https://github.com/SEU_USUARIO/controle-financeiro.git

2. **Acesse o diretório**
   cd controle-financeiro
3. **Instale as dependências**
   npm install
4. **Inicie o projeto**
   npx expo start
5. **Execute no seu dispositivo**
   Escaneie o QR Code no terminal com o app Expo Go
   Ou pressione "a" para abrir no emulador Android

   🏁 **Conclusão**
   O aplicativo cumpre o propósito de auxiliar no controle financeiro pessoal, proporcionando uma experiência prática e intuitiva, com recursos visuais e categorização inteligente das finanças do usuário.
