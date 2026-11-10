# Skills gratuitas para o Claude

Ferramentas de IA prontas para usar no Claude, criadas por **Filipe | Dados e IA** ([@filipe.dadoseia](https://www.instagram.com/filipe.dadoseia/)).

Skills são pacotes com instruções e scripts que o Claude executa para fazer uma tarefa do começo ao fim, do mesmo jeito sempre.

| Skill | O que faz | Onde roda | Download |
|---|---|---|---|
| **Copiloto Financeiro** | Lê o extrato do banco (CSV, OFX, PDF ou print), categoriza os gastos com regras que aprendem com você e gera o painel do mês com orçamento, metas e alertas. | Qualquer plano do Claude, inclusive o gratuito | [copiloto-financeiro.zip](https://github.com/fp-costa91/skills/raw/main/copiloto-financeiro.zip) |
| **Editor de Reels** | Transforma takes gravados no celular em um Reel pronto: escolhe o melhor take, corta pausas, legenda com destaque, b-roll e áudio no padrão das redes. | App desktop do Claude ou Claude Code (precisa de ffmpeg e Python) | [editor-de-reels.zip](https://github.com/fp-costa91/skills/raw/main/editor-de-reels.zip) |
| **Relatório automático** | Transforma uma planilha em relatório executivo em PDF, com indicadores, gráficos, alertas e uma análise escrita como a de um analista. Pode enviar por e-mail. | Qualquer plano do Claude com execução de código | [relatorio-automatico.zip](https://github.com/fp-costa91/skills/raw/main/relatorio-automatico.zip) |
| **Painel interativo** | Transforma qualquer planilha num painel interativo em um único arquivo HTML: filtros, indicadores vs período anterior, gráfico que explica a variação e detalhe ao passar o mouse. Sem Power BI nem ferramenta paga. | Qualquer plano do Claude com execução de código | [painel-interativo.zip](https://github.com/fp-costa91/skills/raw/main/painel-interativo.zip) |

## Como instalar

1. Baixe o `.zip` da skill (não precisa descompactar).
2. No Claude (site ou app): **Personalizar → Skills → "+" → Criar skill → Enviar uma skill** e escolha o arquivo.
3. Em **Configurações → Capacidades**, deixe ativada a execução de código e criação de arquivos.
4. Numa conversa nova, peça a tarefa. Ex.: "faz meu check-in do mês" com o extrato anexado.

No **Claude Code**, descompacte a pasta em `~/.claude/skills/`.

## Avisos

- O Copiloto Financeiro é uma ferramenta de organização e educação financeira, **não é recomendação de investimento**.
- Não envie senhas nem números completos de cartão ou conta para nenhuma IA.
- Uso livre para fins pessoais. Quer uma versão feita para a sua empresa? Me chama no direct: [@filipe.dadoseia](https://www.instagram.com/filipe.dadoseia/).
