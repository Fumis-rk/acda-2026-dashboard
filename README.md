# ACDA 2026 — Dashboard

## Configuração já feita

O `config.js` deste pacote já contém os dois links CSV publicados da sua Google Planilha:

- TURMAS
- HORARIOS

Não altere esses links.

## GitHub

1. Crie um repositório, por exemplo `acda-2026-dashboard`.
2. Envie:
   - `index.html`
   - `config.js`
   - `README.md`

## Netlify

1. Entre no Netlify.
2. `Add new project` → `Import an existing project`.
3. Escolha o repositório do GitHub.
4. Build command: deixe vazio.
5. Publish directory: `.`
6. Publique.

## Google Planilhas

A fonte do dashboard é a planilha publicada em CSV. Portanto:

- continue editando as abas `TURMAS` e `HORARIOS`;
- não mude os nomes dos cabeçalhos;
- não exclua as colunas `ID_TURMA`, `ID_HORARIO` etc.;
- o dashboard lerá os dados publicados quando for carregado.

## Estrutura

TURMAS = uma linha por turma.

HORARIOS = uma linha por horário da turma.

Uma mesma turma pode ter vários horários sem ser duplicada.

## Observação

Como as abas estão publicadas na Web, os dados dessas abas ficam acessíveis a quem tiver os links publicados. Não coloque informações pessoais ou sensíveis nessa base.

## Próximos aprimoramentos

Depois da publicação podemos acrescentar:

- botão Atualizar;
- filtro por dia;
- impressão/PDF;
- cores por modalidade;
- tela de cadastro;
- edição da planilha pelo dashboard;
- domínio personalizado.
