To test the Outcome variable, enter some text in the dialog box and press Check.  The first script will do the following:

If the word entered into the dialog box is **True** the Outcome variable will be set to correct, any other value will set iy to false.

The second script will then check the value of the Outcome variable.  If the varibale is set to Correct the script with end with success if the variable is set to anything else the script will end with a fail.  In addition this final script will also output the value of the Outcome variable.

@lab.TextBox(Data1)

@lab.Activity(Automated1)

The Outcometest varibale is set to: @lab.Variable(OutComeTest)

You will notice in the outputs the output from the scripts is always one execution behind what you type in.
