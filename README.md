# Comunidade da Fé · Church — Plataforma de Gestão

Plataforma de gestão da igreja (membros, batismo, grupos, eventos, contatos e indicadores),
desenvolvida pela **Smart Automation**.

## Publicar o link (GitHub Pages)
1. Suba o arquivo `index.html` neste repositório.
2. **Settings → Pages → Branch: `main` → Save**.
3. Em alguns minutos o link fica disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPO`.

## Importante — dados das pessoas
Este arquivo **não contém dados de membros**. Os cadastros ficam na planilha
privada do Google (banco central), nunca no repositório público.

Para ligar o banco central:
1. Publique o Apps Script (arquivo `Codigo_AppsScript.gs`) como app da web.
2. Cole a URL na 1ª linha do `index.html`:

       const BACKEND_URL="https://script.google.com/macros/s/.../exec";

3. Faça o commit. A partir daí todos veem os mesmos dados e o login é validado no servidor.

## Acesso
- **admin** — controla configurações (Smart Automation)
- **igreja** — uso diário da equipe

Troque as senhas padrão no painel **Administração** ao entrar.

---
© Smart Automation · Automação · BI · Tecnologia
