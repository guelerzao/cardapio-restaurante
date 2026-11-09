<!-- ═══════════════════════════════════════════════════════════════ SYSTEM://CARDAPIO-RESTAURANTE · PROJECT README · v1.0 Dica: procure por "EDITAR" para achar o que personalizar. ═══════════════════════════════════════════════════════════════ --> <p align="center"> <img src="https://capsule-render.vercel.app/api?type=venom&color=0:0D1117,45:0A2540,100:00F0FF&height=220&section=header&text=CARD%C3%81PIO%20DE%20RESTAURANTE&fontSize=44&fontColor=00F0FF&fontAlignY=42&desc=%E2%96%B8%20CARDS%20%C2%B7%20PRE%C3%87OS%20%C2%B7%20CATEGORIAS%20%C2%B7%20JAVASCRIPT&descSize=17&descColor=FF00E5&descAlignY=64&animation=twinkling&stroke=00F0FF&strokeWidth=1" alt="Banner Cardápio de Restaurante" width="100%" /> </p> <p align="center"> <a href="https://github.com/guelerzao/cardapio-restaurante"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=2800&pause=900&color=00F0FF&background=0D111700&center=true&vCenter=true&multiline=false&repeat=true&width=720&height=48&lines=%3E+CARREGANDO+CARD%C3%81PIO+DA+%22CANTINA+VERDE%22...;%3E+PRATOS+%C2%B7+PRE%C3%87OS+%C2%B7+CATEGORIAS;%3E+STATUS%3A+PROJETO+FICT%C3%8DCIO+DE+ESTUDO+%E2%9A%A1" alt="Typing animation" /> </a> </p> <p align="center"> <img src="https://img.shields.io/badge/STATUS-ONLINE-00F0FF?style=for-the-badge&labelColor=0D1117" alt="Status online" /> <img src="https://img.shields.io/badge/HTML5-0D1117?style=for-the-badge&logo=html5&logoColor=E34F26" alt="HTML5" /> <img src="https://img.shields.io/badge/CSS3-0D1117?style=for-the-badge&logo=css3&logoColor=1572B6" alt="CSS3" /> <img src="https://img.shields.io/badge/JavaScript-0D1117?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript" /> </p> <p align="center"> <a href="https://guelerzao.github.io/cardapio-restaurante/"> <img src="https://img.shields.io/badge/%E2%96%B6%20VER%20DEMO-00F0FF?style=for-the-badge&labelColor=0D1117" alt="Ver demo" /> </a> <a href="https://github.com/guelerzao"> <img src="https://img.shields.io/badge/PERFIL-FF00E5?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" alt="Perfil no GitHub" /> </a> </p> <p align="center"> <img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F0FF,100:FF00E5&height=2&section=header" width="100%" alt="divisor" /> </p> <!-- ░░░ SOBRE O PROJETO ░░░ --> <h2 align="center">⟦ 01 · SOBRE O PROJETO ⟧</h2>
yaml
projeto:      Cardápio de restaurante
restaurante:  "Cantina Verde" (fictício)
objetivo:     "Listar pratos, preços e categorias em cards claros,
               com filtro para o cliente achar o que quer rápido."
autor:        Augusto de Almeida Guelere
categorias:   [Entradas, Massas, Pratos, Sobremesas, Bebidas]
stack:        [HTML5, CSS3, JavaScript]
status:       Concluído · aceita melhorias

Cardápio digital com cards de pratos, preços em reais e botões de categoria. Os pratos ficam em uma lista no script.js, e a página é montada a partir dela, então adicionar ou remover um item é só editar uma linha.

