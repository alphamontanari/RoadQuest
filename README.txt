# RoadQuest — v1.0.0

**Missão: Trânsito seguro é responsabilidade de todos.**

Projeto desenvolvido para a **Semana do Trânsito — 18 a 25 de setembro**, como ação da **Secretaria Municipal de Comunicação de Itapetininga**.

## Equipe

- **Desenvolvedor:** André Montanari
- **QA (Quality Assurance):** Arthur Luciano Nascimento da Costa
- **Órgão responsável:** Secretaria Municipal de Comunicação de Itapetininga

## Sobre o projeto

**RoadQuest** é um game educativo em HTML5 criado para transformar regras de trânsito em desafios interativos de curta duração.

A proposta da campanha é simples: em vez de apenas apresentar orientações em cards, textos ou peças publicitárias, o jogador precisa **tomar decisões corretas no trânsito para avançar de fase**.

Cada missão reproduz situações comuns de circulação urbana, como controle de velocidade, travessia escolar, semáforo, faixa de pedestres, respeito ao sentido da via e estacionamento permitido.

Ao concluir todos os desafios, o jogador desbloqueia o selo **Condutor Consciente**, reforçando a mensagem central da campanha:

> **Trânsito seguro é responsabilidade de todos.**

## Objetivo da campanha

O RoadQuest foi pensado como uma peça de comunicação pública interativa para:

- incentivar comportamentos seguros no trânsito;
- apresentar regras de forma prática e lúdica;
- aproximar a campanha de públicos acostumados a jogos e experiências digitais;
- estimular o compartilhamento da ação nas redes sociais;
- reforçar que segurança no trânsito depende de decisões individuais e coletivas.

## Missões

O jogo é composto por cinco fases progressivas.

### Fase 1 — Controle de velocidade

O jogador deve conduzir respeitando o limite da via e permanecer na mão correta.

A fase apresenta os conceitos básicos de velocidade, direção e posicionamento na faixa de circulação.

### Fase 2 — Área escolar

O jogador deve reduzir a velocidade, parar antes da faixa e aguardar todas as crianças concluírem a travessia.

A missão reforça atenção redobrada em áreas de circulação de estudantes e prioridade à travessia segura.

### Fase 3 — Cruzamento semaforizado

O jogador permanece livre para acelerar, frear ou avançar.

Entretanto, deve respeitar o ciclo do semáforo e a linha de retenção. Avançar no vermelho ou entrar em rota de colisão com outro veículo encerra a missão.

### Fase 4 — Cruzamento + faixa de pedestres

A fase combina dois conhecimentos já apresentados.

Primeiro, o jogador deve respeitar o semáforo. Depois, precisa reduzir, parar e aguardar o pedestre concluir a travessia antes de seguir.

### Fase 5 — Desafio final

A última fase reúne os principais elementos do jogo em uma única rota:

- via coletora com limite de 40 km/h;
- redução para 20 km/h na lombada sinalizada;
- via local com limite de 30 km/h;
- área escolar;
- cruzamento semaforizado;
- faixa de pedestres;
- retorno ao limite de 40 km/h;
- estacionamento em vaga permitida;
- respeito à guia amarela e acessos de garagem.

A fase funciona como uma prova final de assimilação das regras trabalhadas anteriormente.

## Requisitos para desbloquear o selo Condutor Consciente

Ao concluir o jogo, o participante recebe o selo **Condutor Consciente** após atender aos seis requisitos principais:

1. Respeitar os limites de velocidade;
2. Respeitar a travessia escolar;
3. Respeitar o semáforo;
4. Dar preferência na faixa de pedestres;
5. Manter o sentido correto da via e não invadir a contramão;
6. Estacionar somente em local permitido.

## Regras gerais de jogabilidade

Durante todas as fases, o jogador deve respeitar regras básicas de circulação.

O veículo não pode:

- subir na calçada;
- invadir a contramão;
- permanecer sobre a linha dupla contínua;
- avançar o sinal vermelho;
- colidir com outros veículos;
- avançar sobre pedestres;
- estacionar em área proibida ou em frente a garagem.

O carro também não esterça quando está completamente parado. O movimento lateral só ocorre quando o veículo está em deslocamento.

A seta para baixo funciona como freio. Mantida por aproximadamente 1,5 segundo com o veículo parado, permite engatar a marcha à ré.

## Ciclo semafórico

O sistema de semáforo utiliza um ciclo alternado entre os sentidos vertical e horizontal:

- **10 segundos — verde**;
- **4 segundos — amarelo**;
- **14 segundos — vermelho**.

Quando o sentido do jogador abre, veículos que já entraram no cruzamento concluem a travessia. Os veículos que ainda não entraram aguardam sua vez.

## Controles

### Desktop

