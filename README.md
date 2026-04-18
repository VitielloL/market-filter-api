# 📦 MarketFilter - Kafra Portal Data Query Tool

Uma ferramenta poderosa e flexível para consultar e filtrar dados de marketplace do Kafra Portal. Integre filtros por ID, nome e refinamento em seus projetos com facilidade.

## 🎯 Sobre

MarketFilter é uma solução completa para processamento de dados de marketplace, oferecendo múltiplas estratégias de filtragem para atender diferentes necessidades de consulta. Perfeita para análise de dados de marketplace e integração com aplicações web e Node.js.

## 🛠️ Tecnologias

- **JavaScript** - Lógica de filtro
- **Node.js v18.14.1+** - Ambiente de execução
- **JSON** - Formato de dados
- **HTML5** - Interface web

## ⚙️ Como Usar

### Execução via Node.js

```bash
# Filtrar por ID
node filtroID.js

# Filtrar por Nome
node filtroNome.js

# Filtrar por Nome com Refinamento
node filtroNomeRefine.js
```

### Uso no Navegador

Abra `filtro.html` no seu navegador para usar a interface web de filtros.

## 📊 Estrutura de Dados

A aplicação trabalha com objetos JSON contendo:
- `id` - ID do item
- `nameid` - ID do nome
- `price` - Preço do item
- `amount` - Quantidade disponível
- `vendor_name` - Nome do vendedor
- `buyer_name` - Nome do comprador
- E muitos outros campos de marketplace

## 📁 Arquivos

- `filtro.js` - Script principal de filtros
- `filtroID.js` - Filtro especializado por ID
- `filtroNome.js` - Filtro especializado por Nome
- `filtroNomeRefine.js` - Filtro avançado com refinamento
- `filtro.html` - Interface web interativa
- `data.json` - Dados de exemplo do marketplace

## 🚀 Funcionalidades

✅ Filtro por ID de item  
✅ Filtro por Nome de item  
✅ Filtro com refinamento  
✅ Interface web integrada  
✅ Suporte Node.js  
✅ Processamento de JSON  

## 📝 Licença

MIT
