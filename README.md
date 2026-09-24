# Atividade Aula 03 - CSS

Este repositório contém o projeto desenvolvido para a atividade da Aula 03 da disciplina de Desenvolvimento Web I, onde foram aplicados estilos CSS a uma página institucional.

## Relatório do Projeto

* **Tema da Página:** Página institucional da empresa fictícia **TechNova Soluções Digitais**, destinada à apresentação da empresa, serviços prestados e contactos.
* **Cores Escolhidas:**
  * **Azul Escuro (`#1e3a8a` e `#0f172a`):** Aplicado no cabeçalho, rodapé e títulos para transmitir confiança e profissionalismo.
  * **Cinzento Claro (`#f4f7f6`):** Aplicado no fundo do `body` para proporcionar um contraste suave e leitura confortável.
  * **Branco (`#ffffff`):** Aplicado nas áreas de destaque (`#sobre` e `.card`) para evidenciar o conteúdo principal.
  * **Cinzento Neutro (`#4a5568` e `#64748b`):** Utilizado nos parágrafos para garantir uma legibilidade adequada.
* **Seletores Utilizados:**
  * **Seletores por Tag:** `body`, `main`, `nav`, `a`, `img`, `section`, `h1`, `h2`, `h3`, `p`.
  * **Seletores por Classe:** `.card`, `.logo`, `.imagem-institucional`, `.container-cards`.
  * **Seletores por ID:** `#cabecalho`, `#sobre`, `#servicos`, `#rodape`.
* **Aplicação de Margin, Padding e Border:**
  * `margin`: Aplicado no `main` (`2rem auto`) para centralizar a página, na secção `#sobre` (`margin-bottom: 2rem`), nos títulos e na margem externa dos cartões (`.card`).
  * `padding`: Aplicado no `#cabecalho`, `#sobre`, `#rodape` e internamente nos cartões (`.card`) para afastar o texto das extremidades das caixas.
  * `border`: Aplicado na imagem (`2px solid #cbd5e1`), no painel `#sobre` (`1px solid #e2e8f0`) e no contorno dos cartões `.card` (`2px solid #94a3b8`).
* **Utilização do Box Model:**
  * Foi definida a regra global `* { box-sizing: border-box; }` no início do CSS para garantir que o tamanho final das caixas inclua o `padding` e a `border`.
  * O Box Model é demonstrado nos cartões `.card`, combinando o conteúdo interno, um `padding` de `1.5rem`, uma `border` de `2px` e uma `margin` de `0.5rem`.
* **Dificuldade Encontrada e Resolução:**
  * *Dificuldade:* A imagem ultrapassava os limites laterais do ecrã ao diminuir o tamanho da janela do navegador.
  * *Resolução:* Foi aplicada a propriedade `max-width: 100%` e `height: auto` na regra da imagem, tornando a apresentação responsiva e ajustada ao espaço disponível.
