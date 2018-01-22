# BigData Challange

Questo e' un repository di test per la Big Data Challange.

L'obiettivo e' predirre l'andamento del consumo energetico a partire da time series geo-temporali.

## Ranking

La valutazione dei progetti avverra' attraverso due classifiche: Una sulla precisione e una sulla velocita'. I due ranking hanno peso equivalente.

La precisione verra' calcolata usando lo scarto quadratico tra le previsioni e i dati reali. La velocita' invece 

# Software

## Modello

Un approccio possibile potrebbe essere quello di clusterizzare i dati per correlazione, e poi usare le reti neurali per predirre l'andamento delle serie.

## Strumenti

CUDA sara' utile per utilizzare la GPU, magari usando una libreria intermedia che ci astragga i dettagli implementativi.

Un'altra alternativa sarebbe quella di usare OpenCL, che ci permetterebbe di usare solo software open source, al costo di essere piu' lenti.

## Linguaggi

# Hardware

La challange usera' un'instanza amazon p2.8xlarge https://aws.amazon.com/ec2/instance-types/p2/, che ha circa 1 TFLOP di potenza CPU, e 10 TFLOPs di potenza GPU.

## Environment

Secondo le specifiche, tutto dovra' girare su Ubuntu 16.04, con docker. 

## GPU

Avremo a disposizione 8 schede Nvidia K80, per un totale di 16 GPU modello GK210.
