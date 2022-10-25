# NLP-Star-Trek-Scripts
Using digital form of the actual scripts of the 'Star Trek' science fiction series to perform interesting NLP tasks and answering some questions on Topic Modelling, Character properties and the plot as a whole.


## About the Dataset

The Data consists of .json files with the full scripts of all Star Trek series processed into character lines:

Structure:

```json
{ 
                  seriesname : 
                    {episode number : 
                        {character : alllines
                        }
                    }
                  }
```
e.g.

allserieslines['DS9']['episode 0']['SISKO']

Text scraped from http://www.chakoteya.net/StarTrek/index.html
