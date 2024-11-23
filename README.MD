
# Cálculo da Resolução de um Pluviômetro Automático por báscula

Considere um Pluviômetro tipo copo coletor, com dupla báscula, diâmetro do funil 20cm, a bascula move quando 6 ml caem sobre ela vinda do funil. Vamos encontrar a resolução em mm de chuva para cada movimento da báscula para este diametro.

## Para calcular a resolução em milímetros de chuva por movimento da báscula do pluviômetro, consideraremos a seguinte abordagem:

Área do Funil: O funil do pluviômetro possui um diâmetro de 20 cm, então o raio é r=20cm/2= 10 cm. A área AA do funil em centímetros quadrados é dada pela fórmula da área de um círculo:

<center><img src=https://raw.githubusercontent.com/mchavesferreira/estacaometerologica/refs/heads/main/imagens/formula1.png></center>


Calculando em milímetros quadrados (considerando 1 cm² = 100 mm²), obteremos a área total.

Volume por Basculamento: Cada movimento da báscula ocorre com a coleta de 6 ml (ou 6000 mm³) de água da chuva.

Altura em Milímetros (Resolução): A resolução, ou seja, a altura de chuva em milímetros para cada basculamento, é a relação entre o volume de água e a área do funil, dada por:
   
<center><img src=https://raw.githubusercontent.com/mchavesferreira/estacaometerologica/refs/heads/main/imagens/formula2.png></center>


## Fórmula Geral



A resolução em milímetros de chuva para cada movimento da báscula é calculada por:



`Resolução (mm) = Volume (mm³) / Área (mm²)`



### Componentes:

- **Volume**: O volume de água que aciona a báscula, em mm³ (1 ml = 1000 mm³).

- **Área**: A área da seção do funil, em mm².



A área do funil é calculada considerando o diâmetro do funil:



`Área = π × r²`



onde:

- `r`: Raio do funil (metade do diâmetro).



---



## Exemplo 1: Funil com 20 cm de diâmetro e báscula de 6 ml



### Dados:

- **Diâmetro do funil**: 20 cm

- **Volume por basculamento**: 6 ml



### Cálculos:

1. **Convertendo o diâmetro para milímetros**:

   `r = (20 × 10) / 2 = 100 mm`



2. **Calculando a área do funil**:

   `Área = π × (100)² ≈ 31415.93 mm²`



3. **Convertendo o volume para milímetros cúbicos**:

   `6 ml = 6 × 1000 = 6000 mm³`



4. **Calculando a resolução**:

   `Resolução = 6000 / 31415.93 ≈ 0.191 mm`



**Resultado**: Cada movimento da báscula corresponde a aproximadamente **0,191 mm de chuva**.



---



## Exemplo 2: Funil com 13,7 cm de diâmetro e báscula de 6,5 ml



### Dados:

- **Diâmetro do funil**: 13,7 cm

- **Volume por basculamento**: 6,5 ml



### Cálculos:

1. **Convertendo o diâmetro para milímetros**:

   `r = (13.7 × 10) / 2 = 68.5 mm`



2. **Calculando a área do funil**:

   `Área = π × (68.5)² ≈ 14748.35 mm²`



3. **Convertendo o volume para milímetros cúbicos**:

   `6.5 ml = 6.5 × 1000 = 6500 mm³`



4. **Calculando a resolução**:

   `Resolução = 6500 / 14748.35 ≈ 0.441 mm`



**Resultado**: Cada movimento da báscula corresponde a aproximadamente **0,441 mm de chuva**.



---



## Conclusão



A resolução de um pluviômetro depende do tamanho do funil e do volume necessário para acionar a báscula. Este cálculo é essencial para determinar a precisão da medição de precipitação.



