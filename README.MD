
# Cálculo da Resolução de um Pluviômetro Automático por báscula

Considere um Pluviômetro tipo copo coletor, com dupla báscula, diâmetro do funil 20cm, a bascula move quando 6 ml caem sobre ela vinda do funil. Vamos encontrar a resolução em mm de chuva para cada movimento da báscula para este diametro.

## Para calcular a resolução em milímetros de chuva por movimento da báscula do pluviômetro, consideraremos a seguinte abordagem:

Área do Funil: O funil do pluviômetro possui um diâmetro de 20 cm, então o raio é r=20cm/2= 10 cm. A área AA do funil em centímetros quadrados é dada pela fórmula da área de um círculo:

<center><img src=https://raw.githubusercontent.com/mchavesferreira/estacaometerologica/refs/heads/main/imagens/formula1.png></center>


Calculando em milímetros quadrados (considerando 1 cm² = 100 mm²), obteremos a área total.

Volume por Basculamento: Cada movimento da báscula ocorre com a coleta de 6 ml (ou 6000 mm³) de água da chuva.

Altura em Milímetros (Resolução): A resolução, ou seja, a altura de chuva em milímetros para cada basculamento, é a relação entre o volume de água e a área do funil, dada por:
   
<center><img src=https://raw.githubusercontent.com/mchavesferreira/estacaometerologica/refs/heads/main/imagens/formula2.png></center>


# Cálculo da Resolução de um Pluviômetro

Este documento explica como calcular a **resolução em milímetros de chuva** por movimento da báscula de um pluviômetro tipo copo coletor. Também são apresentados exemplos com valores para diferentes configurações do funil e volume de basculamento.

---

## Fórmula Geral

A resolução em milímetros de chuva para cada movimento da báscula é calculada pela fórmula:

\\[
\\text{Resolução (mm)} = \\frac{\\text{Volume (mm}^3\\text{)}}{\\text{Área (mm}^2\\text{)}}
\\]

### Onde:
- **Volume**: Volume de água que aciona a báscula (convertido para \\( mm^3 \\)).
- **Área**: Área da seção do funil (convertida para \\( mm^2 \\)).

A área do funil é calculada considerando o diâmetro do funil, pela fórmula:

\\[
A = \\pi \\times r^2
\\]

Com \\( r \\) sendo o raio do funil, obtido pelo diâmetro dividido por 2.

---

## Exemplo 1: Funil com 20 cm de diâmetro e báscula de 6 ml

### Dados:
- **Diâmetro do funil**: 20 cm
- **Volume por basculamento**: 6 ml

### Cálculos:
1. Convertendo o diâmetro para milímetros:
   \\[
   r = \\frac{20 \\times 10}{2} = 100 \\text{ mm}
   \\]

2. Calculando a área do funil em \\( mm^2 \\):
   \\[
   A = \\pi \\times (100)^2 = 31415.93 \\text{ mm}^2
   \\]

3. Convertendo o volume para \\( mm^3 \\):
   \\[
   6 \\text{ ml} = 6 \\times 1000 = 6000 \\text{ mm}^3
   \\]

4. Calculando a resolução:
   \\[
   \\text{Resolução} = \\frac{6000}{31415.93} \\approx 0.191 \\text{ mm}
   \\]

**Resultado**: Cada movimento da báscula corresponde a aproximadamente **0,191 mm de chuva**.

---

## Exemplo 2: Funil com 13,7 cm de diâmetro e báscula de 6,5 ml

### Dados:
- **Diâmetro do funil**: 13,7 cm
- **Volume por basculamento**: 6,5 ml

### Cálculos:
1. Convertendo o diâmetro para milímetros:
   \\[
   r = \\frac{13.7 \\times 10}{2} = 68.5 \\text{ mm}
   \\]

2. Calculando a área do funil em \\( mm^2 \\):
   \\[
   A = \\pi \\times (68.5)^2 \\approx 14748.35 \\text{ mm}^2
   \\]

3. Convertendo o volume para \\( mm^3 \\):
   \\[
   6.5 \\text{ ml} = 6.5 \\times 1000 = 6500 \\text{ mm}^3
   \\]

4. Calculando a resolução:
   \\[
   \\text{Resolução} = \\frac{6500}{14748.35} \\approx 0.441 \\text{ mm}
   \\]

**Resultado**: Cada movimento da báscula corresponde a aproximadamente **0,441 mm de chuva**.

---

## Conclusão

A resolução de um pluviômetro depende do tamanho do funil e do volume necessário para acionar a báscula. Este cálculo é essencial para determinar a precisão da medição de precipitação.

