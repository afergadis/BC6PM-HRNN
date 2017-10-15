# Hierarchical Bidirectional Attention-Based RNN in BioCreative VI Precision Medicine Track, Document Triage Task

Repository containing the winning system of the BioCreative VI Precision Medicine Track, Document Triage Task (2017). The model is a Hierarchical Bidirectional Attention-Based RNN, implemented in Keras.

# Embeddings
Put (or link) the embeddings file [PubMed-w2v.bin](http://evexdb.org/pmresources/vec-space-models/PubMed-w2v.bin) into 
the `embeddings` directory, or use Cached Embeddings.

## Cached Embeddings
Put (or link) the _cached_ embeddings file [_word_vectors.p](https://drive.google.com/open?id=0B1Ke0XMx85YWZmFJaVNvQlZjLU0) into 
the `embeddings` directory.

# Run and get saved model
  - Run `triage.py`
  - Wait for the training to stop. The saved model will be stored at `triage/models/experiments`
  - Use `triage/models/submissions/submit_task1.py` to load the saved model 
  and use it to get the predictions on a new dataset. 
  Set `model_name` to the name of the desired saved model in `triage/models/experiments`. 