- **↑ / W** — acelerar
- **↓ / S** — frear / manter pressionado para engatar ré
- **← / A** — virar à esquerda
- **→ / D** — virar à direita
- **P** — pausar
- **R** — reiniciar a fase
- **M** — ativar/desativar o som

### Mobile

O jogo utiliza controles touch integrados à própria tela:

- direcional esquerdo;
- acelerar;
- virar à esquerda/direita;
- frear / ré;
- pause;
- restart;
- controle de som.

A interface foi desenvolvida em formato vertical **9:16**, com canvas-base de **1080 × 1920 px**, dimensionado responsivamente para ocupar 100% da largura disponível.

## Identidade visual

A direção visual do RoadQuest utiliza estética inspirada em games 8-bit e 16-bit, com câmera top-down.

A identidade da campanha combina:

- amarelo de segurança;
- preto;
- branco;
- tons de cinza e asfalto;
- sinalização viária como elemento gráfico;
- sprites de veículos, pedestres, escolas, casas e elementos urbanos.

O objetivo foi manter o caráter institucional da Prefeitura sem perder a linguagem visual de game.

## Áudio

O projeto utiliza efeitos sonoros e música em estética 8-bit gerados via navegador.

Entre os efeitos utilizados estão:

- aceleração do veículo;
- passos durante travessias;
- feedback sonoro de sucesso;
- alerta de erro;
- efeitos associados às missões.

O usuário pode deixar o jogo mudo pelo controle de som disponível na interface.

## Compartilhamento

O RoadQuest possui recursos de compartilhamento tanto na tela inicial quanto ao final da experiência.

No início, o compartilhamento aparece de forma discreta.

Ao concluir o jogo, o jogador recebe o selo **Condutor Consciente** e pode compartilhar o resultado com a mensagem:

> Concluí o desafio da Semana do Trânsito e desbloqueei o selo Condutor Consciente: 6/6 requisitos atendidos — limites de velocidade, travessia escolar, semáforo, faixa de pedestres, sentido correto da via e estacionamento permitido. Você consegue também?

URL de produção prevista:

`https://www.itapetininga.sp.gov.br/semana-do-transito/`

O projeto também possui suporte a:

- Web Share API;
- WhatsApp;
- Facebook;
- X;
- copiar link;
- Open Graph;
- imagem de destaque para compartilhamento.

## Tecnologia

O projeto foi desenvolvido sem engine externa de jogos.

Tecnologias utilizadas:

- **HTML5**;
- **CSS3**;
- **JavaScript**;
- **Canvas API**;
- **Web Audio API**;
- **Web Share API**.

A escolha por tecnologias nativas permite que o game seja publicado como uma página web leve, incorporado ao site institucional e executado diretamente no navegador.

## Etapas de desenvolvimento

O desenvolvimento do RoadQuest ocorreu de forma incremental.

### 1. Conceito

Definição da ideia de transformar regras da Semana do Trânsito em fases de um game educativo.

### 2. Protótipo

Criação do primeiro cenário top-down, movimentação do veículo, HUD, controle de velocidade e sistema de fases.

### 3. Mecânicas educativas

Implementação das regras de:

- velocidade;
- área escolar;
- pedestres;
- cruzamentos;
- semáforos;
- estacionamento;
- contramão;
- colisões.

### 4. Mobile-first

Refatoração da interface para formato 9:16, controles touch integrados e reorganização das mensagens para evitar sobreposição aos elementos da via.

### 5. UX/UI

Aprimoramento de:

- HUD;
- feedbacks de missão;
- telas de início e conclusão;
- legibilidade em dispositivos móveis;
- identidade visual da campanha;
- controles transparentes sobre o canvas.

### 6. Áudio

Inclusão de música e efeitos sonoros em estética 8-bit.

### 7. QA

Testes de jogabilidade e identificação de problemas relacionados a:

- posicionamento de semáforos;
- colisões;
- circulação na contramão;
- travessia de pedestres;
- lógica do estacionamento;
- sinalização horizontal;
- fluxo do cruzamento;
- controles mobile;
- sensação de velocidade.

As observações de QA foram incorporadas em ciclos sucessivos de refatoração.

### 8. Branding

O game passou a utilizar o nome **RoadQuest**, mantendo a Semana do Trânsito e a Prefeitura de Itapetininga como identidade institucional da campanha.

### 9. Compartilhamento

Implementação de compartilhamento social, imagem de destaque e selo final **Condutor Consciente**.

## Versão

**RoadQuest v1.0.0**

Primeira versão consolidada para produção.

---

**Secretaria Municipal de Comunicação de Itapetininga**  
**Desenvolvimento:** André Montanari  
**Quality Assurance:** Arthur Luciano Nascimento da Costa
