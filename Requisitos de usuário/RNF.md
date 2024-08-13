# 1. Requisitos Não Funcionais

<p align="justify">A <i>Tabela 2</i> a seguir contém os <b>Requisitos Não Funcionais (RNF)</b> elicitados utizando a técnica de Brainstorm .</p>

| ID   |                                 Requisito NF                              | Categoria/Tipo | Prioridade | Requisitos Relacionados |
| :--: | :-----------------------------------------------------------------------: |:-------------: | :--------: | :-----------------: |
| RNF01 |  O carregamento das páginas deve ser inferior a 2 segundos em condições normais de operação. |Desempenho              |Média       |    RNF08             |
| RNF02 |   O sistema deve ser capaz de suportar até 1.000 usuários simultâneos sem degradação significativa do desempenho. |  Desempenho  |Alta        |   -           |
| RNF03 | A plataforma deve realizar backups automáticos diários e permitir a recuperação de dados em caso de falhas.            |  Disponibilidade/Confiabilidade      |Alta      |     -               |
| RNF04 | O sistema deve ser acessível e funcionar corretamente em navegadores modernos (Chrome, Firefox, Edge) e em dispositivos móveis (smartphones e tablets). |   Portabilidade      |Alta      |    -             |
| RNF05 | O sistema deve permitir que apenas administradores aprovem ou rejeitem anúncios, garantindo que apenas conteúdo aprovado seja exibido. |  Proteção  |Alta        |    RNF06              |
| RNF06 |  Implementar um sistema seguro de login e senha para coordenadores, garantindo que apenas usuários autorizados possam postar anúncios. |  Proteção     |Alta      |     RNF05           |
| RNF07 |Deve haver ajuda contextual e orientações para cada seção do sistema.|  Portabilidade       |Média      |     RNF04          |
| RNF08 |A exibição de anúncios deve ser atualizada em tempo real para refletir as aprovações recentes.| Desempenho      |Média      |     RNF01          |

<div style="text-align: center">
<p>Tabela 2: Requisitos Não Funcionais</p>
</div>
