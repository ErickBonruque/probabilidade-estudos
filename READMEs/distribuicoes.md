<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fórmulas com Texto em Branco</title>
</head>
<body>

<h1>Distribuições Probabilísticas</h1>

<h2>Binomial</h2>
<p>A distribuição binomial modela o número de sucessos em uma série de tentativas independentes, cada uma com uma probabilidade de sucesso fixa.</p>
<h3>Fórmula:</h3>
<p><img src="https://latex.codecogs.com/svg.latex?P(X%20%3D%20k)%20%3D%20%5Cbinom%7Bn%7D%7Bk%7D%20%5Ccdot%20p%5Ek%20%5Ccdot%20(1-p)%5E%7Bn-k%7D" style="filter: brightness(0) invert(1);"></p>

<h2>Geométrica</h2>
<p>A distribuição geométrica modela o número de tentativas independentes necessárias para obter o primeiro sucesso em uma série de experimentos Bernoulli.</p>
<h3>Fórmula:</h3>
<p><img src="https://latex.codecogs.com/svg.latex?P(X%20%3D%20k)%20%3D%20(1-p)%5E%7Bk-1%7D%20%5Ccdot%20p" style="filter: brightness(0) invert(1);"></p>

<h2>Pascal (ou Negative Binomial)</h2>
<p>A distribuição de Pascal, também conhecida como distribuição binomial negativa, modela o número de tentativas independentes necessárias para obter um número fixo de sucessos em uma série de experimentos Bernoulli.</p>
<h3>Fórmula:</h3>
<p><img src="https://latex.codecogs.com/svg.latex?P(X%20%3D%20k)%20%3D%20%5Cbinom%7Bk-1%7D%7Br-1%7D%20%5Ccdot%20p%5Er%20%5Ccdot%20(1-p)%5E%7Bk-r%7D" style="filter: brightness(0) invert(1);"></p>

<h2>Hipergeométrica</h2>
<p>A distribuição hipergeométrica modela o número de sucessos em uma amostra de tamanho fixo retirada de uma população finita, sem reposição.</p>
<h3>Fórmula:</h3>
<p><img src="https://latex.codecogs.com/svg.latex?P(X%20%3D%20k)%20%3D%20%5Cfrac%7B%5Cbinom%7Ba%7D%7Bk%7D%20%5Ccdot%20%5Cbinom%7Bb%7D%7Bn-k%7D%7D%7B%5Cbinom%7Ba&plus;b%7D%7Bn%7D%7D" style="filter: brightness(0) invert(1);"></p>

<h2>Poisson</h2>
<p>A distribuição de Poisson modela a probabilidade de um número específico de eventos ocorrer em um intervalo fixo de tempo ou espaço, dado uma taxa média de ocorrência desses eventos.</p>
<h3>Fórmula:</h3>
<p><img src="https://latex.codecogs.com/svg.latex?P(X%20%3D%20k)%20%3D%20%5Cfrac%7Be%5E%7B-%5Clambda%7D%20%5Clambda%5Ek%7D%7Bk%21%7D" style="filter: brightness(0) invert(1);"></p>

</body>
</html>