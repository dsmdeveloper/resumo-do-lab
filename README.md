# O que eh Nuvem?
A definição de nuvem, na computação, é o fornecimento de serviços de computação pela internet, incluindo servidores, armazenamento, bancos de dados, redes, software e análise. Esses recursos são oferecidos sob demanda, com flexibilidade para acessar, usar e escalar conforme a necessidade, sem a necessidade de manter infraestrutura física própria. Essa entrega de recursos via internet permite reduzir custos, acelerar inovações e adaptabilidade das empresas
Em termos simples, a nuvem é um conjunto de servidores remotos conectados pela internet que hospedam e processam dados e aplicações, acessíveis a qualquer momento e lugar, eliminando a necessidade de hardware local.

# Tipos de Nuvem
Os três tipos de nuvem são:

- **Nuvem Pública:** Ambiente compartilhado oferecido por provedores como Azure, onde recursos são usados sob demanda e pagos conforme o uso. É escalável, econômica, e gerenciada pelo provedor. Ideal para organizações que precisam de flexibilidade e baixo custo.
    
- **Nuvem Privada:** Infraestrutura dedicada exclusiva para uma organização, podendo estar no próprio data center ou hospedada. Oferece maior controle, segurança e customização, mas geralmente com custo maior e manutenção própria.
    
- **Nuvem Híbrida:** Combina nuvem pública e privada, permitindo mover dados e aplicações entre elas conforme necessidade. Equilibra flexibilidade, custo e segurança, ideal para organizações que precisam de controle e escalabilidade.
    

## Comparação entre Nuvem Pública, Privada e Híbrida - KPTs (Keep, Problem, Try) e Opts (Oportunidades)

|Aspecto|Nuvem Pública|Nuvem Privada|Nuvem Híbrida|
|---|---|---|---|
|**Keep (Vantagens)**|Baixo custo, alta escalabilidade e flexibilidade|Segurança e controle total da infraestrutura|Flexibilidade para balancear segurança e custo|
|**Problem (Desafios)**|Menor controle e riscos com multiusuários|Custo elevado e necessidade de equipe técnica|Complexidade de gerenciamento e integração|
|**Try (Melhorias)**|Melhorar controle e segurança|Otimizar custos e simplificar manutenção|Automatização e integração avançada|
|**Oportunidades**|Rápida implementação e inovação|Conformidade com normas rígidas e alta segurança|Equilíbrio entre performance, segurança e custo|

Essa comparação ajuda na escolha dependendo do foco da empresa: custo e agilidade (pública), segurança e controle (privada) ou flexibilidade e combinação das duas (híbrida).

# CapEx e OpEx
CapEx (Capital Expenditure) são os gastos de capital, investimentos iniciais altos para comprar ativos físicos como servidores e infraestrutura, típicos de nuvens privadas ou datacenters on-premises. Já OpEx (Operational Expenditure) são despesas operacionais pagas conforme o uso, típicas de nuvens públicas, onde não há grande investimento inicial, mas custo contínuo mensal ou por consumo.

## Comparação CapEx vs OpEx na nuvem

|Aspecto|CapEx|OpEx|
|---|---|---|
|Natureza do gasto|Investimento fixo e grande|Despesa variável, paga conforme o uso|
|Exemplos|Compra de servidores, infraestrutura própria|Serviços em nuvem, software como serviço (SaaS)|
|Impacto financeiro|Alto custo inicial, depreciável|Custo operacional, custo previsível e flexível|
|Flexibilidade|Baixa, difícil ajustar rapidamente|Alta, permite escalar conforme demanda|
|Manutenção|Requer equipe e custo interno|Suporte e manutenção são responsabilidade do provedor|
|Indicado para|Ambientes com necessidade de controle e segurança|Projetos que precisam de agilidade e escalabilidade|

