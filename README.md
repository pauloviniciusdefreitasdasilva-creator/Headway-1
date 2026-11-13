# Headway 1 · Elementary A1–A2

Curso interativo complementar com **12 guias independentes** e navegação por unidade. Cada página pode ser aberta diretamente; não há carrossel.

## Conteúdo em cada unidade
- Explicações gramaticais, estruturas, exemplos traduzidos e pronúncia.
- Player HTML5 com **dois vídeos MP4 locais**: vídeo de abertura e vídeo principal da unidade.
- Conversation Lab calibrado ao nível de cada unidade: 5 tópicos por unidade, 5 perguntas por tópico, vocabulário, useful chunks e missão em dupla.
- Exercícios de gramática/comunicação, quiz de vocabulário e compreensão de leitura com feedback.
- Speaking, writing, contador de palavras, salvamento local e exportação.
- Modo escuro como padrão, alternância para modo claro e preferência salva.
- Controle de progresso opcional, sem prazos ou duração obrigatória.

## Estrutura
- `index.html`: página inicial e índice das unidades.
- `units/unit-01.html` … `units/unit-12.html`: guias separados.
- `data/course.json`: conteúdo e dados de cada unidade, incluindo conversação e caminhos dos vídeos.
- `assets/course.css` / `assets/course.js`: interface e interações.
- `media/videos/unit-01.mp4` … `unit-12.mp4`: vídeos principais.
- `media/openers/unit-01-opener.mp4` … `unit-12-opener.mp4`: vídeos de abertura.

## Instalação dos vídeos
Os caminhos dos players são locais. Depois de extrair o pacote de mídia no diretório raiz do repositório, a estrutura deverá conter as pastas `media/videos` e `media/openers`. Os MP4s são otimizados para reprodução no navegador e não redirecionam para YouTube.

## GitHub Pages
Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main` e pasta `/(root)`. Depois de adicionar e enviar a pasta `media/`, os 24 players estarão disponíveis também no site publicado.

## Ritmo de estudo
Não há tempo pré-definido nem prazo para concluir uma unidade. O aluno pode avançar no próprio ritmo e repetir qualquer seção sempre que precisar.

## Observação
Companion independente de estudo. Os vídeos são arquivos MP4 fornecidos no pacote de mídia do projeto.
