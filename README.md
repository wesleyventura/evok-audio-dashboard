# Painel de Produção Evok Audio

Sistema completo de controle de produção para fábrica com design moderno all black, detalhes verde e branco.

## 🚀 Acesso ao Sistema

**URL de Produção:** https://8xhpiqce3ekq.manus.space

**Credenciais de Administrador:**
- Usuário: `admin`
- Senha: `123456`

## 📋 Funcionalidades

### 🔐 Sistema de Autenticação
- Login/logout seguro
- Sessões persistentes
- Controle de permissões por usuário

### 📦 Cadastro de Produtos
- Nome do produto
- Categoria
- Quantidade produzida por hora por funcionário
- CRUD completo (Criar, Ler, Atualizar, Deletar)

### 👥 Cadastro de Funcionários
- Nome, departamento, função
- Salário e cálculo automático de custo/hora (salário ÷ 220 horas)
- Criação de usuário e senha
- Controle de permissões individuais

### 🏭 Controle de Produção
- Registro de produção com data, ordem, horário de início
- Sistema de produção pendente/finalizada
- Cálculo automático de eficiência (% acima/abaixo do estimado)
- Controle de quantidade produzida vs esperada

### 📊 Relatórios
- Filtros por período, categoria e produto
- Estatísticas de eficiência por departamento
- Relatórios detalhados de produção
- Cálculos de percentual de entrega

### 📈 Dashboard
- Métricas em tempo real:
  - Categoria mais produzida
  - Departamento mais produtivo
  - Produto mais produzido
  - Departamento com melhor eficiência
  - Custo de mão de obra por produto/categoria
- Filtros personalizáveis
- Visualizações gráficas

### ⚙️ Configurações (Apenas Admin)
- Gerenciamento de permissões de usuários
- Controle de acesso à visualização de funcionários
- Definição de administradores

## 🎨 Design

- **Tema:** All black com detalhes verde (#00ff00) e branco
- **Logo:** Evok Audio integrada em todas as telas
- **Responsivo:** Otimizado para desktop, tablet e mobile
- **UX/UI:** Interface moderna e intuitiva

## 🔧 Tecnologias

- **Backend:** Flask (Python)
- **Frontend:** HTML5, CSS3, JavaScript
- **Banco de Dados:** SQLite
- **Autenticação:** Flask Sessions com hash de senhas
- **Deploy:** Manus Platform

## 📱 Responsividade

O sistema é totalmente responsivo e funciona perfeitamente em:
- 💻 Computadores desktop
- 📱 Tablets
- 📱 Smartphones

## 🔒 Segurança

- Senhas criptografadas com hash
- Controle de sessões
- Validação de permissões em todas as rotas
- Proteção contra acesso não autorizado

## 📊 Cálculos Automáticos

### Eficiência de Produção
```
Eficiência = (Quantidade Produzida / Quantidade Esperada) × 100
Quantidade Esperada = Qtd por Hora × Horas Trabalhadas
```

### Custo por Hora
```
Custo/Hora = Salário ÷ 220 horas mensais
```

## 🚀 Como Usar

1. **Acesse:** https://8xhpiqce3ekq.manus.space
2. **Login:** Use `admin` / `123456` para acesso completo
3. **Cadastre Produtos:** Defina produtos e metas de produção
4. **Cadastre Funcionários:** Registre equipe com permissões
5. **Registre Produção:** Inicie e finalize produções
6. **Acompanhe Métricas:** Use dashboard e relatórios

## 📞 Suporte

Sistema desenvolvido especificamente para Evok Audio com todas as funcionalidades solicitadas implementadas e testadas.

---

**Desenvolvido com ❤️ para Evok Audio**