Na prática, nuvem privada tende a ser mais CapEx, enquanto a pública é mais OpEx, e a nuvem híbrida mistura esses modelos para balancear investimentos e custos operacionais conforme a necessidade

# Vantagens da Nuvem

## Escalabilidade

**Escalabilidade** é a capacidade de um sistema, software ou infraestrutura tecnológica de crescer ou reduzir de forma eficiente, mantendo desempenho e qualidade mesmo com aumento de carga, usuários ou dados. Em outras palavras, um sistema escalável consegue adaptar recursos conforme a demanda, sem travar ou perder eficiência.

Na prática, escalabilidade pode ser:

- **Vertical:** aumentar recursos de um único servidor (CPU, memória).
    
- **Horizontal:** adicionar mais servidores ou instâncias para distribuir a carga.
    
Na nuvem, escalabilidade é um benefício central, permitindo expandir (ou reduzir) recursos rapidamente e pagar apenas pelo que realmente é usado, trazendo flexibilidade e economia para empresas.

## Elasticidade

Na nuvem é possível escalar automaticamente os recursos de acordo com a quantidade de acessos e depois reduzir quando a demanda cai. Esse ajuste dinâmico, chamado de elasticidade, permite aumentar servidores, processadores ou memória sempre que há muitos acessos e, em seguida, diminuir recursos quando o tráfego volta ao normal, evitando custos desnecessários.

Essa escalabilidade automática garante boa performance e economia, sendo útil, por exemplo, para sites que recebem picos de visitas em datas específicas (como Black Friday) e depois retornam ao volume regular de acessos. Tudo isso pode ser configurado para acontecer sem intervenção manual, utilizando serviços de autoescalonamento disponíveis em plataformas como Azure e AWS.

## Confiabilidade

Confiabilidade na nuvem é a capacidade de um serviço, sistema ou aplicação de funcionar de forma estável e previsível, garantindo disponibilidade e acesso aos dados sempre que necessário. Esse conceito envolve minimizar falhas, evitar quedas e garantir que recursos estejam disponíveis mesmo diante de problemas como picos de uso ou falhas de hardware.

Na prática, a confiabilidade em nuvem se alcança por meio de:

- Redundância de infraestrutura (vários servidores/data centers).
    
- Estratégias de backup e recuperação de desastres.
    
- Monitoramento contínuo e automação para detectar e corrigir falhas rapidamente.
    
- SLAs com altos índices de disponibilidade, garantindo que os serviços fiquem acessíveis na maior parte do tempo.
    
Provedores de nuvem investem fortemente para entregar alta confiabilidade, o que é essencial para empresas que dependem dos serviços digitais estarem sempre ativos.

## Previsibilidade

Previsibilidade, na nuvem, é a capacidade de antever e controlar o desempenho e os custos dos serviços utilizados, evitando surpresas e permitindo um planejamento financeiro e operacional mais eficiente.

No contexto de custos, a previsibilidade significa saber com clareza quanto será gasto e como as variações de uso afetam a fatura, usando ferramentas de monitoramento e políticas de governança. Já na parte técnica, está ligada à confiança de que os recursos contratados estarão disponíveis e terão performance estável, mesmo com variações de demanda, graças a mecanismos como autoescalonamento e SLAs.

A previsibilidade na nuvem, portanto, traz segurança para avançar com projetos, controlar orçamentos e garantir a experiência dos usuários sem imprevistos.

## Segurança

A segurança na nuvem envolve um conjunto de práticas, tecnologias e políticas para proteger dados, aplicações e infraestrutura contra ameaças, acessos não autorizados e ataques cibernéticos. Para isso, são utilizadas ferramentas como criptografia, autenticação multifator, controle de acesso, monitoramento contínuo e backups automáticos.

Os principais pilares da segurança em nuvem são:

- **Proteção de dados:** Uso de criptografia e backup para garantir que dados estejam seguros, tanto em trânsito quanto em repouso.
    
