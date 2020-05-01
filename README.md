# Generate TV Scripts using RNN
* This project was a part of Udacity Deep Learning Nano Degree.
* Built a LSTM network along with embedding neural network using Pytorch to generate tv scripts.
* Used Seinfeld dataset of scripts from 9 seasons
* The main goal of this project is to generate a realistic TV script given a starting word.

## Requirements
* If you don't have python installed on your machine download it from [here](https://www.python.org/ftp/python/3.8.2/python-3.8.2.exe)
* Then install pip on your machine by downloading this [get-pip.py](https://bootstrap.pypa.io/get-pip.py) and from the downloads directory and  run ```python get-pip.py```
* To start working on the project run the following command after cloning the repository.
```
pip install -r requirements.txt
```
This would install all the requirements.
## Output
* This dataset consists of Seinfeld Script for 9 Seasons
* Did preprocessing of the text.
* Considered 5000 frequently repeated words as vocabulary
* Given a starting word (Name of the character in the scripts) the model would be able to generate a script of required length.
* The character names are
    * jerry
    * elaine
    * george
    * kramer
* Given below is a sample of the output with __jerry__ as starting word and length of the script __400__
```
jerry: i have no idea how to get it.

jerry:(to the phone) hello, mr. peterman, you know.

elaine: what?

george: no, i can't.

jerry: oh, no, not...

jerry: oh, yeah.(to kramer) you know, you have to be a good time.

george: i don't know.

jerry: oh no, no, no, no. i didn't get a chance. i don't care for this.

elaine: what?

jerry:(to elaine) you know, it's like that, i don't have a big deal.

jerry: oh.... i got a little crush for this. i mean, i mean, i think we can have the same.

elaine:(looking at her watch) oh, i think i can.(turns and walks away.) hey, hey!

jerry: hi, what happened.

kramer:(to george) oh, you know, i think i can get the money.

jerry:(to elaine) what?

george:(looking at the tag) oh! yeah, yeah, i am so glad about it. i think i should. i think i'm gonna tell you. i don't have any idea.

jerry: what?

jerry: i dont know, i was just curious.

kramer:(to jerry) i can't believe this, i'm gonna get a massage, and the whole is going to the hospital.

newman: i told you, i don't care...

george:(on phone) hey!

jerry: what is it?

elaine: i know, i'm a little concerned about this.

elaine: oh, yeah.

kramer: well, i don't know what to do with this guy.

jerry: i can't believe it.

george: oh, yeah, well, you know...

jerry: i don't know.
```
*__This looks realistic right!!!__*
