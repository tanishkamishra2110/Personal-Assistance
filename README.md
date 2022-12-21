# Personal-Assistance
C++ text to speech application which acts as a personal assistant.
If you need to listen to the speech, then you must include these 4 lines of code:

string phrase = "whatever message you want to listen to"; string command = "espeak "" + phrase + """; const char *charCommand = command.c_str(); system(charCommand);
