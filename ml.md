
# Table of Contents

1.  [Termini base](#org01ced4a)
    1.  [Modello](#orgbe41e0a)
    2.  [Dataset in input](#org860c00c)
    3.  [Supervised learning](#org751c10f)
    4.  [Unsupervised learning](#org538977e)
    5.  [Etichetta](#org572087a)
    6.  [Cluster](#org6b47d47)
2.  [Prerequisiti](#orgc892123)



<a id="org01ced4a"></a>

# Termini base

Per poter effettuare delle previsioni su un dato, è necessario definire alcuni componenti:


<a id="orgbe41e0a"></a>

## Modello

Relazione tra le caratteristiche e l&rsquo;output.
Rappresentazione interna dei dati che l&rsquo;algoritmo ha appreso finora. Scatola nera che dati dei valori in input, fornisce una previsione in base a ciò che ha appreso finora.


<a id="org860c00c"></a>

## Dataset in input

Per poter effettuare il training del modello, è necessario creare un insieme di dati da fornire in input. Questi dati sono costituiti da un insieme di caratteristiche (ovvero dei parametri che definiscono il dato) e, nel caso di supervised learning, da un&rsquo;etichetta, che rappresenta il dato di output. Nel caso di unsupervided learning, l&rsquo;etichetta non viene fornita dal <span class="underline">data scientist</span> ma deve essere dedotta dall&rsquo;algoritmo di learning.


<a id="org751c10f"></a>

## Supervised learning

Il <span class="underline">data scientist</span> fornisce l&rsquo;etichetta insieme ai dati.


<a id="org538977e"></a>

## Unsupervised learning

Il <span class="underline">data scientist</span> non fornisce l&rsquo;etichetta insieme ai dati. L&rsquo;algoritmo di machine learning deve ricavare anche l&rsquo;etichetta.


<a id="org572087a"></a>

## Etichetta

Valore in output a cui corrispondono le varie caratteristiche che caratterizzano il dato.


<a id="org6b47d47"></a>

## Cluster

Per poter effettuare previsioni su dei dati non etichettati, è necessario definire dei cluster, ovvero un gruppo di dati. Il numero di cluster deve essere uguale al numero di possibili etichette. L&rsquo;algoritmo di learning definisce i cluster in base a dei possibili criteri matematici: ad esempio la distanza relativa tra ogni punto. Per esempio, per fornire una previsione su un nuovo dato, il modello prende la distanza del nuovo dato da ogni cluster e sceglie il cluster più vicino.


<a id="orgc892123"></a>

# Prerequisiti

