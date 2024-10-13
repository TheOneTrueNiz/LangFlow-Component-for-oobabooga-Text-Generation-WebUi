# LangFlow-Component-for-oobabooga-Text-Generation-WebUi
Code for a Component to run local models from Text Gen WebUi in Langflow

Select Custom component in the Langflow playground menu. Copy and Paste this code, set your webui api and desired model parameters. This component passes a prompt to the Text Gen WebUi and collects the response from the model as its output. 



Start the API in text-generation-webui:

Edit the CMD_FLAGS.txt file in the main oobabooga folder

Type -- listen
     -- api 
     -- api-key sk-111111111111111111111111111111111111111111111111

Save the CMD_FLAGS.txt file

Start text-generation-webui



Start langflow

Add a Custom Component

Open the code editor for the custom component

Copy/paste this code and save

Type the api key you saved in CMD_FLAGS.txt in the langflow component
or add a global variable with the api key in langflow
