# stardict_tool

stardict2txt and info



stardict2txt.py from rongyi - https://gist.github.com/rongyi/ff2f8a1a82cddb2efc9239bb0d7ca78b

Python 3 version, original stardict2txt.py is Python 2 only (however python 3 version appears to be more robust, sorting works when ran under Python 3).


Tested with "GNU Collaborative International Dictionary of English" from http://build.koreader.rocks/download/dict/


## Dict tools and libs

 * pygloassy - maintained as of early 2022, mosty working.. TODO more details
 * https://github.com/pettarin/penelope - broken mobi support and no longer maintained

### Stardict info and other tools/libs

  * https://github.com/lig/pystardict
  * https://github.com/nijel/stardicter
  * https://github.com/pysuxing/python-stardict

### Mobi


https://jakemccrary.com/blog/2020/11/11/creating-a-custom-kindle-dictionary/


  * https://github.com/apeyser/tab2opf - patch needed for Windows support
  * https://github.com/quiris11/tab2opf



`prcgen dictionary.opf` will produce the dictionary.prc
`mobigen dictionary.opf` will produce the dictionary.mobi
`kindlegen dictionary.opf` will produce the dictionary.mobi

in kindle got:"

  English
  STARDICT
