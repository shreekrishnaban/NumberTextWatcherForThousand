#**Add Thousand Seperator automatically at Android EditText While Writing**
This class is used For thousand seperator to the android EditText while taking currency input, 
This seperats the editText input with comma while user is entering the value.

#Fetures

 1. Puts thousand separator as EditText text changed.

 2. adds 0. Automatically when pressed period (.) At First.

 3. Ignores 0 input at Beginning.
 
#How to use ?
 1. Just Download the java file and paste it in your project.
 2. Use this class in your EditText as follows
     ```editText.addTextChangedListener(new NumberTextWatcherForThousand(editText));```

#To get the input as plain Double Text
 Use the trimCommaOfString method of the same class like this
     ```NumberTextWatcherForThousand.trimCommaOfString(editText.getText().toString())```
 
