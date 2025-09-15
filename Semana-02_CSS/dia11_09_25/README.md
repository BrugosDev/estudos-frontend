# Exercício principal (do dia 11/09) | Main Exercise (for 11/09)

- Entender box model e espaçamento.
- Understand box model and spacing.

## Problema para resolver | Problem to solve

## Cenário | Scenario

- Uma start-up de delivery em Fortaleza (pequena, sem equipe de design) pediu uma página “Sobre” rápida para seu site. Eles querem destacar dois blocos de informação: “Como funciona” e “Nossos Planos”. Cada bloco precisa ficar visualmente separado e com espaço confortável ao redor — o cliente pede que os blocos não fiquem “colados” um no outro nem muito grandes na tela.
- A delivery start-up in Fortaleza (small, without a design team) asked for a quick 'About' page for their website. They want to highlight two blocks of information: 'How it works' and 'Our Plans.' Each block needs to be visually separated and have comfortable spacing around it — the client requests that the blocks not be 'stuck' together or too large on the screen.

- Dois blocos lado a lado (um para “Como funciona” outro para “Nossos Planos”) ou empilhados em telas pequenas.
- Two blocks side by side (one for 'How it works' and another for 'Our Plans') or stacked on small screens.

- Cada bloco deve ter borda perceptível, espaçamento interno para o texto ficar arejado e margem externa para separar os blocos.
- Each block should have a noticeable border, internal spacing for the text to be airy, and external margin to separate the blocks.

- Os blocos devem manter largura confortável (nem muito largos, nem muito estreitos).
- The blocks should maintain a comfortable width (neither too wide nor too narrow).

- Preferência que o layout não “quebre” quando o cliente aumentar o padding (ou seja, usar box-sizing que evite surpresa no tamanho total).
- Preference that the layout does not "break" when the client increases the padding (i.e., using box-sizing to avoid surprises in the total size).

- Observação: você não precisa implementar a responsividade completa agora — foque em usar corretamente width, padding, border, margin e box-sizing para deixar os blocos bem proporcionados.
- Preference that the layout does not "break" when the client increases the padding (i.e., using box-sizing to avoid surprises in the total size). ...


### Sua missão | Your mission


- Crie um arquivo chamado sobre-startup.html.
- Create a file called about-startup.html.
 
- Estruture dois blocos (div) que representem “Como funciona” e “Nossos Planos”.
- Structure two blocks (div) that represent 'How it works' and 'Our Plans'.

- Use padding para espaçamento interno, margin para separar os blocos, border para destaque, e escolha o box-sizing adequado (explique em um comentário por que escolheu border-box ou content-box).
- Use padding for internal spacing, margin to separate the blocks, border for emphasis, and choose the appropriate box-sizing (explain in a comment why you chose border-box or content-box).

- Teste em diferentes tamanhos de janela e ajuste width para manter boa leitura.
- Test in different window sizes and adjust the width to maintain good readability.


###  Por que isso importa? | Why does this matter?

- O box model é a base do layout na web. Entender como margin, border, padding e box-sizing interagem evita surpresas no layout (elementos "estourando" fora do contêiner, diferenças de tamanho inesperadas, problemas ao ajustar espaçamentos). Saber controlar isso deixa seu CSS previsível e seus designs mais estáveis — essencial antes de avançar para Flexbox/Grid e layouts complexos.

- The box model is the foundation of layout on the web. Understanding how margin, border, padding, and box-sizing interact prevents surprises in layout (elements "bursting" out of the container, unexpected size differences, issues when adjusting spacings). Being able to control this makes your CSS predictable and your designs more stable — essential before moving on to Flexbox/Grid and complex layouts.