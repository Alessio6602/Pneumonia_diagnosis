

## Pneumonia_diagnosis
Questa repository contiene il progetto di tesi svolto da Alessio Gatto, presso l'Università degli Studi di Bari "Aldo Moro". Il progetto consiste nella creazione e valutazione di un modello di Machine Learning basato sull'architettura MobileNet. L'obiettivo del progetto è permettere al modello addestrato di diagnosticare correttamente la polmonite ai pazienti, e di evidenziare le zone ritenute infette.

## Dataset
Il dataset utilizzato è presente sul sito Kaggle col nome di ChestXRay2017, scaricabile dal seguente link: https://www.kaggle.com/datasets/tolgadincer/labeled-chest-xray-images/data

Alternativamente è possibile scaricare la versione ridotta del dataset utilizzata durante gli esperimenti dal seguente link: [https://drive.google.com/drive/folders/1VBgbTsW4j6qn_LOLlvKmjzYC3PsdM419?usp=drive_link](https://drive.google.com/file/d/1gz831Zrm4F5tTQ3XIUaSNhUNNLHMgKmw/view?usp=drive_link)

## Setup
- Estrarre lo zip e salvare il dataset sul drive con il nome ChestXRay2017. Creare al suo interno, se non presente, una cartella "val" con all'interno due cartelle: "PNEUMONIA" e "NORMAL".
- Se si vuole utilizzare il programma in locale scaricare le librerie con il comando: pip install -r requirements.txt 

## Utilizzo
Aprire google Colab con il proprio account, dopodichè selezionare carica e aprire il file Pneumonia_diagnosis.ipynb. Durante l'esecuzione sarà necessario fornire l'autorizzazione ad accedere al proprio drive per accedere al dataset. Il programma permette di addestrare il modello e salvarlo sul drive. Per eseguire le predizioni su un modello già addestrato eseguire solo le celle poste dopo la scritta "Esecuzione su modello pre-addestrato".
Non è necessario scaricare il file requirements.txt su colab pocihè le librerie necessarie verranno installate durante l'esecuzione delle celle.

## Contributi 

[@Alessio Gatto](https://github.com/Alessio6602/Pneumonia_diagnosis.git)

## Requirements.txt

tensorflow==2.15
tf_keras_vis==0.87


