# neural-music-composer

This repository consists in the design and the implementation of a neural music composer based on recurrent units. 

In order to follow the logical order going through the notebooks, please be aware of this ordered list:
1. DataExtractionTransformation.ipynb --> get data in midi format, parse it, transform it into piano roll, encode it as text
2. DataPreparation.ipynb --> one-hot encode the textual data, train-test-validation split
3. GatedRnnModel.ipynb --> TPU setup, Tensorflow and Keras setup, char-level LSTM-based model design and training, char-level GRU-based model design and training
4. SequencesGeneration.ipynb --> char-level generation loop based on sampling at a certain temperature, collection of generated text sequences
5. Text2Midi.ipynb --> from text to piano-roll, from piano-roll to midi files
