# Start nos Estudos

Jornadas de aprendizado gamificadas do portal **Disciplinas do Prof. Eber Santana** (IFS Campus Tobias Barreto).

Página: https://ebersantana.github.io/startnosestudos/

## Como funciona

- Usa o mesmo login (turma, nome e PIN) do portal em `../disciplinas/`. Os dois ficam no mesmo endereço, então o jogo lê o perfil e o progresso do aluno.
- Pontos: +10 por página nova aberta numa disciplina, +5 por dia de estudo, +3 por atividade em laboratórios e simuladores (+50 ao concluir), e os pontos dos módulos interativos (flashcards, V ou F, caderno e PBL).
- Níveis, missão do dia, "continuar de onde parou", semana de estudo, mapas de aventura e conquistas.
- Sincronização entre aparelhos: a ação `jornada` do Apps Script do portal (`disciplinas/apps-script/Codigo.gs`) junta as páginas visitadas e os dias de estudo na aba **Jornadas** da planilha e devolve o progresso de cada material. Sem ela, o jogo mostra o progresso guardado no aparelho.

## Arquivos

- `index.html`: a página inteira (HTML, CSS e JavaScript, sem dependências). Carrega `aparencia.js`, `config.js`, `progresso-turma.js` e `acessibilidade.js` do portal.
