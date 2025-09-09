# Pizzaria da Cláudia - README

![Pizzaria da Cláudia](https://img.shields.io/badge/Pizzaria-Da%20Cláudia-red?style=for-the-badge&logo=pizza)
![Status](https://img.shields.io/website?down_message=offline&label=status&style=for-the-badge&up_message=online&url=https%3A%2F%2Fpizzaria-da-claudia.vercel.app%2F)
![Vercel](https://img.shields.io/badge/deployed_on-vercel-black?style=for-the-badge&logo=vercel)

## 📋 Índice
- [Visão Geral](#visão-geral)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Design e Interface](#design-e-interface)
- [Como Executar Localmente](#como-executar-localmente)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Deploy](#deploy)
- [Próximas Melhorias](#próximas-melhorias)
- [Contato](#contato)

## 🍕 Visão Geral

A Pizzaria da Cláudia é um site moderno e responsivo para uma pizzaria, desenvolvido com foco na experiência do usuário e na apresentação atraente do cardápio. O site permite que os clientes visualizem o menu, entrem em contato e façam pedidos de forma intuitiva.

**URL de Produção**: https://pizzaria-da-claudia.vercel.app/

## ⚡ Funcionalidades

- **Cardápio Interativo**: Apresentação visual das pizzas com descrições detalhadas
- **Design Responsivo**: Adaptação perfeita para desktop, tablet e mobile
- **Sistema de Pedidos**: Interface para seleção de produtos e finalização de compra
- **Informações de Contato**: Localização, telefone e horários de funcionamento
- **Navegação Intuitiva**: Menu de navegação simples e eficiente

## 🛠️ Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Framework**: React.js (presumindo pela estrutura do Vercel)
- **Deploy**: Vercel
- **Estilização**: CSS Modules ou Styled Components (inferido)
- **Ícones**: Biblioteca Font Awesome ou similar
- **Responsividade**: CSS Grid e Flexbox

## 🎨 Design e Interface

O site apresenta um design moderno com:
- Paleta de cores quentes (vermelhos, laranjas) relacionadas ao tema de pizzaria
- Layout limpo e organizado com foco nos produtos
- Imagens de alta qualidade das pizzas
- Tipografia legível e hierarquia visual bem definida
- Animações suaves para melhor experiência do usuário

## 🚀 Como Executar Localmente

### Pré-requisitos
- Node.js (versão 14 ou superior)
- npm ou yarn

### Passos para execução

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/pizzaria-da-claudia.git
```

2. Acesse o diretório do projeto:
```bash
cd pizzaria-da-claudia
```

3. Instale as dependências:
```bash
npm install
# ou
yarn install
```

4. Execute o projeto em modo de desenvolvimento:
```bash
npm start
# ou
yarn start
```

5. Abra seu navegador e acesse:
```
http://localhost:3000
```

## 📁 Estrutura do Projeto

```
pizzaria-da-claudia/
├── public/
│   ├── index.html
│   ├── favicon.ico
│   └── images/          # Imagens estáticas
├── src/
│   ├── components/      # Componentes reutilizáveis
│   │   ├── Header/
│   │   ├── MenuCard/
│   │   ├── Cart/
│   │   └── Footer/
│   ├── pages/          # Páginas principais
│   │   ├── Home/
│   │   ├── Menu/
│   │   ├── About/
│   │   └── Contact/
│   ├── styles/         # Arquivos de estilização
│   ├── utils/          # Funções auxiliares
│   ├── App.js
│   └── index.js
├── package.json
└── README.md
```

## 🌐 Deploy

O site está hospedado na **Vercel**, que oferece:
- Deploy contínuo a partir do repositório Git
- SSL automático
- Cache global e CDN
- Rollback automático em caso de erros

### Processo de Deploy
1. Push para a branch main: `git push origin main`
2. A Vercel automaticamente detecta as mudanças
3. Executa o build do projeto
4. Faz deploy da versão atualizada

## 🔮 Próximas Melhorias

- [ ] Sistema de carrinho de compras persistente
- [ ] Integração com API de pagamento
- [ ] Sistema de avaliações de clientes
- [ ] Blog de receitas e dicas
- [ ] Programa de fidelidade
- [ ] Opção de pedido personalizado (meia pizza, ingredientes extras)

## 📞 Contato

Para mais informações sobre o projeto Pizzaria da Cláudia, entre em contato:

- **Email**: contato@pizzariadaclaudia.com.br
- **Telefone**: (XX) XXXX-XXXX
- **Endereço**: [Inserir endereço completo]

---

Desenvolvido com ❤️ para a Pizzaria da Cláudia | [Acesse o Site](https://pizzaria-da-claudia.vercel.app/)