<p align="center"> <img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF00E5,100:00F0FF&height=2&section=header" width="100%" alt="divisor" /> </p> <!-- ░░░ RECURSOS ░░░ --> <h2 align="center">⟦ 02 · RECURSOS ⟧</h2>
Módulo	O que faz
🍽️ Cards de pratos	Ícone, nome, descrição e preço de cada item
🏷️ Filtro por categoria	Botões que mostram só as Entradas, Massas, Pratos, Sobremesas ou Bebidas
💰 Preço formatado	Valores em reais com toLocaleString("pt-BR")
🧬 Dados em lista	Cardápio gerado por JavaScript a partir de um array de objetos
📱 Responsivo	Grade que se ajusta sozinha ao tamanho da tela com auto-fill
♿ Acessibilidade	Botões reais, estado aria-pressed e foco visível no teclado
🪶 Zero dependências	Só HTML, CSS e JavaScript puro (as fontes vêm do Google Fonts)
<p align="center"> <img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F0FF,100:7C3AED&height=2&section=header" width="100%" alt="divisor" /> </p> <!-- ░░░ TECH STACK ░░░ --> <h2 align="center">⟦ 03 · TECH STACK ⟧</h2> <p align="center"> <img src="https://skillicons.dev/icons?i=html,css,js,git,github,vscode&theme=dark&perline=6" alt="Tech stack" /> </p> <p align="center"> <img src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,100:FF00E5&height=2&section=header" width="100%" alt="divisor" /> </p> <!-- ░░░ COMO RODAR ░░░ --> <h2 align="center">⟦ 04 · COMO RODAR ⟧</h2>
bash
guelerzao@system:~$ git clone https://github.com/guelerzao/cardapio-restaurante.git
guelerzao@system:~$ cd cardapio-restaurante
guelerzao@system:~$ start index.html      # Windows
guelerzao@system:~$ open index.html       # macOS
guelerzao@system:~$ xdg-open index.html   # Linux

Ou simplesmente baixe o repositório e dê dois cliques no arquivo index.html.

Como editar o cardápio

Abra o script.js e mexa na lista pratos. Cada item é um objeto:

js
{ nome: "Pudim de leite", desc: "Receita da casa com calda de caramelo.", preco: 18, cat: "Sobremesas", icone: "🍮" }

Para criar uma categoria nova, basta usar um valor diferente em cat. O botão do filtro aparece sozinho.

<p align="center"> <img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF00E5,100:00F0FF&height=2&section=header" width="100%" alt="divisor" /> </p> <!-- ░░░ ESTRUTURA ░░░ --> <h2 align="center">⟦ 05 · ESTRUTURA ⟧</h2>
text
cardapio-restaurante/
├── index.html   # estrutura da página
├── style.css    # estilos, cores e responsividade
├── script.js    # lista de pratos, filtro e formatação de preço
└── README.md    # este arquivo
<p align="center"> <img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F0FF,100:FF00E5&height=2&section=header" width="100%" alt="divisor" /> </p> <!-- ░░░ PRÓXIMOS PASSOS ░░░ --> <h2 align="center">⟦ 06 · PRÓXIMOS PASSOS ⟧</h2>
bash
guelerzao@system:~$ ./roadmap --status

  [██████████] 100%  Cards, preços e filtro por categoria    ✔ CONCLUÍDO
  [██████░░░░]  60%  Publicar no GitHub Pages                ⟳ EM ANDAMENTO
  [███░░░░░░░]  30%  Fotos reais dos pratos                  ⏳ NA FILA
  [██░░░░░░░░]  20%  Carrinho de pedido                      ⏳ NA FILA

guelerzao@system:~$ _
<!-- EDITAR: ajuste as porcentagens ao seu progresso real --> <p align="center"> <img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F0FF,100:FF00E5&height=2&section=header" width="100%" alt="divisor" /> </p> <!-- ░░░ CONTATO ░░░ --> <h2 align="center">⟦ 07 · CANAIS DE COMUNICAÇÃO ⟧</h2> <p align="center"> <a href="https://www.linkedin.com/in/augusto-guelere-/" target="_blank"> <img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=00F0FF&color=0A66C2" alt="LinkedIn" /> </a> <a href="mailto:augustodealmeidaguelere@gmail.com"> <img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=FF00E5&color=D14836" alt="Email" /> </a> <a href="https://github.com/guelerzao" target="_blank"> <img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=FFFFFF&color=30363D" alt="GitHub" /> </a> </p> <p align="center"> <em>Gostou do projeto? Deixe uma ⭐ no repositório e vamos conversar.</em> </p> <p align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F0FF,50:0A2540,100:0D1117&height=120&section=footer&animation=twinkling" alt="Rodapé" width="100%" /> </p>
