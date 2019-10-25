# id-multi-label-hate-speech-and-abusive-language-detection

## About this data
Here we provide our dataset for multi-label hate speech and abusive language detection in the Indonesian Twitter. The main dataset can be seen at **re_dataset** with labels information as follows:
* **HS** : hate speech label;
* **Abusive** : abusive language label;
* **HS_Individual** : hate speech targeted to an individual;
* **HS_Group** : hate speech targeted to a group;
* **HS_Religion** : hate speech related to religion/creed;
* **HS_Race** : hate speech related to race/ethnicity;
* **HS_Physical** : hate speech related to physical/disability;
* **HS_Gender** : hate speech related to gender/sexual orientation;
* **HS_Gender** : hate related to other invective/slander;
* **HS_Weak** : weak hate speech;
* **HS_Moderate** : moderate hate speech;
* **HS_Strong** : strong hate speech.

For each label, `1` means `yes` (tweets including that label), `0` mean `no` (tweets are not included in that label). 

Due to the Twitter's Terms of Service, we do not provide the tweet ID. All username and URL in this dataset are changed into USER and URL. 

For text normalization in our experiment, we built typo and slang words dictionaries named **new_kamusalay.csv**, that contain two columns (first columns are the typo and slang words, and the second one is the formal words). Here the examples of mapping:
* *beud --> banget*
* *jgn --> jangan*
* *loe --> kamu*

Furthermore, we also built abusive lexicon list named **abusive.csv** that can be used for feature extraction.

## More detail
If you want to know how this dataset was build (include the explanation of crawling and annotation technique) and how we did our experiment in multi-label hate speech and abusive language detection in Indonesian language using this dataset, you can read our paper in here: https://www.aclweb.org/anthology/W19-3506.pdf.

## How to cite us
This dataset and the other resource can be used for free, but if you want to publish paper/publication using this dataset, please cite this publication:

**Muhammad Okky Ibrohim and Indra Budi. 2019. Multi-label Hate Speech and Abusive Language Detection in Indonesian Twitter. In *ALW3: 3rd Workshop on Abusive Language Online, 46-57*.** (Every paper template may have different citation writting. For LaTex user, you can see **citation.bib**).

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
