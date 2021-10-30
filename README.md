# NLP

Natural Language Processing apps 

Multilingual_NLP.py ################################################## start

#This script is demonstartion of Multilingual Natural Language Processing app using Stanza,Streamlit mainly.

Documentation link for Stanza: https://stanfordnlp.github.io/stanza/

# Depencies can be installed using below commands :

pip install streamlit==1.1.0
pip install stanza==1.3.0
pip install mtranslate==1.8
pip install PyAutoGUI==0.9.53
pip install pandas==1.2.4
pip install nltk==3.6.2

The windows path for language downloaded models is :
C:\Users\<username>\stanza_resources

Refer Supported_Languages sheet in stanza_supported_languages.xlsx and check for the languages you want to download.

#command prompt Sample code to download the language model is as follows :

import stanza
# to download language model for Afrikaans
stanza.download('af')
# to download language model for German
stanza.download('de')
# to download multilingual model 
stanza.download("multilingual")

Update langtable sheet in stanza_supported_languages.xlsx if you wish to add OR delete languages. Mostly nlp_langid	are transid same however google around for transid.

Multilingual_NLP.py ################################################## end
