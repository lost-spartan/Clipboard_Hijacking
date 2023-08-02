# Clipboard_Hijacking

This is a python code which can read the text (not images or any other media) present in your clipboard. 
This code contains few function definations

## Module Distribution.
- Getting data from the Clipboard.
- Putting the data into a **.txt** file.
- Sending the recieved Clipboar data from one Email id to other. This function contains few segments such as : 
- - Setting of text file as an attachment.
  - Attaching the attachment as a MIME multipart object.
 
## Requirements
To run the following code you need to have a compiler (IDE) which can run the python code, together with this you need to install or update **pip** to the latest version and together with this you need to have **pywin 32 module** installed into your system.

## Working Principle
When you will run this code any text that is present in your clipboard will be read, displayed to the output screen of compiler and then a **.txt** file will get created in the path you have stored (for multiple run you might need to delete the pre-created text file or you can change the name of text file). After this your compiler will read the given requisites to send a mail from the code and tracing the location of text file application of necessary encryption, payloads to create a MIME Multipart Object. Then the text file is attached to MIME Multipart Object and then it is sent to the destined E-mail id using the **smtp** manipulation.

## Result
After running the code you will see the text present in your clipboard on you IDE output screen and you will recieve a mail with a subject, message given in code with an attachment (.txt file) which will contain your clipboard data

## Thank you For Reading

This code was submitted as a part of my 2nd year project in the year of 2021-2022
