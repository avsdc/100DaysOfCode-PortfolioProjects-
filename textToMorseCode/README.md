
Description:

textToMorseCode application uses Python, Html, Flask and WTForms.

A dictionary i.e. morse_code_dict is used for converting from text to morse code, and morseCodeToText.
Keys consist of letters of the English alphabet, numbers 0-9, and some punctuation marks.
Values consist of series of dots and dashes.

keys list consists of keys, and values list consists of values. A form MyForm that takes FlaskForm as parameter
conists of input and output TextFields, and submit SubmitField.

Under the @app.route("/"), the function index determines whether the function textToMorseCode should be executed
or the function morseCodeToText should be executed. This is in turn determined by string1 and whether it contains
letters, numbers or dots and dashes.

string1 is entered in input_text of the html form, and pressing submit button results in string2 being displayed 
in output_text.

In the textToMorseCode function, there is a for loop, so that each character in string1 can be checked to see if it
is the first or middle letters of a word (in the if part), or if it is a space, last letter in a word or punctuation 
mark (in the else part). At the end of the for loop, the output_string consists of morse code for text entered in
input_text area of the html form.

In the morseCodeToText function, there is a for loop that determines if the character is a dot or dash (in the if part),
or if it is a space or "/" (in the else part).
In the if part, the dots or dashes are accumulated in a string i.e. ltr_str. In the else part, if the char is space,
the index of the ltr_str in the values list is determined and resulting position (pos) is used to index the keys list
and thereby retrieves the letter key. The letter is concatenated to the out_str. 

If the char is a "/", then again the index of the ltr_str in the values list is determined and resulting position (pos) 
is used to index the keys list and thereby retrieves the letter key. The letter is concatenated along with a space to
the out_str.

Requirements:

Python 3.6 is the interpreter for the application. This application was run in Pycharm Community edition.