🐍 Snake Game
Um jogo clássico da cobrinha desenvolvido com HTML5 Canvas, CSS3 e JavaScript puro, totalmente responsivo e sem dependências externas.
🎮 Demonstração
Controle a cobra, colete alimentos, aumente sua pontuação e tente sobreviver o máximo possível sem bater nas paredes ou em si mesma.
---
✨ Funcionalidades
✅ Interface moderna e responsiva
✅ Controle por teclado
✅ Controles touch para dispositivos móveis
✅ Sistema de pontuação em tempo real
✅ Aumento gradual da velocidade conforme a pontuação cresce
✅ Pausar e continuar a partida
✅ Tela de Game Over
✅ Reinício rápido da partida
✅ Design com tema escuro e animações suaves
---
🕹️ Controles
Desktop
Tecla	Ação
↑	Mover para cima
↓	Mover para baixo
←	Mover para esquerda
→	Mover para direita
P	Pausar/Continuar
Espaço	Pausar/Continuar
Mobile
Utilize os botões direcionais exibidos abaixo do jogo:
▲ Cima
▼ Baixo
◀ Esquerda
▶ Direita
---
🚀 Como executar
Opção 1 — Abrir diretamente
Salve o código em um arquivo:
```text
index.html
```
Abra o arquivo em qualquer navegador moderno:
Google Chrome
Microsoft Edge
Firefox
Safari
Nenhuma instalação adicional é necessária.
---
Opção 2 — Executar com servidor local
Se preferir utilizar um servidor local:
```bash
# Python
python -m http.server 8000
```
Depois acesse:
```text
http://localhost:8000
```
---
🏗️ Estrutura do Projeto
```text
snake-game/
│
└── index.html
```
Todo o projeto está contido em um único arquivo:
HTML → Estrutura da aplicação
CSS → Estilização e responsividade
JavaScript → Lógica do jogo
---
⚙️ Mecânicas do Jogo
Movimentação
A cobra se move em uma grade de:
```text
30 x 30 células
```
Cada célula possui:
```text
20px x 20px
```
Alimentação
Ao consumir um alimento:
A pontuação aumenta em 1 ponto
A cobra cresce
Um novo alimento aparece em uma posição aleatória
Velocidade Dinâmica
A velocidade aumenta conforme a pontuação:
```javascript
moveInterval = Math.max(55, 110 - score \* 2);
```
Isso torna o jogo progressivamente mais desafiador.
---
☠️ Condições de Derrota
O jogo termina quando a cabeça da cobra:
Colide com uma parede
Colide com o próprio corpo
---
🎨 Tecnologias Utilizadas
HTML5
CSS3
JavaScript (ES6+)
HTML5 Canvas API
---
📱 Responsividade
O projeto foi desenvolvido para funcionar em:
Desktop
Tablets
Smartphones
Em telas menores:
Os controles touch são exibidos automaticamente
O layout se adapta ao espaço disponível
---
🔧 Possíveis Melhorias
Sistema de recordes (High Score)
Armazenamento via LocalStorage
Níveis de dificuldade
Sons e efeitos sonoros
Temas personalizados
Obstáculos no mapa
Modo multiplayer local
Animações mais avançadas
---
📄 Licença
Este projeto pode ser utilizado livremente para fins educacionais, estudos e personalizações.
---
👨‍💻 Autor
Desenvolvido como um exemplo de implementação do clássico Snake Game utilizando JavaScript puro e Canvas.

