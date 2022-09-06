# Identification of limitations

a) My solution will not work well on a transcript which do not meet or satisfy any of the rules used in identifying the speakers in each sentence.<br/>
The rules or conditions I used are :<br/>
*   If the identified entity is a person and the three parts of speach identified before that entity are "PRON , NOUN, AUX"<br/>
*    If the identified entity is a person and the 2 parts of speach identified before that entity are "AUX , PRON"<br/>

*    If the identified entity is a person and the 4 parts of speach identified after that entity are "PUNCT , PRON,AUX,PRON". <br/>
My solution will not perform well on transcripts which do not satisfy the rules stated above.


b) My solution will not work well on transcripts which have names of persons which are not in the knowledgebase of the spacy model I used in my implementation. <br/>
c) My solution will not be efficient on a transcript which do not meet the format "speakerID : utteranceText" for each line or utterance. <br/>
d) Also my solution will not be able to work well on transcripts which do not have the names of the speakers in them. <br/>

