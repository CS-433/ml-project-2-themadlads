# ml-project-2-themadlads
ml-project-2-themadlads created by GitHub Classroom


This is the repo for the ML4Science project 
## Fine-tuning a neural language model to address text constraints

We couldn't include our pretrained models as they were too heavy to be supported on github. (13 GB)
If you want to have a look at the different GPT-2 models, you can send us an email and we could look for a way to send it to you via a cloud service.


## Here is a quick overview for each of the notebooks:

#### Notebook 0 (N0):
A test notebook for generating text using  GPT-2 model.

#### Notebook 1 (N1):
This notebook is the poem generation system that we use in Experiment 4.
There is two version : one for google colab and the other one for local running.

#### Notebook 2 (N2):
This notebook is for computing the rhyme score accuracy.

#### Notebook 3 (N3):
You can generate the model with the N3-training-gpt2-and-generate-poems notebook. You will need a GPU and yu will need to install the  right environments including pytorch and cuda. 
This notebook also generates a text file generated by the model. You can then test the rhyming accuracy of this text file using the N2-compute-rhymes-score notebook. You can then run the Plot Results Task 1 notebook to get the plots. 

#### Notebook generate_only the rhymes :
Transform a poem dataset into a dataset containing only the last words of each verse.

#### Notebooks plot results:
Those notebooks are used for creating the pots we used in our report (loss and performance metric)

#### Notebook processing poems:
Notebooks containing all our data processing. Used for creating datasets that are useful for fine-tuning.

#### Notebook addblankline:
Another notebook for processing poems, this one was used for adding blank lines between each poem or each stanza.

#### Notebook delete_end_punctuation:
Another notebook for processing poems, this one deletes punctuation at the end of each verse

#### Notebook perplexity:
A notebook that contains our attempt at calculating perplexity of our models. Which we did not use at the end.

## All the data used to train the models and all data generated by the models are in this repo in the folders.
data_... and poems_...
