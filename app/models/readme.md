# recnn Models be @awarebayes

All of the models have been trained with the code in /examples/[Library Basics]/algorithms how to 

For Movie lens ML20m dataset with the state size of 1290 and frame size of 10.

Movie embeddings [found here](https://drive.google.com/open?id=1EQ_zXBR3DKpmJR3jBgLvt-xoOvArGMsL) are 128.
So the state is [128 (action=movie) x 10 (frame_size) + 10 (reward=rating, [1]xframe_size=10).

Everything is released under the Apache Licence.
