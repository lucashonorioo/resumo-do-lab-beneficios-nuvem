# Resumo do Lab Beneficios da Nuvem



Os benefícios da computação em nuvem, como os oferecidos pelo Microsoft Azure, são diversos e impactam diretamente na agilidade, escalabilidade e eficiência da infraestrutura de TI. 
No entanto, antes de implantar qualquer serviço na nuvem, é fundamental entender alguns conceitos importantes, como o SLA.
O SLA (Acordo de Nível de Serviço) determina o tempo mínimo de disponibilidade garantido para cada serviço contratado, com valores como 99%, 99,9% ou até 99,999%. Esses números indicam o tempo máximo de inatividade aceitável por semana, mês ou ano. 
No entanto, é importante compreender que esse valor não é uma previsão de falha, e sim um limite contratual. Caso o serviço fique inativo por um tempo superior ao estabelecido no SLA, o cliente pode ter direito a um ressarcimento proporcional ao tempo excedido.
Ao criar uma máquina virtual no Azure, a plataforma facilita o preenchimento das informações por meio de ícones de ajuda (representados por um “i”), que exibem um resumo sobre cada item e fornecem links para documentação detalhada. Isso garante mais segurança para o usuário na hora de configurar sua máquina corretamente.
Outro aspecto essencial na nuvem é a replicação de dados. No Azure, as contas de armazenamento podem adotar diferentes estratégias de redundância, como:
•	LRS (Locally Redundant Storage)
•	ZRS (Zone-Redundant Storage)
•	GRS (Geo-Redundant Storage)
•	GZRS (Geo-Zone-Redundant Storage)
Cada uma dessas estratégias impacta diretamente no SLA e nos custos. 
Quanto maior a redundância (ou seja, a replicação dos dados em múltiplas regiões ou zonas), maior a disponibilidade garantida, mas também maior o custo. Por isso, o planejamento prévio é essencial para equilibrar resiliência, desempenho e orçamento.
