
# GPT Uitgelegd

Deze repository biedt een eenvoudige benadering voor het bouwen van een GPT (Generative Pre-trained Transformer) model met behulp van een aangepaste dataset en PyTorch.

## Inhoudsopgave
- [Overzicht](#overzicht)
- [Installatie](#installatie)
- [Gebruik](#gebruik)
- [Dataset](#dataset)
- [Modeltraining](#modeltraining)
- [Bijdragen](#bijdragen)
- [Licentie](#licentie)

## Overzicht
Dit project toont hoe je een GPT-model kunt maken en trainen met PyTorch, gebruikmakend van je eigen dataset. Het behandelt data preprocessing, modelarchitectuur, training en evaluatie.

## Installatie
1. Clone de repository:
   ```bash
   git clone https://github.com/rickkosse/gpt_uitgelegd.git
   cd gpt_uitgelegd
   ```
2. Installeer de benodigde pakketten:
   ```bash
   pip install -r requirements.txt
   ```

## Gebruik
1. Bereid je dataset voor zoals beschreven in de [Dataset](#dataset) sectie.
2. Open het `gpt.ipynb` notebook.
3. Volg de instructies in het notebook om data te preprocessen, het model te definiëren en te trainen.

## Dataset
De dataset moet een tekstbestand zijn met de data waarop je het model wilt trainen. Plaats je dataset in de repository map en update het notebook om naar je datasetbestand te verwijzen. In deze tutorial gebruiken we het ted_dutch_mono.nl bestand. Dit zijn uitgeschreven TED talks in het Nederlands.

## Modeltraining
Het notebook bevat stappen om:
- De dataset te laden en te preprocessen.
- De GPT modelarchitectuur te definiëren.
- Het model te trainen.
- De prestaties van het model te evalueren.

## Bijdragen
Bijdragen zijn welkom! Open een issue of dien een pull request in met je verbeteringen of suggesties.
