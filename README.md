# Sentiment-Button-app

![This is an image](https://miro.medium.com/proxy/1*_JW1JaMpK_fVGld8pd1_JQ.gif)

It is a smart review system for general store, restaurents, Shoping Malls etc. 
This project involves building an app on [MIT app inventor](https://appinventor.mit.edu/) for reciving user review and connecting it to [Thinkspeak cloud service](https://thingspeak.com/) for uploading data and providing analysis of the collected review.

## Getting started

The instructions provided below will help you understand and setup the environment for the project in your local system.

### Prerequisites

Create an account on MIT app inventor and Thinkspeak cloud service through the above mentioned links.
**MIT app inventor** - Open the designer page and include component required onto the main page. Then create the block code for the back end working of the app.
<br>
**Thinkspeak channel** - Create a new channel. Connect it to the build module in the MIT app through which you'll collect the responded data and incoorporate its analysis through different tools present in TSC Services.

### Methodology

The display screen of the app will contain:</br>

    A heading for the name of the mart, 
    Two buttons for the good and bad review, 
    Two messagge for instruction, 
    Two invisible components: web, clock. 
    
We can describe the coding in three major steps - </br>
    
    First: When the button for good review is taped the block is executed, it iterates the value of predefined variable and passes the value to the "write api" for  feeding in field one. It Also disables both the review button for 10 sec becouse the thinkspeak sever can take one value every 10 seceonds.
    Second: Both the buttons will be enabled back for use. 
    Third: Value of the variable is then updated and passed to the api key for the bad review.
