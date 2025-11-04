# Product Catalog – Catálogo de Produtos (Web + Mobile)

> **Aplicação full-stack com React (Web) + React Native (Mobile)** consumindo **API REST real**.  
> Listagem, busca, detalhes e navegação completa — **pronto para produção**.

![Demo Web](https://i.imgur.com/demo-web.gif)  
![Demo Mobile](https://i.imgur.com/demo-mobile.gif)

---

## Funcionalidades

| Plataforma | Recursos |
|-----------|--------|
| **Web** | • Listagem com paginação <br> • Busca por nome <br> • Detalhes do produto (`/produto/:id`) <br> • Loading states + error handling |
| **Mobile** | • Tela inicial com botões <br> • Lista scroll infinita <br> • Navegação com stack <br> • Deep linking |

---

## API Externa (ProWeb)

> **Documentação oficial:** [Swagger UI](https://proweb.leoproti.com.br/swagger-ui/index.html)

- **Endpoint principal:** `GET /produtos`
- **Parâmetros:** `page`, `size`, `nome`
- **Resposta:** JSON com `id`, `nome`, `preco`, `imagem`, `descricao`

---

## Deploy ao Vivo

| Plataforma | Link |
|----------|------|
| **Web** | [https://product-catalog.adailc.dev](https://product-catalog.adailc.dev) |
| **Mobile** | Escaneie com **Expo Go**:  
  ![QR Code](https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=exp://exp.host/@adail-dev/product-catalog) |

---

## Estrutura do Projeto

