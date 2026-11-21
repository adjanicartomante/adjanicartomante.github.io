# Adjani Cartomante — Site

Site estático em HTML, CSS e JavaScript.


## Funcionalidades
- Layout responsivo para desktop e celular.
- Menu mobile.
- Catálogo de serviços com seleção para o formulário.
- Formulário que abre o WhatsApp com os dados preenchidos (não envia automaticamente).
- Carta do Dia com mensagens simbólicas aleatórias.
- FAQ expansível.
- Botão flutuante de WhatsApp.

## Testar
1. Extraia a pasta/ZIP.
2. Abra `index.html` no navegador. Para testar em servidor local, na pasta do projeto execute `python -m http.server 8000` e visite `http://localhost:8000`.

## Publicar grátis com GitHub Pages
1. Crie um repositório público no GitHub.
2. Envie `index.html`, `style.css`, `script.js` para a raiz.
3. Abra Settings → Pages.
4. Selecione Deploy from a branch, branch `main`, pasta `/ (root)` e salve.
5. Aguarde o GitHub Pages publicar o endereço HTTPS.

## Personalização
O WhatsApp está configurado para `5527992445863` (Brasil + DDD + número, sem símbolos). Para alterar, modifique `WHATSAPP` no `script.js` e os links `wa.me` no HTML. Edite textos e serviços em `index.html`; cores e visual em `style.css`; cartas/mensagens em `script.js`.

## Limitações desta versão
O agendamento é encaminhado para o WhatsApp; não há banco de dados, painel administrativo, autenticação nem processamento de pagamento. Valores não foram fixados no site. A Carta do Dia é lúdica/reflexiva e não oferece previsões garantidas. Antes de divulgar, teste o número, revise o conteúdo e, se passar a coletar dados de forma persistente, publique uma política de privacidade adequada.
