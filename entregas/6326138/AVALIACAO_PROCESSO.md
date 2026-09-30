# Ficha de Avaliação de Processo (PDD) — Questão 5

> MOLDE. Copie para `entregas/SEU_RA/` e preencha. Escolha **um** cenário (A ou B).

**Cenário escolhido:** A

1. **Nome do processo e descrição resumida:**
   Renomeaçao e arquivamento de comprovantes, o processo consiste em organizar diariamente arquivos PDF, renomeando-os e movendo-os para pastas especificas com base na data e no numero do documento presentes no nome original do arquivo

2. **Volume / frequência estimados:**
   Frequencia diaria o volume tende a ser alto por se tratar de rotina de arquivamento de comprovantes, tornando o trabalho manual bastante repetitivo

3. **As entradas são estruturadas?** (sim/nao + justificativa)
   Sim, os dados necessarios (data e numero do documento) já vêm no próprio nome do arquivo PDF de forma padronizada, permitindo facil extraçao via código (como manipulação de strings ou Regex)

4. **As regras são claras e determinísticas?** (sim/nao + justificativa)
   Sim. Existe uma regra logica e fixa para a nova nomenclatura baseada nos dados lidos, nao ha ambiguidades, exceçoes complexas ou necessidade de julgamento e interpretação humana

5. **Veredito — o processo é elegível a RPA?** (justifique com base em regras claras, dados estruturados e repetibilidade)
   Elegivel, o processo se encaixa perfeitamente nos pilares de viabilidade para RPA: possui alta repetibilidade (diario/alto volume), consome entradas de dados totalmente estruturadas e funciona sob regras 100% claras e determinísticas, sem margem para decisões subjetivas
