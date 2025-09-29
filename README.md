# 🛡️ Módulo de Governança e Conformidade

Este repositório contém meu resumo do módulo Governança e Conformidade, desenvolvido durante o laboratório da DIO, explorando os principais recursos do Azure voltados para **governança, conformidade e proteção de recursos**, garantindo consistência, segurança e aderência a normas regulatórias.

---

### Azure Policy
Ferramenta que ajuda a **impor padrões organizacionais** e avaliar a conformidade em escala.  
- Fornece governança consistente em áreas como **segurança, custos e monitoramento**.  
- Permite definir **políticas e iniciativas integradas**, aplicáveis a armazenamento, rede, computação, segurança e monitoramento.  
- Avalia os recursos existentes e indica se estão:  
  - **Non-compliant**: não estão em conformidade.  
  - **Remediation**: ajustados automaticamente para se adequar.  
  - **Compliant**: atendem plenamente às regras definidas.  

> Diferente de permissões individuais, a Policy é aplicada para toda a organização, garantindo padrões uniformes.

---

### Bloqueios de Recursos
Protegem contra **exclusão ou modificação acidental**.  
Os bloqueios podem ser aplicados em **níveis diferentes** (assinatura, grupo de recursos ou recurso individual).  

| Tipo de bloqueio | Ler | Atualizar | Excluir |
|------------------|-----|-----------|---------|
| **Excluir**      | Sim | Sim       | Não     |
| **ReadOnly**     | Sim | Não       | Não     |

> Importante: bloqueios são herdados em níveis inferiores, mas não acompanham o recurso se ele for movido de grupo.

---

### Portal de Confiança do Serviço
Local para consultar todas as **regras, políticas e certificações** que a Microsoft segue, oferecendo transparência sobre **conformidade e segurança**.

---

### Microsoft Purview
Família de soluções para **governança, risco e conformidade de dados**, oferecendo uma visão unificada dos dados em ambientes **locais, multinuvem e SaaS**.  
Recursos principais:  
- **Descoberta automatizada** de dados.  
- **Classificação de dados confidenciais**.  
- **Linhagem ponta a ponta** dos dados.  

> Atenção: o Purview não é uma ferramenta de segurança, mas de **governança e gestão de dados**.

---

## Links de Referência
- [Documentação oficial do Azure Policy](https://learn.microsoft.com/azure/governance/policy/overview)  
- [Documentação sobre bloqueios de recursos no Azure](https://learn.microsoft.com/azure/azure-resource-manager/management/lock-resources)  
- [Microsoft Trust Center (Portal de Confiança do Serviço)](https://www.microsoft.com/trust-center)  
- [Microsoft Purview - Documentação oficial](https://learn.microsoft.com/purview/)

---