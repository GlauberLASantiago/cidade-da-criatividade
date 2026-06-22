# 🌈 Cidade da Criatividade

Jogo educativo 3D em navegador onde o jogador explora uma cidade colorida, coleta moedas douradas e descobre murais sobre criatividade e música. Ao concluir o desafio, um certificado é gerado para entrega no Moodle.

## 🎮 Sobre o Jogo

O jogador percorre ruas de uma cidade animada, encontrando **30 moedas douradas** espalhadas pela cidade. Cada moeda está associada a um **mural educativo** com conteúdo sobre criatividade e música. Personagens NPC caminham pelas ruas, tornando o ambiente mais vivo. Ao coletar todas as moedas e ler todos os murais, o jogo exibe uma tela de vitória com opção de **baixar o certificado de conclusão**.

## 🕹️ Controles

### Desktop
| Ação | Tecla |
|------|-------|
| Andar | `W` `A` `S` `D` |
| Olhar | Teclas de seta |
| Pular / Ver moedas ao longe | `Espaço` |

### Mobile
| Ação | Gesto |
|------|-------|
| Andar | Joystick na tela |
| Olhar | Deslize à direita |
| Pular / Ver moedas ao longe | Botão **Pular** |

## 🚀 Como Jogar

1. Abra o arquivo `index.html` em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
2. Digite seu nome completo na tela inicial.
3. Clique em **Jogar** (ou pressione `Enter`).
4. Explore a cidade e colete as 30 moedas douradas flutuantes.
5. Ao coletar todas as moedas, clique em **Baixar certificado** e entregue no Moodle.

> Nenhuma instalação ou servidor é necessário — o jogo roda diretamente no navegador.

## 🗂️ Estrutura do Projeto

```
cidade-da-criatividade/
├── index.html            # Jogo completo (HTML + CSS + JS em um único arquivo)
├── moeda.mp3             # Som de coleta de moeda
├── npc.mp3               # Som dos personagens NPC
├── pulo.mp3              # Som de pulo
├── carro-bate.mp3        # Som de colisão com veículo
├── colidiu.mp3           # Som de colisão
├── transito.mp3          # Som ambiente de trânsito
├── musica-de-fundo.mp3   # Trilha sonora do jogo
└── venceu.mp3            # Som de vitória
```

## 🛠️ Tecnologias

- **[Three.js r128](https://threejs.org/)** — renderização 3D no navegador via WebGL
- **HTML5 / CSS3 / JavaScript** — sem dependências extras além do Three.js
- **Web Audio API** — efeitos sonoros e trilha sonora

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais.
