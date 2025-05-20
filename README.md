# 💰 Sistema de Empréstimos - Painel de Gestão

Este é um sistema web para controle de empréstimos com painel de login, cadastro de clientes e gestão de pagamentos diários. Ideal para negócios que realizam empréstimos com prazos curtos (20 e 24 dias) e juros fixos.

## 🚀 Funcionalidades

- Login protegido (usuário: `admin`, senha: `admin`)
- Cadastro de clientes com:
  - Nome
  - CPF
  - Telefone
  - Rua
  - Valor do empréstimo
  - Dias para pagamento (20 ou 24)
- Cálculo automático do valor total com taxa de 20%
- Pagamentos divididos em parcelas diárias
- Registro de pagamentos com visualização por quadradinhos:
  - 🟩 Verde: Pago
  - 🟥 Vermelho: Atrasado
  - ⬜ Cinza: A vencer
- Opções para:
  - Editar cliente
  - Excluir cliente
  - Registrar pagamento
  - Remover pagamento
- Dados persistentes no navegador (via `localStorage`)

## 🛠 Tecnologias

- React.js
- TailwindCSS
- ShadCN UI Components

## 🧪 Instalação Local

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

4. Acesse no navegador:
   ```
   http://localhost:3000
   ```

## 📝 Licença

Este projeto é de uso livre. Modifique conforme sua necessidade.

---

> Projeto criado com ❤️ por [Seu Nome]
