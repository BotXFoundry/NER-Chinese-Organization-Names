# NER-Chinese-Organization-Names

Last Updated On：2024-09-04

## Overview

Named Entity Recognition (NER) is a core technology in the field of Natural Language Processing (NLP). As the foundation of information extraction, NER is capable of accurately identifying and classifying key entities in text, such as person names, place names, and organization names, providing robust support for advanced NLP tasks like relation extraction and question answering systems. Particularly in the domains of human-computer interaction and intelligent services, NER enables systems to more precisely comprehend user needs by accurately recognizing named entities in user inputs, thereby offering personalized service experiences. Consequently, organization names datasets occupy an indispensable position in the performance evaluation of NER models, with their data quality and annotation quality playing a vital role in assessing model performance. Nevertheless, the current lack of publicly available, high-quality, and ultra-large-scale Chinese organization names datasets significantly hinders the in-depth development of related research and applications. To address this gap, we have meticulously gathered millions of organization names data from the internet and subjected them to rigorous processes including data correction, text normalization, and deduplication, ultimately open-sourcing a large-scale organization names database containing tens of thousands of entries to meet the needs of academic research and commercial development.

This open-sourced 100000 level Chinese organization names corpus will enrich and provide high-quality training and evaluation data for subtasks in the NLP field, such as word segmentation, named entity recognition, sentiment analysis, and knowledge graph construction, thereby contributing to algorithm optimization and model performance enhancement. We aspire to lower the data barriers between research and industry by providing standardized data resources, promote the translation of academic research achievements into practical applications, and accelerate the innovative application of AI technologies in fields like intelligent robots and human-computer interaction. In the realm of intelligent robots, precise place name recognition and processing form the foundation for efficient and natural human-computer interaction. We also anticipate that our organization names corpus will empower intelligent robots with a better understanding of user intentions and elevate the interactive experience.


### Dataset Characteristics:
**Large Scale**: Comprising millions of organization names collected from the internet, the dataset has been meticulously screened and processed, ultimately open-sourced as a 100000 level data corpus.
<br> 
**High Quality**: Advanced techniques such as data correction, text normalization, and deduplication have been employed to ensure the accuracy and reliability of the dataset.
<br> 
**Standardized**: Adhering to a unified annotation standard and data format, it facilitates data sharing and comparison among different research teams.
<br> 
**Diverse**: Encompassing organization names from various fields and cities, it caters to the diverse needs of industry research and intelligent services.




## Project Overview
### Directory

The directory classification for this project is as follows:

* [Chinese-Organization-Names](/Chinese-Organization-Names) 

     &emsp;&emsp;  [Chinese-Organization-Names_Big-Data_ni](Chinese-Organization-Names/Chinese-Organization-Names_Big-Data_ni.txt)
     <br> 
     &emsp;&emsp;  [Chinese-Organization-Names_Food_ni](Chinese-Organization-Names_Food_ni.txt)
     <br> 
     &emsp;&emsp;  [Chinese-Organization-Names_Rubber-Production-Company_ni](Chinese-Organization-Names_Rubber-Production-Company_ni.txt)
     <br> 
     &emsp;&emsp;  [Chinese-Organization-Names_ZhenJiang_ni](Chinese-Organization-Names/Chinese-Organization-Names_ZhenJiang_ni.txt)
     <br> 

* [POS_Standards](/POS_Standards)

     &emsp;&emsp;  [POS_Standards.pdf](POS_Standards/POS_Standards.pdf)
     <br> 
     &emsp;&emsp;  [POS_Standards.png](POS_Standards/POS_Standards.png)
     <br> 
     &emsp;&emsp;  [POS_Standards.xlsx](POS_Standards/POS_Standards.xlsx)
     
### File Encoding Format

File Format: The vocabulary bank is provided in the form of plain text files (.txt), with each line containing a single company name vocabulary.
<br> 
Encoding Method: It employs UTF-8 encoding to ensure support for multilingual characters (though the primary focus of this vocabulary bank is on Chinese organization names).
<br> 
No Additional Annotations: The current version of the company name vocabulary bank does not include additional annotation information, such as part of speech, but future versions may consider adding them.
<br> 
Note: the remaining part of the "Note" section was cut off in the original request, but if there's more content to be.
<br> 

### Part-Of-Speech tagging (POS) Standards
                                                                                        
| Number |Signal | Definition |
|:--:| :--: | :--:|
| 1 | ns | proper nouns referring to name of places|

### Size of the data sample

|   Number  |   Name   |   Size of Names  |
|:--:| :--: | :--:|      
| 1  | Chinese-Organization-Names_Big-Data_ni |392340|
| 2 | Chinese-Organization-Names_Food_ni |12892|
| 3  | Chinese-Organization-Names_Rubber-Production-Company_ni |15997|
| 4  | Chinese-Organization-Names_ZhenJiang_ni   |2605|

### Data Example

Chinese-Organization-Names_Big-Data_ni.txt

```
山东科兴生物制品有限公司
江西婺源制药厂
上海崇明绿华乳品厂
```

## License

This project is freely open to universities, research institutes, enterprises, organizations, and individuals both domestically and internationally, and can be used for research and commercial purposes.
<br>
We warmly welcome any valuable opinions and suggestions for this open-source project. Please send your emails to botx@botxfoundry.com.
<br>
The license agreement for this project is **Apache License 2.0**. You are free to use, copy, modify, and distribute this project, but you must comply with the provisions in the license.
<br>

## Publisher Introduction

BotXFoundry      &emsp;&emsp;   Web: http://www.botxfoundry.com

As a leading provider of commercial-grade intelligent robot platform solutions, BotX Foundry is dedicated to offering customers advanced intelligent robot universal platform products and technical services. It empowers digital transformation through its unique "F (Foundation) + X (Innovative Scenarios)" model.

The company's core products encompass three main sectors: universal mobile platforms for robots (tethered chassis), essential universal components for robots, and intelligent cloud-based robot brains. This forms a comprehensive and closed-loop product technology system centered around the five-dimensional ABCDE foundational capabilities: AI (Artificial Intelligence for Intelligent Cloud-Based Robot Brains), Bot (Universal Tethered Chassis for Robots), Control (Core Control Components for Robots), Drive (Power and Drive Components for Robots), and Edge (Universal Edge Computing Platforms for Robots).
<br> 
BotXFoundry boasts core technologies in various areas such as indoor and outdoor universal mobile chassis, high-precision servo control for robots, multi-modal and high-precision positioning and navigation, spatial computing for the Metaverse, large-scale models and intelligent human-machine interaction, integrated large-scale model development and training, and autonomous driving for robots.

As a tech company specializing in robotics, we are deeply aware of the significance of data in AI technology development. Consequently, we will continue to invest resources in optimizing and expanding this project while exploring more innovative application scenarios, thereby contributing further to the advancement of AI technology and human-computer interaction in intelligent robots. We look forward to collaborating with researchers and industry peers worldwide to jointly propel the prosperity and development of artificial intelligence technology.