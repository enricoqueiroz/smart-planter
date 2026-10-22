# Smart Planter

Vaso inteligente com modelagem 3D feita no Autodesk Inventor,
projetado para monitorar a umidade do solo de uma planta.

## Sobre
A estrutura física (caixa principal, parte transparente e peça
inferior) foi modelada e montada no Inventor. A parte eletrônica
foi planejada e simulada: um Arduino Uno lê um sensor de umidade
do solo e mostra a leitura em um display LCD, com um anel de LED
indicando o status visualmente.

**Status atual:** modelagem 3D concluída; eletrônica simulada,
ainda não montada fisicamente.

**Link de um vídeo demonstração no LinkedIn:** https://lnkd.in/p/dquvfhU7

## Estrutura
- `inventor/` — arquivos nativos do Inventor (peças e montagem)
- `step/` — peças exportadas em STEP, abríveis em qualquer CAD
- `imagens/` — renders da montagem 3D
- `eletronica/` — diagrama do circuito planejado (Arduino, sensor
  de umidade, display LCD, anel de LED)

## Componentes planejados
- Arduino Uno
- Sensor de umidade do solo
- Display LCD 16x2
- Anel de LED (NeoPixel) para indicação visual de status

## Tecnologias
Autodesk Inventor, Arduino (C/C++)

## Próximos passos
- Montar o circuito fisicamente
- Escrever o firmware do Arduino
- Encaixar a eletrônica dentro da caixa modelada
