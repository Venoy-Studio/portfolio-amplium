# Amplium — Clone com Dados de Contato Fictícios

Este repositório contém o clone fiel do site [Amplium](https://amplium.vercel.app/), preservando 100% do layout, tipografia, efeitos visuais, interatividade e suporte multilíngue (PT/EN), com **apenas os dados de contato alterados para dados fictícios**, conforme solicitado.

---

## 📋 Alterações Realizadas (Contatos Fictícios)

Todos os canais de contato originais foram substituídos por dados de demonstração/fictícios:

| Canal | Original | Fictício (Atual) |
|---|---|---|
| **WhatsApp / Telefone** | `+55 88 99243-1477` | `+55 11 98765-4321` |
| **Link do WhatsApp** | `https://wa.me/5588992431477` | `https://wa.me/5511987654321` |
| **Instagram** | `https://instagram.com/amplium.co` | `https://instagram.com/amplium.ficticio` |

> Todas as integrações interativas que utilizam o WhatsApp — incluindo o botão do cabeçalho, botão da seção de captação, rodapé e o gerador dinâmico de mensagens do formulário de diagnóstico/briefing — foram atualizadas para o número fictício.

---

## 🚀 Como Executar Localmente

### Pré-requisitos
- Node.js instalado (v18+)

### Instalação e Execução
```bash
# Instalar dependências (Vite)
npm install

# Iniciar servidor de desenvolvimento local
npm run dev
```

O site estará disponível em `http://localhost:5173`.

---

## 📦 Estrutura do Projeto

```
├── assets/                  # Estilos, scripts, logos e imagens da aplicação
├── fonts/                   # Fontes Bebas Neue e Plus Jakarta Sans (.woff2)
├── fonts.css                # Declaração das fontes locais
├── index.html               # Ponto de entrada HTML da aplicação
├── package.json             # Configuração e scripts do projeto
└── README.md                # Documentação
```

---

## 🌐 Deploy

Este projeto é estático e pode ser publicado diretamente na [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/) ou [GitHub Pages] sem necessidade de configurações adicionais.
