# t-student

### O que é o t de Student?

O **t de Student** é uma distribuição de probabilidade usada para fazer inferências estatísticas sobre a média de uma população, especialmente quando a **amostra é pequena** (geralmente \( n < 30 \)) e o desvio padrão da população não é conhecido.

### Para que serve o t de Student?

A distribuição t de Student é usada principalmente em **testes de hipóteses** e na **construção de intervalos de confiança** quando se trabalha com amostras pequenas. Ela é uma ferramenta fundamental em estatísticas inferenciais, e seu uso está relacionado a situações em que o tamanho da amostra é limitado ou o desvio padrão da população é desconhecido.

#### Principais usos do t de Student:

1. **Testes de Hipóteses para a Média**:
   - O teste t é utilizado para verificar se a média de uma amostra é significativamente diferente de um valor específico ou de outra média. 
   - Exemplos de testes incluem:
     - **Teste t unilateral**: Para verificar se a média de uma amostra é maior ou menor que a média da população (ou de outro grupo).
     - **Teste t bilateral**: Para verificar se a média da amostra é diferente da média da população, sem especificar se será maior ou menor.

2. **Construção de Intervalos de Confiança**:
   - O t de Student é usado para calcular intervalos de confiança em torno da média amostral quando o tamanho da amostra é pequeno ou o desvio padrão é desconhecido. 
   - O intervalo de confiança ajuda a estimar o intervalo no qual a verdadeira média da população provavelmente se encontra.


### Diferença entre o t de Student e a distribuição normal (z-score)

A distribuição t de Student é usada quando:
- **Tamanho da amostra é pequeno** (tipicamente \( n < 30 \)).
- **Desvio padrão da população é desconhecido**.

A distribuição **normal** (usada para o z-score) é usada quando:
- O **tamanho da amostra é grande** (geralmente \( n > 30 \)).
- O desvio padrão da **população é conhecido**.

### **Case: Avaliação de um novo medicamento**

Suponha que sejamos pesquisadores que estão avaliando um novo medicamento para reduzir a pressão arterial. Temos um grupo de 10 pacientes e desejamos testar se o novo medicamento reduz a pressão arterial média em relação à pressão arterial normal.

A pressão arterial média de uma população saudável (sem o medicamento) é conhecida e é de **120 mmHg**. Temos a amostra de 10 pacientes que tomaram o medicamento, e mediu sua pressão arterial após 30 dias de uso.

#### Passos do estudo:

1. **Formular as hipóteses:**

Queremos testar se o medicamento **reduziu** a pressão arterial média dos pacientes. Suas hipóteses são:

- **Hipótese nula (H₀)**: O medicamento **não tem efeito**, ou seja, a pressão arterial média é **120 mmHg**.

  H₀ = 120 

- **Hipótese alternativa (H₁)**: O medicamento **reduziu** a pressão arterial média, ou seja, a média é **menor** que 120 mmHg.

  H₁ < 120 
