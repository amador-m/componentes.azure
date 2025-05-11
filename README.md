# Componentes Arquiteturais do Microsoft Azure

## Objetivo Geral
Este repositório tem como objetivo explorar os componentes fundamentais da arquitetura do **Microsoft Azure**, abordando sua infraestrutura física, organização de recursos e modelos de gerenciamento.

## Conteúdo Abordado
- Regiões, pares de regiões e regiões soberanas do Azure.
- Zonas de disponibilidade e datacenters do Azure.
- Recursos e grupos de recursos do Azure.
- Assinaturas e grupos de gerenciamento.
- Hierarquia de grupos de recursos, assinaturas e grupos de gerenciamento.

---

## Infraestrutura Física do Azure
### Regiões do Azure
As **regiões do Azure** são áreas geográficas que contêm datacenters. Cada região oferece suporte a serviços específicos e permite escolher a localização ideal para maior desempenho e conformidade regulatória.

- **Pares de Regiões**: Cada região tem um par correspondente para replicação de dados, garantindo **recuperação de desastres**.
- **Regiões Soberanas**: Algumas regiões são dedicadas a governos e organizações que exigem isolamento de dados, como **Azure Government** e **Azure China**.

### Zonas de Disponibilidade
- São áreas dentro de uma região com infraestrutura redundante.
- Garantem alta disponibilidade ao proteger serviços contra falhas em datacenters específicos.
- Compostas por vários datacenters independentes, proporcionando tolerância a falhas.

---

## Organização de Recursos no Azure
### Recursos e Grupos de Recursos
Um **recurso** no Azure pode ser um servidor virtual, banco de dados, aplicativo ou qualquer outro serviço. Esses recursos são organizados em **grupos de recursos**, facilitando o gerenciamento, monitoramento e controle de custos.

- **Grupos de Recursos**: Conjunto de recursos organizados logicamente para facilitar administração e segurança.
- **Gerenciamento de Permissões**: Uso do **Azure Role-Based Access Control (RBAC)** para definir quem pode modificar cada grupo de recursos.

### Assinaturas e Grupos de Gerenciamento
A **hierarquia de gerenciamento no Azure** segue uma estrutura que facilita controle e governança:

1. **Assinatura do Azure** – Representa um contrato de serviço com a Microsoft, permitindo acesso a recursos.
2. **Grupos de Gerenciamento** – Facilitam o gerenciamento de várias assinaturas, aplicando políticas e controles centralizados.

---

## Recapitulando
Os principais conceitos explorados incluem:
- Como **as regiões e pares de regiões** garantem segurança e desempenho global.
- A importância das **zonas de disponibilidade** para garantir continuidade de serviço.
- Organização e hierarquia dos recursos no Azure para **gerenciamento eficiente**.
- Estrutura de assinaturas e grupos de gerenciamento, permitindo **controle centralizado**.
