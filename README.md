# Politicas-em-Acessos-Azure
Gerenciando Politicas em Acessos Azure

Artigo: Explorando a Segurança e Conformidade no Azure: Fundamentos e Práticas

O uso do Azure como plataforma de nuvem permite uma gestão robusta de segurança, privacidade e conformidade. Nesta aula, foram abordados tópicos essenciais sobre políticas de segurança, ferramentas de compliance e recursos disponíveis na plataforma. Aqui estão os principais conceitos e práticas discutidas:

1. Porta de Confiança no Azure
A Porta de Confiança no Azure é um conceito central que garante que todos os serviços e dados sejam protegidos de acordo com os mais rigorosos padrões de segurança. A Microsoft implementa uma série de frameworks e certificações de segurança, como ISO, SOC, RGPD (Regulamento Geral de Proteção de Dados da UE), entre outros.
A segurança no Azure envolve um conjunto abrangente de proteções, garantindo que dados e operações sigam conformidades internacionais como a FedRAMP (Federal Risk and Authorization Management Program), para instituições federais dos EUA.

2. Bloqueio de Recurso e Organização de Resource Groups
Ao usar o Azure, é possível proteger recursos sensíveis com a funcionalidade de Resource Locks, que impede alterações acidentais. Uma vez ativado, o bloqueio evita a exclusão ou modificação de recursos críticos.
Mover recursos para outro Resource Group também é uma prática recomendada quando se deseja reorganizar o ambiente sem impactar a segurança. Isso permite melhor controle e gestão do ambiente de TI.

3. Microsoft Purview: Uma Visão Centralizada da Governança de Dados
A criação de uma conta no Microsoft Purview oferece acesso a uma poderosa ferramenta de governança e conformidade de dados. O Purview permite a centralização de informações sobre dados armazenados, facilitando a gestão e auditoria.
O novo portal do Purview no Microsoft Preview integra várias plataformas da organização, como Office 365, Azure, Microsoft Fabric, e até mesmo outras plataformas de nuvem, oferecendo uma visão unificada de conformidade.

4. Funcionalidades do Purview: Data Map, Data Catalog e Proteção de Informação
O Purview oferece funcionalidades avançadas para a catalogação de dados, criação de um mapa de dados e proteção de informações. Isso possibilita identificar onde os dados estão armazenados, classificá-los conforme seu tipo e aplicar políticas de proteção adequadas.
A ferramenta de auditoria e configuração permite monitorar o acesso e as mudanças nos dados, garantindo que estejam alinhados com políticas de segurança e compliance.

5. Gerenciamento de Risco e Compliance no Azure
O Azure fornece uma série de ferramentas para gestão de risco e conformidade, com foco em comunicação efetiva, auditorias e gerenciamento de compliance. A plataforma oferece suporte a eDiscovery, barreiras de informações e controles de acesso, garantindo que informações confidenciais permaneçam protegidas.
Recursos de privacidade, como os oferecidos pelo Microsoft Purview Privacy, permitem gerenciar a privacidade dos dados e proteger informações sensíveis contra acessos não autorizados.

6. Políticas de Segurança no Azure
O Azure permite criar e gerenciar políticas de segurança por meio de um Policy Manager. É possível definir políticas de segurança específicas, como locais permitidos para recursos (Allowed Locations) e configurar regras granulares para adequação às necessidades da organização.
Além de utilizar políticas pré-definidas, o Azure também oferece a possibilidade de criar políticas personalizadas, adaptadas às exigências específicas do ambiente de TI da organização.

7. Uso de Tags no Azure
As tags são uma ferramenta poderosa para organizar e gerenciar recursos no Azure. Elas permitem aplicar rótulos a diferentes recursos, facilitando a identificação e a aplicação de políticas específicas.
O uso de tags simplifica a administração e a visualização de grupos de recursos, além de possibilitar a implementação de políticas de forma granular.
