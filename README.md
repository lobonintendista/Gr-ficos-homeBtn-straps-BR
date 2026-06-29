# Wii HOME Menu & Safety Straps Graphics

Projeto dedicado ao estudo, extração, edição e preservação dos gráficos do Nintendo Wii presentes no HOME Menu (`homeBtn.arc`) e nas telas de segurança conhecidas como Safety Straps.

## Sobre

O Nintendo Wii utiliza diversos arquivos gráficos para compor sua interface. Entre os mais conhecidos estão os recursos do HOME Menu, exibido ao pressionar o botão HOME durante os jogos, e as telas de aviso de segurança exibidas antes da inicialização de muitos títulos.

Este projeto tem como objetivo documentar e facilitar a modificação desses recursos para fins de tradução, personalização e preservação.

## Conteúdo

### HOME Menu (`homeBtn.arc`)

<img width="1480" height="834" alt="tela" src="https://github.com/user-attachments/assets/fa42ee4b-bab1-4dab-b955-73dbef009509" />

Inclui elementos gráficos em png traduzidos da pasta timg, extraídos dos arquivos tpl como:

- Botões do menu HOME
- Ícones de bateria dos Wii Remotes
- Painéis e molduras
- Cursores
- Fundos e efeitos visuais
- Ícones de configurações

### Safety Straps

<img width="640" height="480" alt="+ strap2" src="https://github.com/user-attachments/assets/493427cd-d980-4cec-bc99-39ad5d270df4" />

Inclui recursos gráficos das telas de segurança, geralmente ficam em arquivos tpl ou bin com o nome "straps" com as seguintes instruções ao usuário:

- Avisos sobre o uso da pulseira do Wii Remote
- Ilustrações dos controles
- Ícones de segurança
- Mensagens de advertência
- Elementos visuais de proteção ao usuário

## Objetivos

- Extrair gráficos originais do Wii
- Converter texturas para formatos editáveis
- Traduzir textos gráficos para português brasileiro
- Preservar recursos visuais da plataforma
- Facilitar pesquisas sobre a interface do Wii
- Auxiliar projetos de tradução e modificação

## Recursos Utilizados
Para abrir o arquivo homeBtn.arc ou as straps.tpl e modificar os gráficos contidos nestes arquivos, utilize a ferramenta BrawlCrate ou BrawlBox

A estrutura mais comum do homeBtn.arc (HOME Menu do Wii) é semelhante à de outros layouts da interface do console. O arquivo geralmente é um RARC/U8 Archive, contendo layouts, animações, fontes e texturas do menu HOME.

Exemplo de estrutura:

homeBtn.arc
│
├─ anim/    - pasta cpm arquivos com animações dos botões, fade, janelas e efeitos.
│   ├─ homeBtn_00.brlan
│   ├─ homeBtn_01.brlan
│   └─ ...
│
├─ blyt/    - Arquivo que define a posição e tamanho dos elementos da interface.
│   └─ homeBtn.brlyt
│
├─ font/    - Fontes .brfnt usadas pelo menu HOME.
│   ├─ wbf1.brfnt
│   └─ ...
│
├─ timg/    - Texturas .tpl com gráficos em png (botões, ícones, fundo, bateria, volume, etc.). 
│   ├─ button_a.tpl
│   ├─ button_b.tpl
│   ├─ background.tpl
│   ├─ speaker.tpl
│   ├─ battery.tpl
│   └─ ...
│
└─ home.csv  - Textos localizados do menu HOME.

## Aviso

Este projeto é destinado exclusivamente para fins educacionais, pesquisa, preservação digital e desenvolvimento de traduções não comerciais.

## Importância Histórica

O HOME Menu e as telas Safety Straps representam alguns dos elementos mais reconhecíveis da interface do Wii. Seu design minimalista, com predominância de branco, azul-claro e transparências suaves, ajudou a definir a identidade visual da plataforma durante toda a sua vida útil.

Tradução dos gráficos by LOBO NINTENDISTA

Nintendo, Wii e seus respectivos logotipos são marcas registradas da Nintendo.
