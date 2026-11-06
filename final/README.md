# SIGAP — Sistema de Gestão de Indicadores de Saúde da Atenção Primária

Protótipo navegável desenvolvido para a disciplina **Projeto Integrador I** — Profa. Silvia Garcia.

Versão final. Nesta etapa o acesso é restrito à **coordenação da unidade**.

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
| 9 | Autenticação e trilha de auditoria | Acesso e auditoria |

## Escopo de acesso

A implantação foi planejada em duas fases. Na **fase 1**, representada neste protótipo, apenas a coordenação da unidade acessa o sistema. A decisão reduz a superfície de exposição do dado pessoal sensível enquanto a solução é validada na rotina de trabalho e simplifica a operação inicial.

A estrutura de perfis permanece prevista no projeto: confirmado o ganho operacional, a **fase 2** libera acesso à equipe de saúde e aos agentes comunitários, estes últimos restritos à própria microárea, sem necessidade de reescrever o sistema.

## Como usar

Abra o link e clique em **Entrar** — e-mail e senha já vêm preenchidos para demonstração.

A classificação das pacientes é calculada em tempo real. Alterar a faixa etária ou a janela em **Regra do indicador** reclassifica toda a base imediatamente. Registrar uma mamografia na ficha da paciente a retira da lista de pendências.

## Observações

- Todos os dados são fictícios. Nenhuma informação real de paciente foi utilizada.
- As alterações feitas durante a navegação não são gravadas e voltam ao estado inicial ao recarregar a página.
- Protótipo em página única, sem dependências externas além das fontes.
- Toda ação realizada na navegação é gravada na trilha de auditoria, visível em **Acesso e auditoria**.
