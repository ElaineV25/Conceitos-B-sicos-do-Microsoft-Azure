Contas, Recursos e Grupos de Recursos na Azure
A Microsoft Azure organiza seus serviços e estrutura de uso em três níveis principais:

1. 👤 Conta (Subscription)
A conta de assinatura (subscription) é a unidade principal de cobrança e gerenciamento.

É onde você registra seus dados de pagamento e controla o uso da nuvem.

Pode haver múltiplas assinaturas dentro de uma mesma conta Microsoft.

🔹 Exemplos:

Assinatura de teste gratuito

Assinatura paga por consumo

Assinatura do Visual Studio/Aluno

2. 🧱 Recursos (Resources)
Um recurso é qualquer item que você cria ou usa na Azure:

VM, banco de dados, conta de armazenamento, função, etc.

Cada recurso tem um tipo, um nome, uma localização e configurações específicas.

🔸 Exemplo de recursos:

text
Copiar
Editar
- VM Linux (Ubuntu)
- Banco de dados SQL
- App Service (aplicativo web)
3. 🗂️ Grupos de Recursos (Resource Groups)
Um grupo de recursos é um container lógico que agrupa múltiplos recursos relacionados.

Usado para organizar, monitorar, controlar permissões e aplicar políticas.

Todos os recursos em um grupo devem pertencer à mesma assinatura, mas podem estar em regiões diferentes.

🔹 Boas práticas:

Agrupar recursos do mesmo sistema/projeto

Usar nomes claros (ex: rg-sistema-financeiro)

Facilita a exclusão e gerenciamento em lote

🎯 Relação entre eles
text
Copiar
Editar
Conta (Subscription)
└── Grupo de Recursos (Resource Group)
    ├── Máquina Virtual
    ├── Banco de Dados
    └── Storage Account
🔐 Permissões e controle
Você pode aplicar políticas e permissões por grupo de recursos, usando o Azure RBAC.

Isso facilita a delegação de acesso para times específicos.

🧠 Dica prática
Sempre pense no grupo de recursos como a "pasta do projeto" onde você guarda tudo relacionado àquela aplicação ou ambiente.

🔗 Leitura complementar
Visão geral de recursos na Azure

O que é uma assinatura?

