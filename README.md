# Rede Segura

Site informativo sobre violência doméstica, desenvolvido como projeto de extensão da UNIASSELVI ("Desenvolvimento de sites ou aplicativos sobre violência doméstica", ODS 16) pelo aluno de Segunda Licenciatura Álvaro Machado Júnior, com o apoio da OSC AFAGO (instituição parceira).

**Site:** https://redesegura.alvaromjunior.com

## O que o site oferece

- Faixa fixa com 190, Ligue 180 e WhatsApp 180
- Botão **Sair rápido** (e tecla Esc duas vezes), que troca a tela por uma página neutra
- As cinco formas de violência da Lei Maria da Penha (Lei 11.340/2006, art. 7º)
- Medidas protetivas e penas atualizadas pela Lei 14.994/2024
- Canais de denúncia e rede de apoio em São Paulo
- Teste "Isso é violência?", mitos e verdades, como ajudar alguém
- Sem cookies, sem formulários, sem coleta de dados

## Tecnologia

HTML, CSS e JavaScript em um único arquivo (`index.html`), sem banco de dados nem dependências. Publicado no Cloudflare Pages a partir deste repositório: cada alteração na branch `main` atualiza o site automaticamente.

## Como trocar um telefone, endereço ou texto

1. Abra `index.html` e procure o bloco `const DATA = {` no início do `<script>`.
2. Edite o item desejado em `channels` (canais de denúncia), `places` (rede de apoio), `forms`, `quiz` ou `myths`.
3. Salve (no GitHub: botão de lápis → *Commit changes*). O site se atualiza em cerca de 1 minuto.

Itens marcados `todo: true` aparecem com a etiqueta "Preencher com a parceira". Ao completar os dados, apague `todo: true` daquele item.

## Créditos

- Foto da página inicial: [Engin_Akyurt](https://pixabay.com/pt/users/engin_akyurt-3656355/) / Pixabay
- Fontes das informações: Lei 11.340/2006, Lei 14.994/2024, Ministério das Mulheres, Prefeitura de São Paulo, Polícia Civil de SP, TJSP
