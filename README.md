# AttentionIsAllYouNeed

#### Clone this repository and run the inference.ipynb file and install the dependencies by running the command.

```
pip install -r requirements.txt
```

#### Please download the weight from my [Google Drive](https://drive.google.com/drive/folders/18lpTIzkoaGOEQsVci2sZI2-eRHIudNVd?usp=sharing). Make sure to download this weight in ```weights``` folder and place it in the parent directory.

#### Run the inference.ipynb file to see the translation in action.

#### To train your own model on a different dataset, you will have to make three changes, one in ```train.py``` at line 153 to specify your own dataset, and the other two changes in ```config.py```, where you have to change the source language and target language. You might also want to change the max_len property in same file to fit the longest sentence.

#### To see the attention visualization, please run attention_visual.ipynb
