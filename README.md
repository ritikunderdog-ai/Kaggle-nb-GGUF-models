# Kaggle-nb-GGUF-models
This repository have the Kaggle note books to run Hugging face Models And generate API keys. We can use the API and key for your claude code, Hermes agent and Wherever we need.



# Heremes Simple working LLM

 Sometimes your LLM won't work into Hermes If model's Context size or it has Minimum tokens limit is More than 6400. But you can mostly run only the 7B paramesters Model. but it's Maximum token limit usually ~32000.  

 The problem is,
     we can only run 'Less Parameter' Models into kaggle.
     - if You want to run a Large parameter LLM, You have to sacrifice the Bit. example 

    We have to modify the hermes "Model_Metadata.py" file to Bypass the default Settings.
    

     "The more bit you selected"
     "The more Accurate Data You have"

     