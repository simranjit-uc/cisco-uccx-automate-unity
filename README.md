# Using UCCX REST API to automate Cisco Unity VM pin reset workflow
This script will integrate Cisco UCCX with Cisco Unity Connection over REST API. The UCCX will offer an IVR based voice setup to the callers where they can provide their extension through DTMF inputs while the script is capturing that data and interacting with Unity Connection over REST APIs in real time. 

## Prerequisites/Instructions
- Cisco UCCX.
- Account with necessary privileges to access Cisco Unity's CUPI REST API.

## Cloning the App
You can simply issue the following command from the command prompt on your computer to clone this app to your local directory.
```
git clone https://github.com/simranjit-uc/cisco-uccx-automate-unity
```
## Running the App
You can add the script to the UCCX's script repository and associate with with the UCCX application/trigger.

## Script Flowchart
![Output](https://learnuccollab.com/wp-content/uploads/2023/08/CCX-Flow-1.jpg)

## More details
For more details on what this code means, you can check out the following 2 part series:
- Part 1 : https://learnuccollab.com/2023/08/05/cisco-uccx-with-rest-api-integration-unlocking-powerful-automation/
- Part 2 : https://learnuccollab.com/2023/08/20/automate-use-cases-with-cisco-uccx-rest-api-and-unity-connection/
