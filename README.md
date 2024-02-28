# Survival in SNEP's top selling albums 2022

## À propos

This dataset was created to study the survival of albums in the music charts. 
**Are there any characteristics of albums that can influence how long they survive in the top charts ?**

I chose the Top 200 best sold albums from SNEP to study this.

**What is the SNEP ("Syndicat National de l'Edition Phonographique") ?**  The SNEP is the inter-professional organisation that protects the interests of the French record industry since 1922. SNEP's responsibilities include collecting and distributing royalty payments for broadcast and performance, preventing copyright infringement of its members' works (including music piracy), and sales certification of silver, gold, platinum and diamond records and videos. SNEP also compiles weekly official charts of France's top-selling music, including singles and albums. 

**What is the top-selling albums ?** It’s a top published every Friday by the SNEP. It contains the 200 best-sellings albums of the week (Friday to Friday) in France. Physical sales and streaming are taken into account. 


## Contents

- 💡 [À propos](#à-propos)
- 🚀 [Description of the dataset](#description-of-the-dataset)
- 📚 [Sources](#sources)
- 📝 [Licence](#licence)

## Description of the dataset

In this dataset, you will find the 200 best-sellings albums of the week of 01/14/22 in France. The purpose of this dataset is to see the survival of these albums during all the weeks of year 2022.
About variables :
- *Titre* : Title of the album
- *Artiste* : Artist name
- *Label* : Names(s) of albums label(s)
- *Time* : Number of consecutive weeks the album remained in the top since the first week. 
- *Event* : The "event" is when the album leaves the top. "0" for the albums that remains in the top for 51 consecutive weeks of 2022 and "1" for those who leave the top.
- *Annee_Sortie* : Year of album released.
- *Longueur* : Length of the album. If it's a reissue on 01/14/22, it's the new length of the album.
- *Genre* : Music genre of the album.
- *Distributeur* : Name of album distributeur
- *Nombre_Pistes* : Number of tracks. If it's a reissue on 01/14/22, it's the new number of tracks of the album.
- *Reedition* : If the album is a reissue or not on 01/14/22.

## Sources

Data sources :
- SNEP : [Top Albums - SNEP (snepmusique.com)](https://snepmusique.com/les-tops/le-top-de-la-semaine/top-albums/?annee=2022&semaine=02)
- Wikipedia pages of albums
- Spotify

## Licence

Voir le fichier [LICENSE](./LICENSE.md) du dépôt.
