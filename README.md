# 🛡️ Incidente de Ransomware em Baltimore (Maio de 2019)

**Aluno:** Jonny Lacerda Rodrigues  
**Série:** 2º Desenvolvimento de Sistemas  
**Atividade:** Pesquisa — Incidente Real de Ransomware em Escolas/Órgãos Públicos  

---

## 📅 Contexto Geral

Em **7 de maio de 2019**, a cidade de **Baltimore (EUA)** sofreu um **ataque de ransomware** devastador. O malware utilizado foi o **RobbinHood**, que sequestrou dados e paralisou boa parte dos sistemas públicos municipais.  
O incidente se tornou um **marco mundial** na segurança cibernética de governos locais, destacando as consequências da falta de atualizações e planos de contingência.

---

## 🧠 Tática e Vítima

- **Vetor de Ataque:** Não confirmado, mas acredita-se que os invasores exploraram vulnerabilidades em sistemas desatualizados ou credenciais roubadas.  
- **Malware Utilizado:** Ransomware **RobbinHood**, conhecido por buscar privilégios de administrador e criptografar redes inteiras.  
- **Valor do Resgate:** 13 Bitcoins (≈ **US$ 76.280** na época).  

---

## 🚨 Impacto Imediato

| Setor Afetado | Efeito Principal |
|----------------|------------------|
| **Transações Imobiliárias** | Paralisação completa do sistema de registro e impostos, impedindo compra e venda de imóveis. |
| **Contas de Água e Esgoto** | Cobrança suspensa por meses, gerando grande perda de receita. |
| **E-mail Governamental** | Milhares de servidores e contas ficaram inacessíveis, obrigando o uso de e-mails pessoais. |
| **Sistemas de Cobrança** | Cidadãos não conseguiam pagar impostos, multas e taxas online. |

Apesar disso, os sistemas de **emergência (911)** permaneceram funcionais por estarem em rede separada.

---

## 💰 Custo e Decisão

O prefeito **Bernard C. “Jack” Young** recusou o pagamento do resgate, seguindo orientação do FBI.  
Embora o valor exigido fosse relativamente baixo, o custo real foi **muito maior**:

- **Custo direto:** ≈ **US$ 18 milhões** (consultoria, novos equipamentos, horas extras, etc.)  
- **Perda de receita:** milhões adicionais pela interrupção da arrecadação.  
- **Conclusão:** A decisão de não pagar foi ética, mas revelou falhas graves em **infraestrutura e backups**.

---

## 🧩 Fases do Ataque

### 🕵️ Fase 1 — Invasão e Preparação
- Exploração de vulnerabilidades em sistemas **sem atualização (unpatched)**.  
- **Movimentação lateral** dos invasores dentro da rede, buscando servidores críticos.  
- **Desativação** de proteções antes da execução do ransomware.

### 💣 Fase 2 — Execução do Ransomware
- O **RobbinHood** foi ativado em massa, **criptografando dados** e **inutilizando** servidores.  
- Serviços públicos pararam instantaneamente; a cidade voltou ao uso de **papel e caneta**.  
- Foi deixada uma **nota de resgate** exigindo pagamento em Bitcoin.

### 🧰 Fase 3 — Recuperação e Consequências
- **Recusa de pagamento** e reconstrução dos sistemas a partir do zero.  
- **Meses de paralisação** e custo elevado de reconstrução.  
- Falta de um **plano de resposta a incidentes** agravou o impacto.

---

## 🔐 Controles que Poderiam Reduzir o Impacto

| Controle | Descrição | Benefício |
|-----------|------------|------------|
| **Backup 3-2-1** | 3 cópias, 2 tipos de mídia, 1 isolada (air gap). | Permite recuperação rápida sem pagar resgate. |
| **Segmentação de Rede** | Dividir a rede em zonas isoladas. | Impede propagação do ransomware entre setores. |
| **Gestão de Patches e MFA** | Manter sistemas atualizados e usar autenticação multifator. | Reduz vulnerabilidades e invalida credenciais roubadas. |
| **Plano de Resposta a Incidentes** | Procedimentos e simulações de ataque. | Minimiza tempo de inatividade e custos de recuperação. |

---

## 🧾 Conclusão

O **ataque a Baltimore** mostrou que:
- A **negligência em manutenção e backups** pode custar milhões.  
- **Não pagar o resgate** é o caminho certo, mas exige **resiliência e preparo**.  
- **Governos e escolas** devem investir em **cibersegurança preventiva** e **planos de continuidade de negócio**.

---

> 💬 *“A segurança cibernética não é gasto — é investimento em continuidade e confiança pública.”*
