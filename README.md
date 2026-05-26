# Jogo Pac-Man — Scratch

![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-green)
![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-green)
![Scratch](https://img.shields.io/badge/Scratch-4D97FF?logo=scratch&logoColor=white)

Material didático para o desenvolvimento do clássico jogo **Pac-Man** utilizando o ambiente de programação visual **Scratch**, mantido pelo MIT. O projeto foi elaborado para o ensino de **lógica de programação para crianças**, propondo a construção do jogo de forma incremental ao longo de cinco encontros.

---

## Sobre o projeto

A implementação do jogo permite que as crianças exercitem, de forma lúdica, os principais fundamentos da lógica de programação e do pensamento computacional. O Pac-Man deve percorrer o labirinto, coletar todas as bolinhas e desviar dos fantasmas, contemplando mecânicas de movimento, detecção de colisões, sistema de pontuação e progressão por níveis.

O Scratch foi escolhido por permitir a introdução desses conceitos sem que a sintaxe de uma linguagem tradicional se torne uma barreira inicial. A linguagem por blocos é especialmente adequada ao público infantil, mantendo o foco no raciocínio lógico, na criatividade e na resolução de problemas.

---

## Controles e jogabilidade

- Movimentação do Pac-Man pelo labirinto utilizando as **setas do teclado** (↑ ↓ ← →)
- Coleta de **bolinhas** para acúmulo de pontos e progressão de nível
- Desvio dos **fantasmas** (vermelho, rosa, ciano e laranja), que provocam o fim do jogo em caso de contato
- Coleta de **Power Pellets** (bolinhas grandes), que tornam os fantasmas temporariamente vulneráveis e permitem capturá-los para obtenção de pontos adicionais

---

## Plano de aula

O desenvolvimento do jogo é distribuído em cinco aulas, organizadas de forma a apresentar gradualmente novos conceitos e mecânicas, respeitando o ritmo de aprendizado das crianças.

### Aula 1 — Introdução e configuração do projeto

**Objetivos**

- Apresentar o projeto e seus objetivos
- Conhecer a interface do Scratch
- Criar o cenário (labirinto) e os personagens (Pac-Man e fantasmas)
- Configurar os sprites e prepará-los para animação

**Conteúdo**

- Desenho ou importação do labirinto como plano de fundo
- Criação e importação dos sprites do Pac-Man e dos fantasmas
- Navegação básica na interface do Scratch (palco, sprites, blocos)
- Uso do editor de fantasias para animar o Pac-Man (boca aberta e fechada)
- Boas práticas de nomenclatura de sprites para organização do projeto

---

### Aula 2 — Movimentação do Pac-Man

**Objetivos**

- Programar o controle do Pac-Man com as setas do teclado
- Garantir movimentação suave e contínua
- Impedir que o Pac-Man atravesse as paredes do labirinto

**Conteúdo**

- Blocos de movimento: apontar direção e mover passos
- Detecção de cor para identificação de colisão com paredes
- Ajustes de velocidade e fluidez na movimentação

---

### Aula 3 — Fantasmas e colisão

**Objetivos**

- Criar a movimentação automática dos fantasmas
- Programar o comportamento de perseguição ou movimentação aleatória
- Definir a colisão entre os fantasmas e o Pac-Man como condição de fim de jogo

**Conteúdo**

- Uso de direção aleatória ou lógica de perseguição
- Condição de contato com o Pac-Man para encerramento da partida
- Exibição de mensagem de fim de jogo e mecânica de reinício

---

### Aula 4 — Bolinhas e sistema de pontuação

**Objetivos**

- Posicionar bolinhas pelo labirinto
- Programar o Pac-Man para coletar as bolinhas ao tocá-las
- Atualizar a pontuação exibida em tela
- Definir a condição de vitória da partida

**Conteúdo**

- Uso de clones para criação de múltiplas bolinhas
- Variável de pontuação para contabilização dos pontos
- Condição de vitória ao coletar todas as bolinhas do labirinto

---

### Aula 5 — Power Pellets e refinamentos finais

**Objetivos**

- Criar os Power Pellets, que conferem vantagem temporária ao jogador
- Alterar o comportamento dos fantasmas durante o efeito do poder
- Adicionar sons e efeitos visuais à jogabilidade
- Realizar testes e ajustes finais

**Conteúdo**

- Uso de variáveis para controle de estados temporários (por exemplo, `poder = 1`)
- Comportamento dos fantasmas em estado vulnerável
- Inclusão de sons e animações para feedback ao jogador
- Revisão geral e discussão de possíveis expansões (novos níveis, ajustes de velocidade, personalização de personagens)

---

## Conceitos aplicados

| Área | O que o projeto demonstra |
|------|---------------------------|
| **Lógica de programação** | Estruturas condicionais, laços de repetição, variáveis e estados |
| **Pensamento computacional** | Decomposição de problemas, abstração e reconhecimento de padrões |
| **Eventos e interação** | Captura de entradas do teclado e resposta a eventos |
| **Detecção de colisão** | Verificação por contato com sprites e por cor |
| **Programação orientada a sprites** | Comunicação entre sprites, uso de clones e mensagens |

---

## Como acessar o projeto

O projeto pode ser executado diretamente no editor online do Scratch, sem necessidade de instalação:

1. Acesse [https://scratch.mit.edu](https://scratch.mit.edu)
2. Faça o upload do arquivo `.sb3` disponibilizado no repositório
3. Clique na bandeira verde para iniciar o jogo

---

## Observação para educadores

Este plano de aula foi elaborado com o objetivo de introduzir lógica de programação, pensamento computacional e criatividade por meio do desenvolvimento de um projeto completo e familiar às crianças. A estrutura é flexível e pode ser adaptada conforme a faixa etária e o nível da turma, com inclusão ou supressão de mecânicas e ajustes na complexidade das atividades propostas.

---

## Sobre o material

Todo o conteúdo deste repositório é de autoria própria, desenvolvido para fins didáticos com o objetivo de apoiar o ensino de lógica de programação para crianças. O material pode ser utilizado, adaptado e compartilhado, desde que mantidos os devidos créditos.

---

## Autora

**Marianna Rossi**

[GitHub](https://github.com/mariannarossim)

---

## Licença

Este material está licenciado sob a [MIT License](https://opensource.org/licenses/MIT) e pode ser utilizado para fins de estudo e ensino, mantendo os créditos da autora.
