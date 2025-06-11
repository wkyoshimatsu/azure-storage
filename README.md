# Resumo sobre Armazenamento e Banco de Dados no Azure - Certificação AZ-900

Este documento contém um resumo dos principais conceitos sobre **Armazenamento e Banco de Dados no Azure** com foco na certificação Microsoft Azure Fundamentals (AZ-900).

## 📌 Comparação dos Serviços de Armazenamento do Azure
O **Azure Storage** oferece diversas opções para armazenar e gerenciar dados na nuvem. Os principais serviços incluem:

- **Armazenamento de Blobs:** Ideal para armazenar grandes volumes de dados não estruturados, como imagens e vídeos.
- **Arquivos do Azure:** Compartilhamento de arquivos na nuvem com suporte ao protocolo SMB.
- **Discos Gerenciados:** Armazenamento de discos virtuais para máquinas virtuais.
- **Azure Data Lake Storage:** Otimizado para análise de Big Data.
- **Filas do Azure:** Gerenciamento de mensagens entre componentes distribuídos.

## 🔄 Camadas de Armazenamento
O Azure Storage oferece diferentes camadas para otimizar custos e desempenho:

- **Camada Hot:** Para dados acessados frequentemente.
- **Camada Cool:** Para dados acessados ocasionalmente.
- **Camada Archive:** Para armazenamento de longo prazo com acesso esporádico.

## 🔒 Opções de Redundância
O Azure Storage garante alta disponibilidade e proteção contra falhas com diferentes opções de redundância:

- **LRS (Locally Redundant Storage):** Dados replicados dentro de um único datacenter.
- **ZRS (Zone Redundant Storage):** Replicação entre diferentes zonas de disponibilidade.
- **GRS (Geo-Redundant Storage):** Replicação entre regiões geográficas.
- **RA-GRS (Read-Access Geo-Redundant Storage):** Versão do GRS com acesso de leitura.

## 🏢 Tipos de Conta de Armazenamento
O Azure oferece diferentes tipos de contas de armazenamento:

- **Uso Geral v2:** Suporta todos os serviços de armazenamento do Azure.
- **Blobs Premium:** Para cargas de trabalho que exigem baixa latência.
- **Arquivos Premium:** Para compartilhamento de arquivos de alto desempenho.

## 🚀 Opções para Mover Arquivos
O Azure disponibiliza ferramentas para transferência de arquivos:

- **AzCopy:** Ferramenta de linha de comando para copiar dados entre contas de armazenamento.
- **Gerenciador de Armazenamento do Azure:** Interface gráfica para gerenciar e transferir arquivos.
- **Sincronização de Arquivos do Azure:** Sincroniza arquivos entre servidores locais e a nuvem.

## 🔄 Opções de Migração
Para migrar dados para o Azure, existem diversas soluções:

- **Azure Migrate:** Plataforma unificada para migração de servidores e bancos de dados.
- **Azure Data Box:** Dispositivos físicos para transferir grandes volumes de dados para o Azure.

## ⚙️ Configuração de uma Instância de Banco de Dados no Azure
Para criar uma **Instância Gerenciada do Azure SQL**, siga os passos abaixo:

1. **Acesse o Portal do Azure** e faça login.
2. **Pesquise por "Instância Gerenciada do Azure SQL"** e selecione o serviço.
3. **Clique em "Criar"** e configure os detalhes:
   - Nome da instância
   - Grupo de recursos
   - Região
   - Tipo de autenticação
4. **Configuração de rede:** Defina regras de firewall e conectividade.
5. **Clique em "Examinar + Criar"** e depois em "Criar".
6. **Após a implantação**, conecte-se à instância via **SQL Server Management Studio (SSMS)** ou **Azure Data Studio**.

## 🎯 Recursos úteis para certificação AZ-900
- [Microsoft Learn - Curso Oficial](https://learn.microsoft.com/pt-br/certifications/azure-fundamentals/)
- [Documentação do Azure](https://learn.microsoft.com/pt-br/azure/)
- [Simulados e materiais de apoio](https://www.examtopics.com/exams/microsoft/az-900/)

📌 **Última atualização:** Junho de 2025.
