---
layout: model
title: Ner DL Model Bionlp
author: John Snow Labs
name: 
class: 
language: 
repository: clinical/models
date: 2020-01-28
tags: [clinical,ner,dl,cancer,genetics,bionlp,en]
article_header:
   type: cover
use_language_switcher: "Python-Scala-Java"
---

{:.h2_title}
## Description 
Pretrained named entity recognition deep learning model for biology and genetics terms.

 {:.h2_title}
## Predicted Entities
Amino_acid,Anatomical_system,Cancer,Cell,Cellular_component,Developing_anatomical_structure,Gene_or_gene_product,Immaterial_anatomical_entity,Organ,Organism,Organism_subdivision,Organism_substance,Pathological_formation,Simple_chemical,Tissue,tissue_structure 

{:.btn-box}
[Live Demo](https://demo.johnsnowlabs.com/healthcare/NER_TUMOR/){:.button.button-orange}<br/>[Open in Colab](https://colab.research.google.com/github/JohnSnowLabs/spark-nlp-workshop/blob/master/tutorials/Certification_Trainings/Healthcare/1.Clinical_Named_Entity_Recognition_Model.ipynb){:.button.button-orange.button-orange-trans.co.button-icon}<br/>[Download](https://s3.amazonaws.com/auxdata.johnsnowlabs.com/clinical/models/ner_bionlp_en_2.4.0_2.4_1580237286004.zip){:.button.button-orange.button-orange-trans.arr.button-icon}<br/>

## How to use 
<div class="tabs-box" markdown="1">

{% include programmingLanguageSelectScalaPython.html %}

```python

```

```scala

```
</div>



{:.model-param}
## Model Information
{:.table-model}
|-------------------------|----------------------------------|
| Model Name              | ner_bionlp                       |
| Model Class             | NerDLModel                       |
| Spark Compatibility     | 2.4.0                            |
| Spark NLP Compatibility | 2.4                              |
| License                 | Licensed                         |
| Edition                 | Official                         |
| Input Labels            | sentence, token, word_embeddings |
| Output Labels           | ner                              |
| Language                | en                               |
| Case Sensitive          | False                            |
| Upstream Dependencies   | embeddings_clinical              |





{:.h2_title}
## Data Source
Trained on Cancer Genetics (CG) task of the BioNLP Shared Task 2013 with `embeddings_clinical`.
