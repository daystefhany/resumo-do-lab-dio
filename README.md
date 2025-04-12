# resumo-do-lab-dio
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

# DIO | Resumos 

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

## 🖥️ Resumo do Lab: Criando Máquinas Virtuais na Azure
Durante este lab, aprendi os principais conceitos sobre máquinas virtuais na plataforma Microsoft Azure. Mesmo não tendo executado o processo diretamente por falta de conta ativa na Azure, compreendi os passos fundamentais para criar e configurar uma máquina virtual na nuvem, como:
- Acessar o portal [Azure](portal.azure.com);
- Navegar até o recurso de "Máquinas Virtuais";
- SLA é o **acordo de nível de serviço** que define a garantia de disponibilidade que a Azure oferece.
- Aprendi a diferença entre SLAs de **99%, 99,9%, 99,95% e 99,99%**, e como cada um afeta o **tempo de inatividade permitido por semana, mês ou ano**.
- Entendi que **SLAs mais altos** são mais caros, e que em **ambientes de teste** pode-se optar por SLAs menores (ex: 99%) para economizar.
- Saber escolher o SLA ideal depende da **criticidade do serviço** e da **tolerância à indisponibilidade**.

O lab também explicou os diferentes tipos de replicação disponíveis para contas de armazenamento na Azure, cada um com impactos diferentes no **nível de disponibilidade e preço**:
- **LRS (Locally Redundant Storage)**: replicação local em uma única região.
- **GRS (Geo-Redundant Storage)**: replicação entre regiões geograficamente distantes.
- **ZRS (Zone-Redundant Storage)**: replicação entre zonas de disponibilidade.
- **GZRS (Geo-Zone Redundant Storage)**: combinação de replicação geográfica e entre zonas.
- Entendi a diferença entre **grupos de disponibilidade** (alta disponibilidade local) e **zonas de disponibilidade** (em diferentes data centers da mesma região).
- A escolha entre eles também influencia o SLA e o custo final da solução.

## ✅ Conclusão
Esse conteúdo foi essencial para compreender que **a criação de uma máquina virtual na Azure vai muito além de apenas clicar em “criar”**. É necessário avaliar fatores como:
- Qual SLA é mais adequado ao projeto;
- Qual nível de replicação garante a segurança esperada dos dados;
- Como equilibrar **custo vs. desempenho vs. disponibilidade**.
Esse aprendizado é essencial para entender como funciona a infraestrutura em nuvem e como a inteligência artificial pode ser aplicada nesse ambiente, aproveitando o poder de escalabilidade e processamento da cloud computing.


---
Dayane.
---
