# Arduino-Email
Code to send an email or text using an Arduino Nano 33 IoT. 
Check out my YouTube video for steps on how to set up the Gmail account and hardware: https://youtu.be/pLjP7T7vvDU

Format for sending a text:
-the only thing you change in the code is the putting "phoneRecipient" instead of "eMailRecipient" in lines 76 and 87.
-format of the "phoneRecipient" : phonenumber@carrier   > where phonenumber is 10 digits, no dashes or spaces
                                                        > and carrier is "txt.att.net" for AT&T
                                                        >                "vtext.com" for Verizon
                                                        >                "tmomail.net" for TMobile