# Henlos Web

Interface web para sistema de orçamentos via WhatsApp, desenvolvida com Next.js, TypeScript e Tailwind CSS.

## 🚀 Tecnologias

- Next.js 14
- TypeScript
- Tailwind CSS
- Axios
- React Hook Form

## 📋 Pré-requisitos

- Node.js >= 18.x
- npm ou yarn
- [Henlos API](https://github.com/silvestrehz/henlos-api) rodando localmente

## 🔧 Instalação

1. Clone o repositório

```bash
git clone https://github.com/silvestrehz/henlos-web
cd henlos-web
```

2. Instale as dependências

```bash
npm install
```

3. Configure as variáveis de ambiente

```bash
cp .env.example .env.local
```

4. Inicie o servidor de desenvolvimento

```bash
npm run dev
```

## 📦 Scripts

- `npm run dev`: Desenvolvimento
- `npm run build`: Build
- `npm start`: Produção
- `npm run lint`: Linting

## 🌲 Estrutura do Projeto

```
src/
├── app/              # Páginas e rotas
├── components/       # Componentes React
├── services/         # Serviços e API
├── types/           # Types TypeScript
└── lib/             # Utilitários
```

## 🌿 Branches

- `main`: Produção
- `staging`: Homologação
- `develop`: Desenvolvimento
- `feature/*`: Features

## 📝 Commits

Seguimos o padrão Conventional Commits:

- `feat`: Nova feature
- `fix`: Correção de bug
- `docs`: Documentação
- `style`: Formatação
- `refactor`: Refatoração
- `test`: Testes
- `chore`: Manutenção

## 🔗 Links Relacionados

- [Backend - Henlos API](https://github.com/silvestrehz/henlos-api)

## 🤝 Contribuindo

1. Fork o projeto
2. Crie sua feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'feat: add amazing feature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT.
