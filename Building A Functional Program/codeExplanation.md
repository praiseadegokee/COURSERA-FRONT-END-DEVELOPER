Overview
This code contains two functions: consoleStyler and celebrateStyler. The consoleStyler function allows you to customize the appearance of a message logged to the console, while the celebrateStyler function logs a celebratory message with a fixed style. Additionally, there is a third function styleAndCelebrate which combines the functionality of the first two functions.

consoleStyler function
The consoleStyler function takes four arguments:

color (string): The color of the text. Accepts any valid CSS color value.
background (string): The background color of the text. Accepts any valid CSS color value.
fontSize (string): The font size of the text. Accepts any valid CSS font size value.
txt (string): The message to be logged to the console.
The function creates a message and a style string, which are then logged to the console using the console.log function and the %c placeholder for custom styles.

celebrateStyler function
The celebrateStyler function takes a single argument:

reason (string): The reason for the celebration. Accepts either "birthday" or "champions".
The function has a fixed style for the celebratory message, and it logs a different message depending on the value of the reason argument. If reason is "birthday", it logs "Happy birthday". If reason is "champions", it logs "Congrats on the title!". Otherwise, it logs the value of the reason argument.

styleAndCelebrate function
The styleAndCelebrate function combines the functionality of the consoleStyler and celebrateStyler functions. It takes five arguments:

color (string): The color of the text. Accepts any valid CSS color value.
background (string): The background color of the text. Accepts any valid CSS color value.
fontSize (string): The font size of the text. Accepts any valid CSS font size value.
txt (string): The message to be logged to the console.
reason (string): The reason for the celebration. Accepts either "birthday" or "champions".
The function invokes the consoleStyler function with the first four arguments, and the celebrateStyler function with the fifth argument.

'''
consoleStyler('#1d5c63', '#ede6db', '40px', 'Congrats!');
celebrateStyler('birthday');
styleAndCelebrate('ef7c8e', 'fae8e0', '30px', 'You made it!', 'champions');
'''