# Pin_Bruteforce
```
Do not use these programs for malicious purposes, but for educational goals on accounts you have access to.
You can protect yourself from bruteforce with long passwords, but you cannot with PIN codes, except by the 
establishment by the platform of a delay in the event of repeated errors, which is not the case here. 
Fortunately, the stake isn't very big here.
```


## How to use these scripts
### Pre-requirements
You will need to have Python installed as well as the [`keyboard` package](https://pypi.org/project/keyboard/).

### miner.py
This one will type all the combinations in a range you precised. You can select the speed of typing and how long it has to pause between each code it types. All formats of PIN codes are supported, from `1` to `00000001` and beyond, in case you want to use it elsewhere. This parameter is determined in function of the length of the string you filled in the `End at:` input.

