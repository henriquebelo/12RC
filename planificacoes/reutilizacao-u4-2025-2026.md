# Reutilização da Unidade 4 de Redes de Comunicação 2025/2026

Análise de 13 de setembro de 2026. Destino: Redes de Comunicação, 12.º ano, 2026/2027.

Origem: https://moodle.csmiguel.pt/course/section.php?id=9611

## Conclusão

A antiga Unidade 4 — Protocolos da Camada de Aplicação reúne materiais relevantes para várias unidades da nova planificação. Reutilizar conceitos, cenários e sequências de trabalho, adaptando-os aos objetivos atuais e às aulas de 2 horas. Não importar a unidade inteira como uma nova U4: a atual U4 centra-se em SSH/SFTP e integração segura de serviços.

## Mapa de reutilização

| Origem | Destino | Adaptação proposta |
|---|---|---|
| Livro Modelos de Referência (41227) e trabalho OSI/TCP/IP (41228) | U1 | Revisão breve associada ao percurso de um pedido e ao diagnóstico; substituir a apresentação extensa por esquema comentado e explicação individual. |
| Livro Conceitos sobre configurações de rede e serviços (41229) | U1–U4 | Distribuir os capítulos pelas aulas; rever terminologia, exemplos e ferramentas antes de converter em páginas curtas. |
| Laboratório 2 — Packet Tracer (41232) | U2 e U3; revisão na U1 | Reutilizar router, switch, servidor e dez clientes. Desenvolver DHCP e DNS na U2, HTTP na U3; acrescentar HTTPS em ambiente apropriado, falhas controladas e interpretação de evidências. |
| Laboratório 3 — Rede Escolar (41233) | U5/U6; exercícios selecionados na U1 | Usar a rede com salas como cenário fictício de planeamento. Rever endereçamento, separar segmentos, explicitar encaminhamento e critérios de aceitação. Não apresentar a simulação como configuração atual da escola. |
| Laboratório 4 — Rede IoT (42447) | U5 | Aproveitar registo de dispositivos e controlo de estados. Acrescentar sensores, regras de automatização, segmentação e testes de falha. |
| Laboratório 5 — Configuração de Rede em Linux (41234) | U1 e preparação da U2 | Reutilizar configuração estática/dinâmica e testes, com ambiente Linux definido e evidências antes/depois. |
| Laboratório 6 — Servidor FTP (41235) | U4 | Aproveitar sequência instalar/configurar/utilizadores/testar e transformar o laboratório principal em SSH/SFTP. Manter FTP apenas na comparação prevista na planificação. |
| Laboratório 7 — Servidor Web Linux (41237) | U3 | Desenvolver o objetivo de criar um guião de instalação com HTTP/HTTPS, certificados, permissões, registos e diagnóstico. O texto consultado contém sobretudo objetivos, não um guião completo. |
| Laboratório 8 — ZimaOS (42577), OpenMediaVault (41254) | Complemento possível da U4/U6 | Exploração opcional de integração e documentação. Confirmar pertinência, requisitos e versões na preparação da aula. Não substituir os serviços nucleares da planificação. |
| Diário de bordo sobre IA (42123) | Transversal | Candidato a adaptação para registar apoio recebido, verificação, alterações e explicação própria. Perguntas do inquérito ainda por analisar. |

## Revisões identificadas no texto consultado

- O capítulo de endereço IP apresenta IPv4 como a versão atual do IP. Reescrever para contemplar IPv4 e IPv6, articulando com a dupla pilha prevista.
- O livro e o laboratório escolar usam classes de endereços. Ensinar prefixos/CIDR como base de configuração e conservar classes apenas como contexto histórico.
- O laboratório Packet Tracer usa um nome terminado em `.local`. Rever o exemplo para evitar confusão com o uso especial deste sufixo em mDNS.
- O objetivo inicial do laboratório Packet Tracer parece atribuir gateway ao servidor; a lista de equipamentos e os passos atribuem essa função ao router. Tornar a descrição coerente.
- Rever os capítulos de DNS, portas e ferramentas: existem simplificações e exemplos associados a interfaces antigas. Validar os comandos na distribuição e versão escolhidas para o laboratório.
- No trabalho OSI/TCP/IP, verificar a apresentação histórica da ISO e corrigir a designação da organização.
- Os enunciados contêm datas e grupos do ano anterior. Nas novas versões, usar apenas o conteúdo pedagógico, sem nomes de alunos, submissões, notas ou calendários antigos.
- Reorganizar a recolha de evidências: configuração, resultado esperado, teste realizado, interpretação, correção e reteste. Capturas de ecrã devem apoiar a explicação, não substituí-la.

Referências técnicas verificadas: [IPv6, RFC 8200](https://www.rfc-editor.org/info/rfc8200/), [CIDR, RFC 4632](https://www.rfc-editor.org/info/rfc4632/), [Multicast DNS, RFC 6762](https://www.rfc-editor.org/info/rfc6762/).

## Prioridade para preparação das próximas aulas

1. U1: selecionar conceitos do livro e o cenário Linux para exercícios de configuração, rotas e resolução de nomes, mantendo a progressão das aulas já preparadas.
2. U2: desenvolver o cenário integrado do laboratório Packet Tracer em etapas de DHCP, DNS e falhas deliberadas.
3. U3/U4: reaproveitar o formato dos guiões de instalação, acrescentando segurança, verificação e recuperação.
4. U5/U6: retomar os cenários IoT e rede escolar como bases para projetos com decisões justificadas.

Modelo indicativo de aula de 2 horas: 15 min de diagnóstico/revisão, 20 min de teoria e demonstração, 60 min de prática, 15 min de testes e evidências, 10 min de síntese individual. Ajustar à aula concreta.

## Alcance da análise

Consultados: inventário da Unidade 4, texto dos enunciados OSI/TCP/IP e laboratórios 1–8, capítulos textuais dos modelos de referência e uma seleção dos capítulos do livro de configurações e serviços.

Os ficheiros anexos (incluindo guiões DHCP/router/FTP, planta IoT e Workshop 3D), imagens incorporadas, perguntas dos testes e do diário de bordo não foram integralmente inspecionados. A reutilização destes elementos fica dependente dessa revisão. O Laboratório 1 não apresentou enunciado textual no conteúdo acessível da atividade.

Não foram importados conteúdos nem alteradas as disciplinas nesta análise. Este documento é um registo local de apoio à preparação futura.
