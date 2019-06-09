# Music-Generation-with-LSTM
This case study will deal with generating midi music using LSTM <br/>
<b>Reference</b>: https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5 <br/>
In this case study we will generate music using abc notation. ABC notation are a series of characters. By training the char-RNN we can generate new meaningful abc notation and convert it into midi format. Using following site we can convert, play and download the generated midi music https://abcjs.net/abcjs-editor.html <br/>
<b>Data-Source</b>: I have collected data using following two sources:
1. http://abc.sourceforge.net/NMD/
2. http://trillian.mit.edu/~jc/music/book/oneills/1850/X/ <br/>
I merged the abc notations of all the tunes into one text file which will act as input.
