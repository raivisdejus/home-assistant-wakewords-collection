# Hei Džarvis!

Latvian version of "Hey Jarvis" will account for regional accent in pronunciation.


## Training

Target words selected to match sounding of the generated result. 

Test input on https://huggingface.co/spaces/RaivisDejus/Latvian-Piper-TTS 

Model used for sample generation https://huggingface.co/RaivisDejus/Piper-lv_LV-Aivars-medium

```
number_of_examples = 20000
number_of_training_steps = 50000
target_words = [
  "hhej, džarvis!", "hhej, džārvis!", "hhei džarvis!", "hhei džārvis!", 
  "hhej džarvis.", "hhej džārvis.", "hhej džarvi!", "hhej džārvi!", 
  "hej džarvis!", "hej džārvis!"
]
```
