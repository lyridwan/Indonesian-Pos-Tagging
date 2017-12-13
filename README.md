

# README #
- [English Version](#english-version)
  - [Introduction](#introduction)
  - [Corpus](#corpus)
  - [How to Use](#how-to-use)
  - [Credits](#credits)
  - [License](#license)

## Introduction ##

Simple Indonesian POS Tagging program using NLTK lib written in python 3

## Corpus ##
Corpus cited from Tagged UI Corpus
- famrashel, [Github](https://github.com/famrashel/idn-tagged-corpus)  (from http://bahasa.cs.ui.ac.id/)

This Corpus is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/.

## How to Use ##

1. Install Python 3
2. Install NLTK Lib using pip `pip install nltk` or read description [here](http://www.nltk.org/install.html)
3. Run [hmm.py](./hmm.py)
4. Tagging process 
	```python
	print(tagger.tag("saya pergi ke pasar".split()))
	```
## Screenshot ##
Output:
	[alt text](https://s1.postimg.org/2xeoni799b/image.png "Input")  

## Credits ##

- famrashel, [Github](https://github.com/famrashel/idn-tagged-corpus)


## License
This source code is licensed under the [GPL v3](https://opensource.org/licenses/gpl-3.0.html) 
license, see the [LICENSE](./LICENSE) file in the project root for the full license text.


