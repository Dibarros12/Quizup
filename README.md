# QuizUp - Quiz de Bar

Website estatico pronto para publicar na Vercel.

## Ficheiros

- `index.html`: aplicacao completa com o banco integrado.
- `quizup-banco-unico.json`: banco editavel e copia de seguranca.
- `README.md`: documentacao do projeto.

## Banco de perguntas

- 450 perguntas unicas e revistas integradas no `index.html`.
- Quatro opcoes distintas e semanticamente relacionadas com cada pergunta.
- Categorias e niveis de dificuldade.
- Validacao de perguntas, opcoes e identificadores duplicados na importacao JSON.
- Historico de perguntas utilizadas guardado no navegador.

O site funciona imediatamente apos a publicacao, sem ser necessario importar o JSON. O botao **Banco JSON** permite substituir o banco no navegador, exporta-lo ou repor o banco integrado de 450 perguntas.

## Funcionalidades

- Um a oito jogadores ou equipas.
- Temporizador, pontuacao e modo automatico.
- Layout adaptado a computador e telemovel na vertical.
- Ecra inteiro sem deslocamento durante a partida.
- Estatisticas finais por equipa.
- Perguntas certas, erradas e percentagem de acerto.
- Desempenho por categoria.
- Lista de perguntas falhadas, resposta escolhida e resposta correta.

## Publicar na Vercel

1. Coloque os tres ficheiros na raiz do repositorio GitHub.
2. Confirme que o ficheiro principal se chama exatamente `index.html`.
3. Faca commit no ramo `main`.
4. A Vercel publica a nova versao atraves do projeto ligado ao repositorio.

Nao e necessario comando de build, servidor ou base de dados.


### Analytics
- Vercel Web Analytics integrado no `index.html`.
- Ative **Analytics** no painel do projeto Vercel antes da nova publicacao.
