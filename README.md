# COV2WORDS! Word list

This repository takes care of the generation of word lists using the open source version of KNIME. Text files are read in and processed for this purpose. The resulted wordlist is the json file in the root of the repository.

## Contents

- `corpus` contains all textual pre-processed input files
- `manual` contains manually defined words that are easy to remember, e.g. colors
- `stopwords` contains words that are removed from the corpus

## About corpus

The corpus contains the german most frequent words according to researchers from (University of Leipzeig)[https://web.archive.org/web/20090909075401/http://wortschatz.uni-leipzig.de/Papers/top10000de.txt].
Additionally the corpus extended by the biggest geographic terms such as the biggest cities in Germany and neighboring countries.
These information was crawled from Wikipedia and News Articles, that were crawled with (Newsplease)[https://github.com/fhamborg/news-please/wiki/user-guide].

## Contributors:

- Thomas Hepp

## License

MIT 2.0
