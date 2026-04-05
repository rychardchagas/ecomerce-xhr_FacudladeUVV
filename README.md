# E-commerce XHR — AOP3 Desenvolvimento Backend

Repositório da atividade AOP3 — Arquitetura de Interoperabilidade Web | Faculdade UVV

---

## Como funciona o XMLHttpRequest

O `XMLHttpRequest` (XHR) permite realizar requisições HTTP de forma **assíncrona**, sem travar a interface do usuário enquanto aguarda a resposta do servidor.

### Ciclo de uma requisição

1. **Ação do usuário** — o usuário clica em um botão que dispara a função JavaScript
2. **Criação do objeto** — `const xhr = new XMLHttpRequest()`
3. **Configuração** — `xhr.open("GET", "url-da-api", true)` define o método, a URL e o modo assíncrono
4. **Monitoramento** — `xhr.onreadystatechange` acompanha o `readyState` (0 a 4); quando chega em `4` com `status 200`, a resposta está pronta
5. **Tratamento de erro** — `xhr.onerror` captura falhas de conexão
6. **Envio** — `xhr.send()` dispara a requisição; a página continua responsiva
7. **Renderização** — o JSON retornado é convertido em elementos HTML e exibido na tela

---

## Como clonar o projeto

**Pré-requisito:** ter o [Git](https://git-scm.com) instalado.

```bash
git clone https://github.com/rychardchagas/ecomerce-xhr_FacudladeUVV.git
cd ecomerce-xhr_FacudladeUVV
```

Link do repositório: `https://github.com/rychardchagas/ecomerce-xhr_FacudladeUVV.git`

---

## Estrutura do Projeto

```
ecomerce-xhr_FacudladeUVV/
├── index.html   # Página principal com implementação XHR
└── README.md    # Documentação da atividade
```
