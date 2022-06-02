# Sentiment-Button-app

It is a smart review system for general store, resturents, marts etc. 
This project involves building an app on MIT app inventor for reciving user review and connecting it to Thinkspeak cloud service for uploading data and providing data analytics

## Getting started

Below given are the instructions which will help you understand and setup simillar project in your system .

### Prerequisites

You have to create an account on MIT app inventor and Thinkspeak cloud service.
MIT app inventor- On the designer page drag and drop different component required on the main page.
                  Then create the block code for the back end working of app.
Thinkspeak channel- Create a new channel and provide atleat two fields for reciving Good and bad review. Set the color, no. of results, time frame of the graph                       on required on the two fields.

### Methodology

The The display screen of the app contains :\n
    ```
    - a heading for the name of the mart, \n
    - two buttons for the good and bad review , \n
    -two messagge for instruction, \n
    -two invisible components :web, clock .\n
    ```
The coding part has three major blocks - \n
    **first**: When the button for good review is taped the block is executed , it iterates the value of variable(c) and passing the value of c to the "write api" for feeding it in field one.\n
               Also disabling both the review button for 10 sec becouse the thinkspeak sever can take one value every 10 sec. \n
    **second**: Both the buttons are enabled back for use . \n
    **third**: Value of the variable (c2) is updated and passed to the api key for the bad review and also both the buttons are disabled .\n
