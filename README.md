# ML_music

This project was an attempt to make midi-based music using machine learning techniques. The code works well, but depending on your input files, convergence make take quite some time, which is I why I would recommend modifying the code to create and save checkpoints.

The data used for this project are multi-track midi files of variable length. All files used in the training process are in 4/4-time signature to simplify the training and then the output. Vangelis midi files were sources from various places across the internet, as outlined in the works cited section of this paper. The bulk of the data used to train the model are midi files representing the works from a wide variety of classical composers. The initial data for the classical selections was sourced from kunstderfuge.com and consists of over 17,000 multi-track midi files. From this initial set, roughly 3500 midi files were selected from a number of composers to use as the training set. The requirements for the selection were simple: the midi file is complete and contains no metadata errors. Each file in the training set was tested for errors before inclusion in the data by running the convert from midi to binary matrix process on the files. 

To run this project, either clone the repository or download each python script. 

Code for this project comes from Jon Myers https://github.com/jon-myers/Feldman_dreams and Matteo Koffler https://github.com/burliEnterprises/tensorflow-music-generator
