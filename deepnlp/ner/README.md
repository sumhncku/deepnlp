NER (Named Entity Recognition)
==============================
命名实体识别

Train your model
--------------------
自己训练模型

###NER model
#### Prepare corpus the same way as POS
#### Put data files in folder ../deepnlp/ner/data/'your_language_code'
#### Running script

```python
python ner_model.py zh # training Chinese model

python ner_model_bilstm.py   # Bi-LSTM model Chinese

python ner_model_bilstm_crf.py zh # Bi-LSTM-CRF model Chinese

```
#### The trained model can be found under folder ../deepnlp/ner/ckpt/'your_language_code'

#### New Update (July-18)
## Bi-directional LSTM-CRF model (Bi-LSTM-CRF)
Adding Bi-LSTM-CRF model script (pos_model_bilstm_crf.py) for sequence tagging tasks. 
The final layer is a CRF layer with global normalized loss function, compared to locally normalized loss function.

See papers for more details: 
Bidirectional LSTM-CRF Models for Sequence Tagging (https://arxiv.org/pdf/1508.01991v1.pdf)
Natural Language Processing (Almost) from Scratch (http://jmlr.org/papers/volume12/collobert11a/collobert11a.pdf)
