---
layout: model
title: Deidentify RB
author: John Snow Labs
name: 
class: 
language: 
repository: clinical/models
date: 2019-06-04
tags: [clinical,deidentify,en]
article_header:
   type: cover
use_language_switcher: "Python-Scala-Java"
---

{:.h2_title}
## Description 


 {:.h2_title}
## Predicted Entities
Personal Information in order to deidentify 

{:.btn-box}
<button class="button button-orange" disabled>Live Demo</button><br/><button class="button button-orange" disabled>Open in Colab</button><br/>[Download](https://s3.amazonaws.com/auxdata.johnsnowlabs.com/clinical/models/deidentify_rb_en_2.0.2_2.4_1559672122511.zip){:.button.button-orange.button-orange-trans.arr.button-icon}<br/>

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
|-------------------------|------------------------|
| Model Name              | deidentify_rb          |
| Model Class             | DeIdentificationModel  |
| Spark Compatibility     | 2.0.2                  |
| Spark NLP Compatibility | 2.4                    |
| License                 | Licensed               |
| Edition                 | Official               |
| Input Labels            | document, token, chunk |
| Output Labels           | document               |
| Language                | en                     |
| Upstream Dependencies   | ner_deid               |





{:.h2_title}
## Data Source
Rule based DeIdentifier based on `ner_deid`.

