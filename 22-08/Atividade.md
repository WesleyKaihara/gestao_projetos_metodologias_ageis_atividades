**1. Liste três estratégias de mitigação que podem ser aplicadas a riscos técnicos em um projeto de software. Explique como cada estratégia funciona para reduzir a probabilidade ou impacto do risco.**

    1 . Utilizar tecnologias de maior segurança: possuindo umas infra estrutura melhor, as chances do sistema apresentar falhas por causa dela é diminuida 
    
    2. Utilizar redundâncias: Possuindo backup de servidores e redes (internet), o perigo do sistema parar por mal funcionamento é quase anulado

    3. Monitoramento do sistema: Uma equipe qualificada para monitorar se as princípais funcionalidades do sistema estão funcionando, e caso ocorra algum problema, eles consigam arrumar de imediato


2 . Suponha que você esteja liderando um projeto de desenvolvimento de um aplicativo móvel. Liste pelo menos cinco possíveis riscos específicos relacionados a esse projeto. Categorize-os em riscos técnicos, riscos de prazo e riscos de recursos.


    ## Técnicos
    - Compatibilidade de sistemas;
    - Desempenho em aparelhos desatualizados;

    ## Prazo
    - Atraso no desenvolvimento;
    - Alteração de escopo;
    - Tempo para um teste de qualidade;

    ## Recursos
    - Desordem no time de desenvolvimento;
    - Falta de dispositivos para os testes adequados;

3. Caso de Estudo: Considere um projeto de desenvolvimento de um sistema de gerenciamento de inventário para uma empresa de varejo. Identifique os seguintes elementos:
    
        Um sistema de gerencimento de inventário para uma empresa de varejo tem como principal objetivo facilitar a visualização de itens para os usuários, deixando as principais informações como Nome dos produtos, valores e quantidade em estoque, também criando as devidas validações para evitar problemas de logistica e controle.
        Os principais pontos a serem entregues devem estar relacionados ao controle de itens, ou seja, devem ser construidas funcionalidades de listagem, registro, atualização e remoção dos itens da empresa. Também deve ser pensado como irá funcionar os níveis de acesso e formas de login, por se tratar de aplicação com informações sensiveis é necesário realizar as devidas verificações.
        Os principais interessados para a aplicação serão os responsáveis pelo controle dos itens da empresa, com uma ferramenta que possui como principal objeto organizar seu trabalho, o rendimento e qualidade irão aumentar. Os gerentes e possivel investidores também são impactados a partir do momento que possuem melhor controle das movimentações, percas e possíveis fraudes na empresa

**4. Identificação de Riscos: Utilize uma técnica de identificação de riscos, como brainstorming, para listar pelo menos oito riscos que podem afetar o projeto. Certifique-se de considerar riscos relacionados a tecnologia, recursos humanos, prazos e requisitos.**
**5. Avaliação de Riscos: Classifique os riscos identificados com base em sua probabilidade de ocorrência e impacto no projeto. Use uma escala de 1 a 5 para cada dimensão e calcule a pontuação total de risco para cada um.**

| CATEGORIA        | RISCO                                                     | PROBABILIDADE | IMPACTO | PRIORIDADE |
| ---------------- | --------------------------------------------------------- | ------------- | ------- | ---------- |
| Tecnologia       | Falha de segurança                                        | 2             | 5       | 5          |
| tecnologia       | Falha na verificação de quantidade                        | 2             | 5       | 5          |
| tecnologia       | Apontamento incorreto dos produtos                        | 1             | 3       | 3          |
| tecnologia       | conflito entre amarzenamento e cadastro                   | 4             | 4       | 4          |
| recursos humanos | Cadastramento incorreto de produtos e valores             | 5             | 4       | 4          |
| recursos humanos | Integração de funcionários                                | 5             | 5       | 5          |
| prazo            | falta de conhecimento da equipe                           | 3             | 4       | 4          |
| prazo            | Alterações do escopo durante o desenvolvimento do sistema | 1             | 2       | 2          |

**6. Plano de Mitigação: Selecione três dos riscos mais críticos e desenvolva um plano de mitigação para cada um. Descreva as ações específicas que você tomaria para reduzir a probabilidade ou impacto desses riscos.**

    Integração de funcionários: Fornecimento de treinamentos especificos para o utilização do novo sistema.

    Alterações do escopo durante o desenvolvimento do sistema: Planejamento bem consolidado desde o começo do projeto, visando sempre o futuro do software

    Falha de segurança: Adicinar sistemas ant-bots, e verificações de duas etapas.

**7. Comunicação de Riscos: Escreva um comunicado para a equipe do projeto e os stakeholders principais, destacando os riscos identificados e as estratégias de mitigação planejadas. Explique por que esses riscos são importantes e como a equipe está trabalhando para enfrentá-los.**

    O gerencimento correto dos itens do inventário da empresa efetam diretamente a vida e o trabalho dos membros da equipe. Com falhas de segurança, onde os usuário possuem acesso indevido a esse sistema a probabilidade de afetar diretamente o bem estar de cada membro e lucros da empresa é grande. Também podem ser ocasionados falhas e percas por meio de registros realizados de forma incorreta, o que pode resultar em grandes prejuizos para a empresa. Com uma equipe qualificada, por meio de treinamentos ou uma boa relação, os riscos que envolvem falha de operação são reduzidos, isso também afeta os tópicos sobre a segurança e acesso de terceiros, visto que devem ser aplicadas boas práticas para proteger as credenciais. Além disso, a equipe de desenvolvimento também pode realizar implementações de baixo nível para proteger contra ataques que envolvem a segurança da aplicação e da empresa

