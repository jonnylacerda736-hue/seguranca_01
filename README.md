Atividade de Sala 
Nome:Jonny Lacerda Rodrigues 
Serie: 2 DEV 
Questão 1. Pesquisar um incidente real de ransomware em escolas/órgãos públicos, 
resumir as fases do ataque e listar controles que poderiam ter reduzido o impacto. 
1. O Ataque Ransomware em Baltimore (Maio de 2019) 
O ataque começou em 7 de maio de 2019 e não foi um incidente rápido, mas sim uma crise 
que se arrastou por meses, forçando a cidade a operar de forma arcaica. 
A Tática e a Vítima 
● Vetor de Ataque: Embora não se saiba exatamente como os hackers entraram 
inicialmente, o ransomware usado foi o RobbinHood. Esse malware é notório por 
tentar obter acesso a contas de administrador para se espalhar rapidamente por 
toda a rede. 
● O Sequestro: O ransomware agiu criptografando a maioria dos sistemas de e-mail e 
bancos de dados da cidade, tornando-os inutilizáveis. Os invasores deixaram uma 
nota de resgate exigindo 13 Bitcoins (cerca de US$ 76.280 na época) para fornecer 
a chave de descriptografia. 
Paralisação dos Serviços Essenciais 
Apesar de a polícia e os serviços de emergência (911) terem permanecido operacionais 
(pois usavam sistemas separados), o ataque paralisou a espinha dorsal administrativa da 
cidade: 
Setor Afetado 
Transações 
Imobiliárias 
Contas de Água e 
Esgoto 
Impacto Imediato 
Um dos impactos mais graves. O sistema de transferência de títulos 
e impostos da cidade foi desativado, impedindo a compra e venda 
de casas. 
Os sistemas de faturamento e cobrança foram inutilizados, forçando 
a cidade a parar de enviar contas por meses. Isso criou um enorme 
atraso na receita. 
E-mail 
Governamental 
Sistemas de 
Cobrança 
Milhares de funcionários da prefeitura ficaram incomunicáveis ou 
tiveram que recorrer a contas de e-mail pessoais. 
Os cidadãos não conseguiam pagar impostos prediais, multas de 
estacionamento ou outras taxas online. 
Exportar para as Planilhas 
2. Decisão Crítica e Custo Real 
O prefeito de Baltimore, Bernard C. "Jack" Young, tomou a decisão crucial de não pagar o 
resgate, seguindo a orientação do FBI. 
O Prejuízo Multimilionário 
Enquanto o resgate era de apenas US$ 76 mil, a recusa em pagar resultou em um prejuízo 
muito maior devido à necessidade de reconstruir os sistemas do zero: 
● Custo Direto: A cidade gastou aproximadamente US$ 18 milhões em custos 
diretos de recuperação, incluindo serviços de consultoria em segurança, novo 
hardware e horas extras de funcionários. 
● Perda de Receita: A paralisação dos sistemas de cobrança resultou em uma perda 
significativa de receita pública, estimada em milhões de dólares adicionais. 
● Lição Financeira: Baltimore provou que, embora pagar o resgate seja antiético e 
não garanta a recuperação, não pagar pode ser exponencialmente mais caro se 
a infraestrutura de segurança e backup for fraca. 
O Contexto de Vulnerabilidade 
O ataque não foi um evento isolado. Baltimore foi criticada por ter sistemas 
desatualizados e práticas de segurança deficientes. Os especialistas apontaram que a 
cidade falhou em: 
● Atualizar o Software: Muitos sistemas antigos e não corrigidos (unpatched) eram 
vulneráveis. 
● Isolar Redes: O ransomware conseguiu se espalhar por grande parte da rede 
porque não havia separação adequada entre os diferentes sistemas. 
● Ter Backups Efetivos: Muitos backups não estavam isolados (air-gapped) e 
acabaram sendo criptografados junto com os sistemas principais. 
O incidente de Baltimore se tornou um marco na segurança cibernética municipal, alertando 
governos locais em todo o mundo sobre a necessidade urgente de investimentos em 
cibersegurança e planos de recuperação de desastres. 
Fases do Ataque de Ransomware em Baltimore (2019) 
Fase 1: Invasão e Preparação (Exploração de Vulnerabilidades) 
Esta fase envolveu a entrada dos hackers na rede da cidade, explorando sistemas fracos e 
desatualizados: 
● Vetor de Entrada: Embora não confirmado publicamente, a suposição é que os 
hackers exploraram uma vulnerabilidade ou usaram credenciais roubadas em um 
sistema desatualizado ou não corrigido (unpatched) – um ponto fraco comum em 
ambientes de governo. 
● Movimentação Lateral: Uma vez dentro, os criminosos realizaram a chamada 
"movimentação lateral," mapeando a rede para encontrar os servidores e bancos de 
dados mais cruciais e com maior acesso de administrador. 
● Preparação para o Sequestro: Os hackers provavelmente desativaram os 
programas de segurança da rede e se prepararam para a etapa final, focando em 
sistemas críticos como o de transferência de títulos imobiliários e de cobrança de 
contas de água. 
Fase 2: Execução do Ransomware (Criptografia e Exigência de Resgate) 
Esta é a fase visível do ataque, que ocorreu simultaneamente em toda a rede: 
● Liberação do RobbinHood: O ransomware RobbinHood foi acionado em massa, 
criptografando rapidamente todos os dados nos servidores da cidade, tornando os 
arquivos e sistemas completamente inacessíveis. 
● Paralisação em Massa: Sistemas de e-mail, faturamento, pagamentos de impostos 
e registros imobiliários pararam de funcionar quase que instantaneamente. A cidade 
foi forçada a operar com papel e caneta. 
● Exigência de Resgate: Os hackers deixaram a nota de resgate exigindo 13 
Bitcoins (aproximadamente US$ 76 mil), prometendo a chave de descriptografia em 
troca do pagamento. 
Fase 3: Consequência e Recuperação Prolongada (O Custo da Recusa) 
Esta fase foi a mais longa e cara para a administração pública: 
● Recusa de Pagamento: A liderança da cidade recusou-se a pagar o resgate, 
optando por restaurar os sistemas internamente (a partir de backups e 
reconstrução). 
● Impacto Financeiro: A decisão resultou em um custo de recuperação estimado em 
mais de US$ 18 milhões (mais de 236 vezes o valor do resgate), devido à compra 
de novo hardware, serviços de consultoria e horas extras. 
● Paralisação Contínua: Serviços públicos críticos ficaram indisponíveis por 
meses, criando um enorme backlog (acúmulo) na emissão de contas de água e 
transações imobiliárias, e demonstrando a fragilidade da infraestrutura digital de 
Baltimore. 
Controles que Poderiam Ter Reduzido o Impacto 
O custo e a duração da crise poderiam ter sido drasticamente reduzidos com algumas 
defesas-chave: 
1. Backup 3-2-1: O controle mais importante é ter cópias de segurança isoladas (air
gapped ou imutáveis). Isso garante que a cidade possa restaurar todos os dados 
rapidamente e, assim, ignorar o pedido de resgate com segurança. 
2. Segmentação de Rede: Se a rede tivesse sido dividida em zonas, o ransomware 
teria ficado contido em apenas uma área, impedindo que se espalhasse para todos 
os sistemas críticos simultaneamente. 
3. Gestão de Patches e MFA: A manutenção de todos os sistemas atualizados (com 
patches) eliminaria as vulnerabilidades de entrada. Além disso, exigir a 
Autenticação Multifator (MFA) tornaria credenciais roubadas inúteis. 
4. Plano de Resposta a Incidentes: Ter um plano de emergência testado reduziria o 
tempo de inatividade, transformando a crise de meses em apenas dias ou semanas 
de interrupção.