- **Gestão de identidade e acesso:** Restringir quem pode acessar o quê, usando autenticação forte, permissões específicas e revisão constante de acessos.
    
- **Monitoramento e resposta a ameaças:** Vigilância contínua para detectar, responder e corrigir rapidamente qualquer atividade suspeita ou incidente.
    
- **Conformidade e políticas:** Atender normas de privacidade e regulamentação (como LGPD) e aplicar políticas de segurança alinhadas ao negócio.
    
A segurança em nuvem é uma responsabilidade compartilhada: o provedor garante a segurança da infraestrutura, enquanto o cliente é responsável pela proteção dos dados e a configuração correta dos acessos.

## Governança

Governança na nuvem é o conjunto de políticas, processos e controles que garantem o uso seguro, eficiente e alinhado aos objetivos da empresa dos recursos de computação em nuvem. Ela define regras para gerenciar segurança, custos, conformidade legal, acesso a dados e riscos, assegurando que todos os usuários e equipes trabalhem de forma coordenada e responsável.

Essa governança ajuda a:

- Controlar gastos e evitar desperdício.
    
- Garantir segurança e conformidade com normas.
    
- Monitorar uso e desempenho dos serviços.
    
- Definir responsabilidades para gestão e acesso.
    
- Facilitar a inovação sem comprometer o orçamento ou a segurança.
    
Portanto, a governança é essencial para escalar e administrar ambientes de nuvem com eficiência, especialmente em ambientes híbridos ou multicloud.

## Gerenciabilidade

Gerenciabilidade na nuvem é a capacidade de controlar, supervisionar e administrar os recursos, serviços e aplicações que rodam em ambientes de nuvem. Esse gerenciamento envolve o provisionamento, monitoramento, orquestração, segurança, conformidade e otimização de custos para garantir que tudo funcione de forma eficiente e alinhada aos objetivos da organização.

Envolve ferramentas e processos que permitem:

- Provisionar recursos automaticamente e conforme demanda.
    
- Monitorar o desempenho e a saúde dos serviços.
    
- Controlar o uso e gastos, evitando desperdício.
    
- Garantir conformidade com políticas e segurança.
    
- Automatizar operações para reduzir falhas humanas e agilizar processos.
    

Assim, a gerenciabilidade é essencial para manter o controle, a visibilidade e a eficiência em ambientes de nuvem, especialmente quando a infraestrutura é complexa ou distribuída.

## IaaS, PaaS e SaaS

são três modelos principais de serviços em nuvem que oferecem diferentes níveis de controle, flexibilidade e gerenciamento:

- **IaaS (Infraestrutura como Serviço):** Disponibiliza recursos básicos de infraestrutura, como servidores, armazenamento e rede, que o usuário pode configurar e gerenciar conforme a necessidade. O provedor cuida do hardware e da virtualização, mas o cliente administra sistema operacional, aplicações e dados. Exemplo: máquinas virtuais no Azure, AWS EC2.
    
- **PaaS (Plataforma como Serviço):** Fornece um ambiente completo para desenvolver, testar e gerenciar aplicativos sem precisar cuidar da infraestrutura ou middleware. Ideal para desenvolvedores, que podem focar no código, enquanto o provedor mantém o ambiente. Exemplo: Azure App Service, Heroku.
    
- **SaaS (Software como Serviço):** Oferece aplicações prontas para uso, acessadas via navegador ou app, gerenciadas totalmente pelo provedor, incluindo atualizações e manutenção. O usuário apenas utiliza o software sem se preocupar com infraestrutura ou desenvolvimento. Exemplo: Microsoft 365, Gmail.
    

## Comparação IaaS, PaaS e SaaS

