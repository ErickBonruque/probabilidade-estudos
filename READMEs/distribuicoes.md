# Distribuições Probabilísticas

## Binomial

A distribuição binomial modela o número de sucessos em uma série de tentativas independentes, cada uma com uma probabilidade de sucesso fixa.

### Fórmula:
![Fórmula Binomial](https://latex.codecogs.com/svg.latex?P(X%20%3D%20k)%20%3D%20%5Cbinom%7Bn%7D%7Bk%7D%20%5Ccdot%20p%5Ek%20%5Ccdot%20(1-p)%5E%7Bn-k%7D)

## Geométrica

A distribuição geométrica modela o número de tentativas independentes necessárias para obter o primeiro sucesso em uma série de experimentos Bernoulli.

### Fórmula:
![Fórmula Geométrica](https://latex.codecogs.com/svg.latex?P(X%20%3D%20k)%20%3D%20(1-p)%5E%7Bk-1%7D%20%5Ccdot%20p)

## Pascal (ou Negative Binomial)

A distribuição de Pascal, também conhecida como distribuição binomial negativa, modela o número de tentativas independentes necessárias para obter um número fixo de sucessos em uma série de experimentos Bernoulli.

### Fórmula:
![Fórmula Pascal](https://latex.codecogs.com/svg.latex?P(X%20%3D%20k)%20%3D%20%5Cbinom%7Bk-1%7D%7Br-1%7D%20%5Ccdot%20p%5Er%20%5Ccdot%20(1-p)%5E%7Bk-r%7D)

## Hipergeométrica

A distribuição hipergeométrica modela o número de sucessos em uma amostra de tamanho fixo retirada de uma população finita, sem reposição.

### Fórmula:
![Fórmula Hipergeométrica](https://latex.codecogs.com/svg.latex?P(X%20%3D%20k)%20%3D%20%5Cfrac%7B%5Cbinom%7Ba%7D%7Bk%7D%20%5Ccdot%20%5Cbinom%7Bb%7D%7Bn-k%7D%7D%7B%5Cbinom%7Ba&plus;b%7D%7Bn%7D%7D)

## Poisson

A distribuição de Poisson modela a probabilidade de um número específico de eventos ocorrer em um intervalo fixo de tempo ou espaço, dado uma taxa média de ocorrência desses eventos.

### Fórmula:
![Fórmula de Poisson](https://latex.codecogs.com/svg.latex?P(X%20%3D%20k)%20%3D%20%5Cfrac%7Be%5E%7B-%5Clambda%7D%20%5Clambda%5Ek%7D%7Bk%21%7D)