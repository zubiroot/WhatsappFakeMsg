# WhatsappFakeMsg
How to reply to fake msg on whatsapp


Go to inspect element on Whatsapp Web and go to the Sources nav, select the "main" and search that on the code line.

              t.sendMsgRecord = function(e) {

Use the second search.

Then click on the number to stop the acction and answer the message.

Go to the console nav and write the fake message 

              e.__x_quotedMsg.body = "Fake message";
                                    
              e.__x_quotedStanzaID = e.__x_quotedStanzaID + "_";