|Característica|IaaS|PaaS|SaaS|
|---|---|---|---|
|Nível de controle|Alto (infraestrutura e software)|Médio (aplicações e dados)|Baixo (aplicações prontas)|
|Público-alvo|Equipes de TI / Administradores|Desenvolvedores|Usuários finais|
|Responsabilidade|Usuário gerencia sistemas, apps|Usuário desenvolve apps; provedor gerencia infraestrutura|Provedor gerencia tudo|
|Flexibilidade|Maior personalização e controle|Foco no desenvolvimento ágil|Facilidade e rapidez de uso|
|Exemplos|Azure VMs, AWS EC2|Azure App Service, Heroku|Microsoft 365, Google Workspace|

Esses modelos ajudam empresas a escolher o nível de gerenciamento e infraestrutura que desejam delegar ao provedor, indo de infraestrutura pura (IaaS) à aplicação completa pronta para uso (SaaS).

## Modelo de Responsabilidade Compartilhada

O **Modelo de Responsabilidade Compartilhada** na nuvem é uma estrutura que define claramente as responsabilidades de segurança e gerenciamento entre o provedor de serviços de nuvem (CSP) e o cliente.

## Como funciona:

- O **provedor** é responsável pela segurança da infraestrutura física, data centers, hardware, rede e virtualização — ou seja, tudo "da nuvem".
    
- O **cliente** é responsável por proteger seus dados, identidade, aplicativos, sistemas operacionais, configurações e acesso — ou seja, tudo "na nuvem".
    

Essa divisão varia conforme o tipo de serviço:

- **SaaS:** o provedor gerencia quase tudo, o cliente cuida do controle de acesso e dados.
    
- **PaaS:** o provedor gerencia a plataforma, o cliente gerencia aplicativos e dados.
    
- **IaaS:** o provedor gerencia a infraestrutura, o cliente gerencia sistemas operacionais, aplicativos e dados.    

### Componentes de arquitetura do Azure

Esta fonte detalha a estrutura física (Regiões/Zonas) e lógica (Hierarquia) do Azure.

| Conceito | Detalhes Principais | Citação |
| :--- | :--- | :--- |
| **Regiões** | Locais onde os recursos são criados. São pontos em azul escuro no mapa global. Existem mais de 60 regiões ativas em mais de 140 países (abrangência global). | |
| **Regiões Anunciadas** | Estão quase prontas para se tornarem disponíveis (pontilhados no mapa). | |
| **Escolha de Região** | Influencia o **acesso** (proximidade do usuário reduz o *delay* ou lentidão) e o **preço** (não é tabelado, devido a impostos e tipo de recurso). | |
| **Disponibilidade de Recursos** | Nem todos os recursos estão disponíveis em todas as regiões, especialmente aqueles em *preview* (teste). | |
| **Região vs. Data Center (DC)** | Uma região é composta por um ou mais data centers. Recomenda-se a ideia de **três data centers por região** para caracterizar uma Zona de Disponibilidade. | |
| **Zona de Disponibilidade (ZA)** | É um data center (bloco autossustentável). Os DCs se comunicam por uma rede exclusiva de alta performance (backbone da Microsoft) e baixa latência. | |
| **Replicação** | Para garantir alta disponibilidade, os recursos são copiados ao mesmo tempo (escrita ativa) para os três DCs de uma região. | |
| **Falha de DC** | Se um DC ficar indisponível, os outros dois respondem, mantendo o sistema funcional (embora possa haver lentidão). Se os três DCs (região) ficarem fora, é necessário o *Disaster Recovery* (DR) para outra região. | |
| **Residência dos Dados** | As regiões preservam a residência dos dados (conformidade como LGPD). A Microsoft garante que a informação não será movida, pois a informação pertence ao cliente. | |
| **Redundância Interna** | É possível configurar a aplicação para estar em diferentes *racks* (gavetas/servidores) dentro do mesmo DC para proteção contra falhas locais (ex: energia). | |
| **Recomendação de Estudo** | É crucial usar uma conta *trial* para fazer laboratórios e praticar, pois o ambiente de nuvem está em constante mudança. | |

***

