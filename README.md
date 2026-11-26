# Portfólio — Janderson Dias (DevDiaas)

Site de portfólio em **HTML + CSS + JavaScript puros** (sem build, sem dependências para instalar).

## Estrutura

```
index.html                     → o site inteiro (HTML, CSS e JS)
assets/                        → imagens otimizadas (WebP)
curriculo-janderson-dias.pdf   → currículo (botão "Download resume")
```

## Como abrir no VS Code

1. Abra a pasta no VS Code.
2. Instale a extensão **Live Server** e clique em *Go Live* (ou abra o `index.html` direto no navegador).

## Como publicar

**GitHub Pages**
1. Crie um repositório e envie estes arquivos:
   ```bash
   git init
   git add .
   git commit -m "Novo portfólio"
   git branch -M main
   git remote add origin https://github.com/DevDiaas/NOME-DO-REPO.git
   git push -u origin main
   ```
2. No GitHub: *Settings → Pages → Deploy from a branch → main / (root)*.

**Vercel** — importe o repositório; não precisa de nenhuma configuração (projeto estático).

## O que editar

| O quê | Onde procurar no `index.html` |
|---|---|
| Textos em inglês | os próprios elementos (`data-i="..."`) |
| Textos em português | objeto `PT` dentro da tag `<script>` |
| Projetos (links, tecnologias) | seção `id="projects"` |
| Contatos (e-mail, WhatsApp, redes) | seção `id="contact"` |
| Currículo | substitua `curriculo-janderson-dias.pdf` mantendo o nome |

## Formulário de contato

O formulário envia por [FormSubmit](https://formsubmit.co) para o e-mail configurado no `index.html`.
**No primeiro envio**, o FormSubmit manda um e-mail de confirmação para esse endereço: clique no link
para ativar. Depois disso as mensagens chegam normalmente.
