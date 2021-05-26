# AI4D Baamtu Datamation - Automatic Speech Recognition in WOLOF: Third Place Solution

## Solution Summary
We started off by fine-tunning facebook's wav2vec2-xlsr-53 on the Wolof data for our acoustic model (AM) with the help of Hugging Face. After looking at both the training transcriptions and the test predictions genreated by the AM, we noticed a very large overlap in sentences. This prompted us to create a "sentence autocorrect" algorithm utilising lvenshtien distance which was subsequently used to post-processs the AM model predictions.

Expected notebook runtime (training on a RTX 2070 super): 8-9hrs 
