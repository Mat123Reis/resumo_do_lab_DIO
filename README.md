# resumo_do_lab_DIO
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.

Cloud é um tipo de Serviço que disponibiliza Infraestrutura, Plataformas e Softwares para quem não quer ter estes custos de forma fixa.

Existem 3 tipos de Computação em Nuvem:
1.Nuvem Privada (on-premise)
2.Nuvem Pública (Cloud)
3.Nuvem Híbrida (on-premise + Cloud)

Existem o CapEx e OpEx:
CapEx - Despesas de Capital: Gastos iniciais em infraestrutura, despesas reduzem com o tempo.
OpEx - Despesas Operacionais: Gastos conforme necessário e conforme o uso.

Benefícios da Nuvem:
- Alta disponibilidade
- Previsibilidade
- Elasticidade
- Segurança
- Escalabilidade
- Governança
- Confiabilidade
- Gerenciabilidade

Tipos de Serviço em Nuvem:
- IaaS (Infraestrutura como Serviço)
- PaaS (Plataforma como Serviço)
- Saas (Software como Serviço)
 
Componentes de Arquitetura Azure:
- Regiao: Datacenters que oferecem escala e flexibilidade.
- Zona de disponibilidade: Regiões dentro de regiões, separa fisicamente datacenters dentro da mesma região.
- Pares de regiões: Réplica automática que garante que o serviço continue, caso uma região caia por inteiro.
- Regiões soberanas Azure: Serviços Governamentais dos EUA e Azure China (21Vianet), instância separada do Azure.
- Recursos Azure: Componentes disponiveis para criar soluções de nuvem. Ex.: Armazenamento, MV, Redes virtuais, BD, etc.
- Grupo de Recursos: Conteiner para gerenciar e agregar recursos em uma unidade.
- Assinaturas Azure: Fornece acesso autenticado as contas Azure.
- Grupos de Gerenciamento: Incluem várias assinaturas.

          Grupo de Gerenciamento
                    |
                    V
               Assinaturas
                    |
                    V
            Grupo de Recursos
                    |
                    V
                 Recursos

Computação e Rede: Serviços que fornecem discos, processadores, memória, rede, etc.

Serviços de Conteiners Azure: Fornecem ambiente leve e virtualizado que não exige gerenciamento do Sistema Operacional.
  - Instâncias: PaaS que executa um conteiner ou pod de conteiners.
  - Aplicativos: PaaS como instância d conteiner, que pode balancear a carga e escalar.
  - Serviços de Kubernets: Serviço de orquestração para conteiners com arquiteturas distribuídas e grandes volumes de conteiners.
  - Azure Functions: Oferta de plataforma que dá suporte a operações de computação sem servidor.
  - Serviço de App: Plataforma totalmente gerenciada para criar, implantar e dimensionar apps Web e APIs rapidamente.
  - Serviços de Rede: Criar uma VNet, que permite recursos Azure se comunicarem em redes locais e na Internet.
  - DNS: Nomes das Máquinas Virtuais (VM)

E por fim, os Serviços de Armazenamento e pontos de extremidade:
- Blob: Armazenamento massivo de dados não estruturados. Ex.: Texto e números binários.
- Disco: Disco para VM e Apps.
- Fila: Garante o armazenamento, mas não a ordem de execução.
- Arquivos: Compartilhamento de arquivos (drive local da máquina).
- Tabelas: Tabela com chave e valor atribuido, para armazenar dados estruturados não relacionados.
- Camada de acesso: Existem 4 que são Frequente, Esporádico (30 dias), Frio (90 dias) e Arquivo Morto (180 dias).
- Azure Data Box: Armazena até 80 terabytes de dados.
