# BurguerPDV

MVP demonstrativo de cardápio digital para hamburguerias, com identidade visual preta e laranja.

## Funcionalidades

- Landing page com apresentação, recursos e planos sugeridos.
- Cardápio responsivo com busca, categorias e carrinho.
- Pedido formatado para envio ao WhatsApp.
- Painel demonstrativo para cadastrar, editar e ocultar produtos.
- Personalização de nome, logo por URL, endereço, WhatsApp e taxa de entrega.
- Armazenamento local no navegador via localStorage.

**Importante:** este projeto ainda não é um SaaS multiusuário pronto para vender. Não possui autenticação, backend, Firestore, armazenamento de arquivos, pagamentos nem gestão de pedidos persistida. Os dados do painel são locais, não compartilhados entre dispositivos.

## Rodar

```bash
npm install
npm run dev
npm run build
npm run lint
```

Requer Node.js 20+. Para Vercel: framework Vite, build npm run build, saída dist.

## Etapas seguintes

1. Firebase Authentication e cadastro de hamburguerias.
2. Firestore, isolamento por tenant e regras de acesso.
3. Upload real de fotos e logos via Storage.
4. Rotas públicas por slug com dados do banco.
5. Assinaturas e autorização de plano no servidor.
6. Registro de pedidos, testes E2E e observabilidade.
