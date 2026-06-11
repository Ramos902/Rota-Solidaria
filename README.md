# Rota Solidária

Plataforma web voltada à promoção de campanhas de doação de sangue na região de Angatuba e Sorocaba. O sistema conecta doadores a campanhas organizadas por unidades de saúde locais, permitindo inscrições, acompanhamento de status e gestão administrativa das ações.

🔗 **[Acesse o projeto](https://ramos902.github.io/Rota-Solidaria/)**

---

## Tecnologias

- HTML5
- CSS3 (com variáveis customizadas)
- JavaScript (vanilla)
- Tailwind CSS (via CDN)
- Lucide Icons
- VLibras (acessibilidade em Libras)

---

## Front-End

Interface desenvolvida com HTML, CSS customizado e Tailwind CSS, estruturada em duas áreas principais: o site público, voltado aos doadores, e o painel administrativo, destinado às unidades de saúde.

O site público apresenta as campanhas disponíveis, detalhes de cada ação e o fluxo de inscrição. O painel administrativo permite às unidades criar e gerenciar campanhas, acompanhar inscrições e visualizar relatórios básicos.

### Interações

As interações são gerenciadas inteiramente por JavaScript vanilla. O sistema implementa:

- Alternância de tema claro/escuro com persistência via `localStorage`
- Controles de acessibilidade: ajuste de tamanho de fonte e modo de alto contraste
- Integração com VLibras para tradução em Língua Brasileira de Sinais
- Menus responsivos para mobile
- Validações de formulário com feedback visual via toast
- Destaque dinâmico do item de navegação ativo, baseado na URL atual

As preferências do usuário (tema, fonte, contraste) são mantidas entre sessões.

### Estilização

- As fontes utilizadas são **Inter** (interface geral) e **Newsreader** (títulos), importadas do Google Fonts.
- A paleta tem como cor de marca o vermelho `#e02035`, verde `#1a9e6e` como cor de destaque e âmbar `#f07c3a` para ações secundárias, sobre superfícies neutras em branco e lavanda claro.
- O layout combina CSS customizado com classes utilitárias do Tailwind CSS, usando Grid e Flexbox. Páginas administrativas seguem estrutura de duas colunas (formulário + sidebar); o site público alterna entre grade para listagens e coluna única para detalhes.
- O sistema de temas é implementado via classes no elemento `<html>` (`dark`, `alto-contraste`) combinadas com variáveis CSS, permitindo troca visual completa sem recarregamento da página.

---

## Back-End

O projeto é um protótipo front-end estático, sem back-end implementado. Não há servidor, banco de dados ou autenticação real — os dados de campanhas são hardcoded no HTML e as ações de formulário simulam respostas via JavaScript. Uma eventual evolução do projeto envolveria uma API REST e persistência em banco de dados.

---

## Ferramentas e uso de Inteligência Artificial

### Ferramentas

- **Git e GitHub** — versionamento, trabalho colaborativo e hospedagem via GitHub Pages.
- **Visual Studio Code** — editor de código utilizado no desenvolvimento.
- **Google Fonts** — importação das fontes utilizadas na interface.
- **Lucide Icons** — biblioteca de ícones SVG utilizada nos componentes visuais.
- **VLibras** — widget do governo federal para acessibilidade em Libras.

### Aplicação da IA

- **ChatGPT** — auxílio na idealização e explicação do código, com foco didático no aprendizado da estrutura do projeto.
- **Claude** — apoio na geração e revisão de componentes de interface, formatação e revisão dos textos de documentação, promovendo clareza para o leitor.

---

## Considerações Finais

O projeto foi desenvolvido como atividade de extensão do IFSP Campus Itapetininga, com o objetivo de aproximar a comunidade de ações de doação de sangue na região. O foco esteve no desenvolvimento de uma interface acessível, responsiva e funcional, aplicando na prática os conceitos de HTML, CSS e JavaScript estudados ao longo do curso.

---

## Autores

<table>
  <tr>
    <td align="center"><a href="https://github.com/andrwza"><img src="https://github.com/andrwza.png" width="80" height="80" style="border-radius:50%"/><br><sub>Andreza</sub></a></td>
    <td align="center"><a href="https://github.com/Buenno0"><img src="https://github.com/Buenno0.png" width="80" height="80" style="border-radius:50%"/><br><sub>Mateus</sub></a></td>
    <td align="center"><a href="https://github.com/FernandoNino38"><img src="https://github.com/FernandoNino38.png" width="80" height="80" style="border-radius:50%"/><br><sub>Fernando</sub></a></td>
    <td align="center"><a href="https://github.com/Ramos902"><img src="https://github.com/Ramos902.png" width="80" height="80" style="border-radius:50%"/><br><sub>Ramos</sub></a></td>
  </tr>
</table>
