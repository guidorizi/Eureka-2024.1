# 1. Requisitos Não Funcionais

<p align="justify">A <i>Tabela 2</i> a seguir contém os <b>Requisitos Não Funcionais (RNF)</b> elicitados utizando a técnica de Brainstorm .</p>

| ID   |                                 Requisito NF                              | Categoria/Tipo | Prioridade | Requisitos Relacionados |
| :--: | :-----------------------------------------------------------------------: |:-------------: | :--------: | :-----------------: |
| RNF01 |  O carregamento das páginas deve ser inferior a 2 segundos em condições normais de operação. |Desempenho              |Média       |    RNF12             |
| RNF02 |   O sistema deve ser capaz de suportar até 1.000 usuários simultâneos sem degradação significativa do desempenho. |  Desempenho  |Alta        |    RF8              |
| RNF03 | A plataforma deve realizar backups automáticos diários e permitir a recuperação de dados em caso de falhas.            |  Disponibilidade/Confiabilidade      |Alta      |     -               |
| RNF04 | O sistema deve ser acessível e funcionar corretamente em navegadores modernos (Chrome, Firefox, Edge) e em dispositivos móveis (smartphones e tablets). |   Disponibilidade        |Alta      |    RNF12             |
| RNF05 | O sistema deve permitir que apenas administradores aprovem ou rejeitem anúncios, garantindo que apenas conteúdo aprovado seja exibido. |  Proteção  |Alta        |    RF8              |
| RNF06 |  Implementar um sistema seguro de login e senha para coordenadores, garantindo que apenas usuários autorizados possam postar anúncios. |  Proteção     |Alta      |     RNF05           |

<div style="text-align: center">
<p>Tabela 2: Requisitos Não Funcionais</p>
</div>
