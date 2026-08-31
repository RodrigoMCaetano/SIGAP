# SIGAP — Sistema de Gestão de Indicadores de Saúde da Atenção Primária

Protótipo navegável desenvolvido para a disciplina **Projeto Integrador I** — Profa. Silvia Garcia.

**Acesse o protótipo:** https://rodrigomcaetano.github.io/SIGAP/

## Integrantes

- Rodrigo Gabriel Marques Caetano
- Pedro Renato da Silva Proença

## Instituição analisada

USF Veranice Costa Tatino — Itapetininga/SP

## Problema

O acompanhamento de pacientes com pendências nos indicadores de saúde é feito manualmente por planilha. O sistema oficial registra as consultas, mas não sinaliza com clareza quem está pendente, o que atrasa a identificação e o contato com as pacientes e compromete as metas de desempenho vinculadas ao repasse de recursos federais.

## Solução proposta

Transformar o dado agregado por equipe, que as ferramentas oficiais já entregam, em uma **lista individual e acionável** de pacientes a contatar. O escopo inicial é o indicador de prevenção do câncer de mama.

## Funcionalidades do protótipo

| # | Funcionalidade | Onde ver |
|---|---|---|
| 1 | Cadastro de pacientes e importação de planilha | Pacientes |
| 2 | Registro de exames | Ficha da paciente |
| 3 | Regra do indicador parametrizável | Regra do indicador |
| 4 | Lista de pendências filtrável e priorizada | Pendências |
| 5 | Registro de contato com a paciente | Botão "Contato" |
| 6 | Histórico unificado de exames e contatos | Ficha da paciente |
| 7 | Painel de metas e cobertura | Painel / Metas |
| 8 | Exportação em CSV e impressão da lista | Pendências |
| 9 | Perfis de acesso e trilha de auditoria | Usuários e auditoria |

## Como usar

Abra o link, escolha um dos quatro perfis na tela de entrada e clique em **Entrar**. A senha já vem preenchida. O perfil selecionado altera os itens de menu disponíveis.

A classificação das pacientes é calculada em tempo real. Alterar a faixa etária ou a janela em **Regra do indicador** reclassifica toda a base imediatamente.

## Observações

- Todos os dados são fictícios. Nenhuma informação real de paciente foi utilizada.
- As alterações feitas durante a navegação não são gravadas e voltam ao estado inicial ao recarregar a página.
- Protótipo em página única, sem dependências externas além das fontes.
