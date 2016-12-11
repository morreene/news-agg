* This is the legacy version of RSSNews project.
* The code was used to test Django in June 2016. 
* The new project is RSSNews.

* nltk error: 'tokenizers/punkt/english.pickle' not found.

	Go into a python shell and type:
	```
	>>> import nltk
	>>> nltk.download()
	```
	Then an installation window appears. Go to the 'Models' tab and select 'punkt' from under the 'Identifier' column. Then click Download and it will install the necessary files. 