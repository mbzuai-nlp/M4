Put all the 3000 data here.
For human, the filename is:
```<DOMAIN>_human.jsonl```

For machine-generated, filename is:
```<DOMAIN>_<MODEL>.jsonl```

Follow the same format as others.
The model name and domain MUST BE THE SAME and CONSISTENT! Do not add extra stuff eg 3000 in the filename. 
This is for faster automation.

DOMAIN refers to the dataset used, it must be one of the: ```wikipedia, wikihow, reddit, arxiv, ruATD, baike, urdu-news, id-newspaper```

MODEL refers to the model used, it must be one of the: ```davinci, chatGPT, cohere, dolly-v2, bloomz, flan-t5, llama```

The JSONL dictionary entry must be:
```prompt, human_text, machine_text, model, source, source_ID```


