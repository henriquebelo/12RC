# U1 Diagnóstico de rede e revisão de endereçamento

Carga de referência: 8 aulas no primeiro semestre. As três primeiras aulas abaixo iniciam a unidade; as restantes serão desenvolvidas progressivamente. Cada aula tem 2 h.

## Aula 01 Ler e representar uma configuração

1. O que sabemos antes de alterar? Sintoma, hipótese e teste.
2. Ler IPv4, máscara, gateway e DNS. Tabela de parâmetros e pertença à rede.
3. Reconhecer IPv6 e dupla pilha. Expansão, prefixo e âmbito.
4. Desenhar o percurso de um pedido. DNS, encaminhamento e serviço.
5. Construir a ficha da rede. Endereços coerentes, topologia e testes esperados.

Produto: ficha de configuração fundamentada. Cada etapa recolhe uma resposta individual e exige submissão final.

## Aula 02 Diagnosticar por evidências

1. Escolher o próximo teste. Sequência e limites de cada ferramenta.
2. Incidente de endereçamento. Comparação entre plano e configuração.
3. Incidente de rota. Distinguir comunicação local e entre redes.
4. Incidente de resolução de nomes. Comparar resposta DNS e plano.
5. Relatório e transferência. Síntese dos três incidentes e novo caso de serviço.

Produto: relatório com sintoma, evidência, hipótese, teste, correção e reteste. Os cenários podem ser analisados documentalmente; distinguir resultados esperados de testes executados. A montagem real em laboratório será adaptada ao ambiente confirmado pelo professor.

## Aula 03 Observar, configurar e testar uma rede em Ubuntu

Duração: **2 h**. Ambiente confirmado: máquina virtual Ubuntu.

| Etapa | Minutos |
|---|---:|
| 01 — Ler a configuração do Ubuntu | 20 |
| 02 — Prever a comunicação local | 20 |
| 03 — Configurar e testar a ligação | 35 |
| 04 — Diagnosticar uma falha de prefixo | 25 |
| 05 — Explicar e transferir o diagnóstico | 20 |

Produto: evidências da configuração e relatório antes/durante/depois da falha de prefixo. Preparação: duas VMs por rede virtual interna isolada, VM A sem outras rotas IPv4 e VM B em 192.168.10.150/24 com ICMP funcional; interface de laboratório disponível para configuração temporária. Confirmar a montagem antes da aula.

Reutilização: objetivos de configuração de interfaces e conectividade do Laboratório 5 de RC 2025/2026; novo guião, sem dados ou trabalhos de antigos alunos.

## Continuidade

As aulas seguintes deverão retomar TCP/IP, IPv4/IPv6, rotas, nomes, segmentação e privilégios mínimos, incluindo a execução dos incidentes no laboratório, explicação individual, feedback e recuperação. Não dar a U1 por concluída apenas com a análise destes cenários.
