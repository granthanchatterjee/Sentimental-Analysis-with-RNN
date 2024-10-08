In this repository, sentimental analysis is done with RNN(Recurrent Neural Network) using Twitter_Data dataset which has two attributes:<br>
- clean_text(sentences gathered from users in X(former Twitter))<br>
- categories<br>
    - -1: Negative<br>
    - 0: Neutral<br>
    - 1: Positive<br><br>

-----------------------------------------------------------------------------------------------------------------------------------------------<br><br>

- To train the model, make sure that the ipynb file and csv fie both are in same location.<br>
- If not, then give the directory of the dataset properly.<br>
- After that, run the snippets one by one.<br>
<i>Training the model may consume a good amount of time depending on your system. It may be around an hour.</i><br>
- Once the model is trained and h5 file is saved<i>(By default, the h5 file will be saved in the same location of the code file)</i>, there wont be any need of running the same process again.<br>
- After saving the h5 file, directly run the last snippet.<br><br>
-----------------------------------------------------------------------------------------------------------------------------------------------<br><br>
<b>Testing the model:</b><br>
- This code allows the user to run the model and get the classification infinite number of times.<br>
- Once text is entered, it gives the result if the sentence is positive/negative/neutral.<br>
- It is an infinite loop and the loop can be stopped if enter is clicked without entereing any text
