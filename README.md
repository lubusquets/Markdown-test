# Markdown-test

# 🐞 BUG REPORT TÉCNICO

![Status](https://img.shields.io/badge/status-em%20análise-yellow)
![Prioridade](https://img.shields.io/badge/prioridade-alta-red)
![Versão](https://img.shields.io/badge/version-1.0-blue)

# 📋 Informações Gerais

| Campo | Informação |
|---|---|
| Sistema | E-commerce Infantil |
| Ambiente | Produção |
| Navegador | Google Chrome 136 |
| Sistema Operacional | Windows 11 |
| Responsável | Luciana |
| Data | 21/05/2026 |

---

# 🚨 Descrição do Problema

> O botão de finalizar compra não responde ao clique após adicionar produtos ao carrinho.

---

# 🔄 Passos para Reproduzir

1. Acessar a página inicial
2. Adicionar um produto ao carrinho
3. Ir até o carrinho
4. Clicar em **Finalizar Compra**

---

# 📸 Evidências

## Tela do erro

![Erro](./imagens/erro.png)

---

# 💻 Logs Técnicos

```javascript
buttonCheckout.addEventListener("click", () => {
   console.log("Botão clicado");
});
```

```bash
ERROR 500 - Internal Server Error
```

---


