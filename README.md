## CF logging
        cf api https://api.ng.bluemix.net
       then
        cf login

        After makeing changes to manifest.yml
        cf push


Reference Video:
https://www.youtube.com/watch?v=ELwWhJGE2P8

1. Clone this project 
    https://github.com/watson-developer-cloud/conversation-simple

2. Create .env file, set wrkspace_id, user, password. Get these values from bluemix console.
3. Update manifest.yml
4. Login to cf and do cf push

5. In the console, create a new conversation service and simply import the .json from /training folder.
    Wait for watson to train with the json file. May take time.
    
