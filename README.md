# chatbot
A chatbot named floral is made using IBM WATSON for a flower Shopping App
# CREATING WATSON CHATBOT
Register with Watson Assistant by clicking on this link.

1.Verify your account by clicking the confirmation email you receive by email (be sure to check your spam folder, if you don't see the email).

2.Log in to IBM Cloud (which hosts the Watson Assistant service) and when prompted, chose a cloud region and create an organization and space. US-South will work for many, but you have the option to select other cities and countries. For the organization, you can use your company name or even your own name. For space, pick a namespace that makes sense to you. For example, it can be a department in your organization (e.g., marketing) or a phase of development (test, dev, staging, or prod). You'll be able to customize and add new regions, organizations, and spaces at any time, so don't worry too much about what you select at first.

3.Click on the Assistant service within the Watson portion of the IBM Cloud catalog. This will bring you to a service creation page where you'll be asked to enter a name for the service. You can enter whatever you like or simply watson-assistant-flower-shop Select the Lite plan that offers you up to 10,000 requests per month for free and click on Create Click on the Launch tool to launch the Watson Assistant user interface.

4.Click on the workspace to create any workspace or click on the existing one, and explore the example chatbot. What intents and entities are there? If you are adventurous you can even take a look at the dialog section. Play around with the default example in Watson Assistant and when you feel like you have become more familiar with it, go back to the workspaces list by clicking on the table icon in the left side of the page.

# CREATE INTENT
On the Intent page click on Add Intent and a form appears, name your intent greetings and add in description like greet the user and in the Add user examples add the examples of greetings.

You can add as many intents you like based on many ways a user might greet our bot. Once added intents you might see that Try it out says Watson is training

That meas our Watson assistant is training and once that message goes we can test our chatbot by sending user examples we have set as well as any related random messages we haven't trained our bot with.

Once message is entered our chatbot should identify the intent of the message and display it under the message

# IMPORTING ENTITIES

We can actually create a csv file which then can be imported to our watson assistant. In Entities section hover on the first arrow just after the Entities button, it should say something for import

Click on the import button and you will find the format of csv file for importing entities. Create a file like that and then choose the file from your computer

Entities will be imported and watson will be trained with them. Don't forget to check chatbot after training each time.

# CREATING DIALOGS
In the dialogs section of our chatbot tool you should see that two dialogs welcome and anything_else nodes are already there for us with default values

If you try out the chatbot again you should see a welcome response from the chatbot. We will make this response more relating to our florence shop so click on the welcome node and in the Then respond with: section enter your preferred text for welcoming, the text should be very limited to the scope of our chatbot and should not include all the features that our chatbot supports, a nice welcome message would be

> Hello. My name is Floral and I am a chatbot. How can I help you?



 _____ _                 _     __   __            
|_   _| |               | |    \ \ / /            
  | | | |__   __ _ _ __ | | __  \ V /___  _   _   
  | | | '_ \ / _` | '_ \| |/ /   \ // _ \| | | |  
  | | | | | | (_| | | | |   <    | | (_) | |_| |  
  \_/ |_| |_|\__,_|_| |_|_|\_\   \_/\___/ \__,_|  
                                                  
                                                  
______                                            
|  ___|                                           
| |_ ___  _ __                                    
|  _/ _ \| '__|                                   
| || (_) | |                                      
\_| \___/|_|                                      
                                                  
                                                  
______      _               _   _               _ 
| ___ \    (_)             | | | |             | |
| |_/ / ___ _ _ __   __ _  | |_| | ___ _ __ ___| |
| ___ \/ _ \ | '_ \ / _` | |  _  |/ _ \ '__/ _ \ |
| |_/ /  __/ | | | | (_| | | | | |  __/ | |  __/_|
\____/ \___|_|_| |_|\__, | \_| |_/\___|_|  \___(_)
                     __/ |                        
                    |___/                         





                    
                    
                    


if (youEnjoyed) {
    starThisRepository();
}
