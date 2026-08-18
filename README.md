# ACDA 2026 — Dashboard V3

Esta versão mantém a Google Planilha como fonte e adiciona:
- grade semanal;
- filtros por escola, modalidade, categoria, naipe, professor e dia;
- busca;
- limpar filtros;
- atualizar dados;
- impressão;
- visão por turmas;
- visão por escolas;
- alertas de cadastros incompletos;
- detecção de conflito de horário do mesmo professor;
- layout responsivo.

## Atualização no GitHub

Substitua no seu repositório os arquivos:
- index.html
- config.js

O README pode ser substituído também.

Não altere os links do `config.js`.

## Google Planilhas

Continue usando as abas:
- TURMAS
- HORARIOS

A publicação CSV já está configurada.

## Deploy Netlify

Se o Netlify estiver conectado ao GitHub, basta fazer commit/push dos arquivos novos. O Netlify deverá gerar um novo deploy automaticamente.

Se não gerar:
- Netlify → Deploys → Trigger deploy → Deploy site.

## Importante

Como as abas estão publicadas na Web, não coloque dados pessoais/sensíveis nelas.

Uma turma continua sendo uma linha em TURMAS e pode possuir vários registros em HORARIOS.