### Entendendo Pares de Regiao e grupos de Recursos

Este trecho explora a continuidade das regiões (Pares e Soberanas) e a organização dos recursos.

| Conceito | Detalhes Principais | Citação |
| :--- | :--- | :--- |
| **Pares de Região** | Cada região possui uma **região par** que funciona como zona secundária para a região original. | |
| **Disaster Recovery (DR)** | Utiliza a região par para manter o ambiente ativo em outro lugar, reduzindo o tempo de inatividade em caso de interrupção da região principal. O SLA de DR é variável. | |
| **Replicação de Pares** | Pode ser automática para alguns serviços. As atualizações do Azure são distribuídas sequencialmente entre as regiões pares para minimizar o *downtime*. | |
| **Exemplo Brasil** | A região Sul do Brasil replica para o Centro Sul dos Estados Unidos. A região Centro (RJ) ainda não é considerada região de DR para replicação total da principal (São Paulo). | |
| **Regiões Soberanas** | Regiões exclusivas, não acessíveis para clientes normais (ex: China e EUA Governamental). | |
| **Azure Governamental (EUA)** | Exclusiva para a área militar e agências governamentais/estaduais dos EUA. É fisicamente separada das implantações públicas. | |
| **Azure China** | Separada fisicamente. É operada pela empresa **21 Vianet**. Os dados permanecem na China por critérios de conformidade. | |
| **Recursos** | Itens que podem ser criados no Azure, como máquinas virtuais, armazenamento e redes. | |
| **Grupo de Recursos (RG)** | Mecanismo de **organização** dos recursos, agregando-os em uma única unidade ("caixinha"). | |
| **Conteúdo do RG** | Agrupa um recurso principal e todos os subcomponentes associados (IP, disco, placa de rede, etc.). | |
| **Regras do RG** | 1. O recurso só pode estar em **um RG** por vez. 2. RGs não podem ser renomeados. 3. Recursos podem ser movidos para outro RG, inclusive entre assinaturas. 4. Recursos de um RG podem estar em **regiões diferentes**. | |
| **Uso de RG** | Estratégia de organização pode ser por projeto (Projeto X) ou por tipo de item (apenas Máquinas Virtuais). É importante definir uma organização que faça sentido para a aplicação de regras e políticas. | |

***

### Assinatura da Azure e Grupos de Gerenciamento

Esta fonte aborda a estrutura lógica acima dos Grupos de Recursos, focando em Faturamento e Hierarquia.

| Conceito | Detalhes Principais | Citação |
| :--- | :--- | :--- |
| **Assinatura Azure** | Fornece **acesso autenticado e autorização** para usar o Azure. | |
| **Hierarquia Conta vs. Assinatura** | Uma **Conta** (o dono) pode ter **várias assinaturas**. Uma **Assinatura** só pode responder a **uma única conta**. | |
| **Cobrança (Biling)** | Cada assinatura gera uma fatura separada. A separação por assinaturas é uma estratégia usada para **organizar e refinar custos** por projeto ou centro de custo. | |
| **Controle de Acesso** | Usar assinaturas diferentes ajuda a controlar o acesso, garantindo que usuários (ex: pessoal de teste) só tenham permissão onde for necessário. A segurança (permissões) é responsabilidade do cliente. | |
| **Grupos de Gerenciamento (Management Groups)** | Entidade que atua acima das assinaturas, usada para aplicar as mesmas regras, padrões, permissões ou políticas a **múltiplas assinaturas** simultaneamente. | |
| **Hierarquia Completa** | Grupos de Gerenciamento > Assinaturas > Grupos de Recursos > Recursos. | |
| **Herança** | Assinaturas incluídas em um Grupo de Gerenciamento herdam as condições (regras, permissionamentos) definidas neste grupo. | |
| **Propósito** | Essencial para organização, segurança e padronização, especialmente em ambientes grandes com muitas assinaturas. | |

***
