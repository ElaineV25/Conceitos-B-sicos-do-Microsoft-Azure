Estrutura Global da Microsoft Azure
A estrutura global da Azure é composta por data centers interconectados mundialmente, organizados em três níveis principais:

🧱 1. Regiões (Regions)
Uma região é um conjunto de data centers implantados em uma localização geográfica específica.

Exemplo: Brazil South (São Paulo), East US, West Europe.

Cada região oferece redundância local e serviços próximos do usuário final.

🧩 2. Zonas de Disponibilidade (Availability Zones)
São zonas físicas separadas dentro de uma mesma região.

Garantem alta disponibilidade em caso de falhas de energia, rede ou resfriamento.

Cada zona é independente, mas interconectada com baixa latência.

Disponível apenas em algumas regiões.

🛡️ 3. Pares de Regiões (Region Pairs)
A Azure organiza as regiões em pares (Region Pairs) dentro do mesmo continente.

Utilizados para:

Recuperação de desastres

Failover automático

Atualizações planejadas sem indisponibilidade global

Exemplo: Brazil South ↔ South Central US

🛰️ 4. Rede global da Azure
A infraestrutura é conectada por uma rede backbone de alta velocidade.

Utiliza fibras ópticas privadas da Microsoft (não depende da internet pública).

Reduz latência e melhora desempenho de serviços distribuídos.

🌐 Resumo visual
less
Copiar
Editar
Continente
 └── Região (ex: Brazil South)
     ├── Zona 1
     ├── Zona 2
     └── Zona 3
✅ Benefícios da estrutura global
Alta disponibilidade e tolerância a falhas

Menor latência para usuários globais

Backup e replicação entre regiões

Conformidade com leis de soberania de dados (ex: LGPD)

🔗 Recursos
Lista de Regiões Azure

Status da infraestrutura Azure

