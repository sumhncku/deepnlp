# Release Log

## [0.1.7] - WIP
### Changed
tensorflow (=1.2) Support the tensorflow 1.2 function changes

### Added
- Bi-LSTM-CRF model for POS and NER module
- Parser: Python implementation of the dependency parser, which use the same architecture as stanford CoreNLP NNDepParser

## [0.1.6] - 2017-03-09
### Changed
tensorflow (=1.0) Support the latest tensorflow 1.0 function changes

### Added
- Restful API module: Calling deepnlp.org web NLP API access and usage
- textsum: implementing Seq2Seq-Attention model for automatic summarization, e.g. news headline generation
- textrank: textrank algorithm for extract and sort the important sentences

## [0.1.5] - 2016-11-15
### Changed
tensorflow (<=0.12.0)
### Added
- POS: Pre-trained English model using the Brown Corpus

## [0.1.4] - 2016-11-15
### Added
- Segment: Adding Chinese Segmentation models trained by CRF++ package
- POS: Including pre-trained Chinese models from China Daily corpus
- NER: Including pre-trained Chinese models from China Daily corpus
