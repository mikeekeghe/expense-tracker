
<div class="jumbotron text-center">
    <p align="center"><span style="font-family: 'Liberation Sans', serif;"><span
            style="font-size: xx-large;"><strong><H1>How to Create An Expense Tracker App in React Native</H1></strong></span></span>
    </p>
    <p class="western">&nbsp;</p>
    <p class="western" align="center">Author: Michael Ekeghe</p>
    <p class="western" align="center">A React Native Tutorial Project.</p>
    <p class="western" align="center">For the Facebook Developer Challenge 2020</p>

</div>


          
                    
                        ##Introduction
Are you Looking for a way to create an expense and budget tool that runs on your mobile device? Stop searching and lets create one.

This  Expense Tracker is a simple, intuitive, stable and feature-rich app that is just designed for you. Everything you need at your fingertips to manage the expenditures, checkbook and budgets.

Get ready to track Your expenses and stick to a budget with this easy and efficient finance planning tool that we are about to create

Are you ready? Lets dive in


           ##Prerequisites

    • Knowledge of Basic ES6 JavaScript or typescript
    • A Text Editor (Atom/VS Code, or anyone anyone actually)
    • A tiny bit of React Know how
    • Node (versions 12.8 and above)
    • Expo App downloaded from AppStore or Google Play Store
    • Internet
    • API server (I used an API hosted on heroku)



           ##Preliminary Set-up

1. Make sure you have Nodejs set up and working on your machine. If you already have node installed on your machine, just move on to the next item.
For detailed instructions on how to install nodejs on your device, visit the link below
https://nodejs.org/en/download/package-manager/

           ##Summary of Instalation and set up
Assuming that you have Node 12 LTS or greater installed, you can use npm to install the Expo CLI command-line utility:
1. npm install -g expo-cli
2. expo init ExpenseTracker
3. cd ExpenseTracker
4. expo start 


           ##The Main The Main

1. For this project, we are using Expo. Its a command line tool that simplifies your react native development and testing 

Run the below commands to begin
npm install -g expo-cli

2. Next we actually initialize or simply create the react native base project
We do this by running the following command in your terminal window
expo init ExpenseTracker

3. chose the tabs(Typescript) template
  <p class="western"><img src="https://exp-trkr.herokuapp.com/img/0.png" width="665" height="348" name="Image1" align="left" border="0"/></p>

            <p class="western">&nbsp;</p>
            <p class="western"><span style="color: #333333;"><span><strong>Once done</strong></span></span></p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western"><span style="color: #333333;"><span
                    style="font-family: Roboto, Arial, sans-serif;"><span>4. Once done navigate to the new created projects&rsquo; directory</span></span></span>
            </p>
            <p class="western"><span style="color: #333333;"><span
                    style="font-family: Roboto, Arial, sans-serif;"><span>cd </span></span></span><span
                    style="color: #333333;"><span style="font-family: Roboto, Arial, sans-serif;"><span><strong>ExpenseTracker</strong></span></span></span>
            </p>
            <p class="western">&nbsp;</p>
            <p class="western"><span style="color: #333333;"><span
                    style="font-family: Roboto, Arial, sans-serif;"><span><strong>5.Run expo start in your terminal</strong></span></span></span>
            </p>
            <p class="western"><img src="https://exp-trkr.herokuapp.com/img/2.png" width="529" height="487" name="Image3" align="left" border="0"/></p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western"><span style="color: #333333;"><span
                    style="font-family: Roboto, Arial, sans-serif;"><span><strong>6. </strong></span></span></span><span
                    style="color: #333333;"><span style="font-family: Roboto, Arial, sans-serif;"><span>Open the ExpenseTracker folder in your text editor and you will see a similar folder structure</span></span></span>
            </p>
            <p class="western"><img src="https://exp-trkr.herokuapp.com/img/3.png" width="195" height="380" name="Image4" align="left" border="0"/></p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>
            <p class="western">&nbsp;</p>

            <p class="western"><span style="color: #333333;"><span
                    style="font-family: Roboto, Arial, sans-serif;"><span>7. now let's test our template app with the Expo app on your mobile device.</span></span></span>
            </p>
            <p class="western"><span style="color: #333333;"><span
                    style="font-family: Roboto, Arial, sans-serif;"><span>For Android users, </span></span></span></p>
            <p class="western"><span style="color: #333333;"><span
                    style="font-family: Roboto, Arial, sans-serif;"><span>Launch the expo app </span></span></span></p>
            <p class="western"><span style="color: #333333;"><span
                    style="font-family: Roboto, Arial, sans-serif;"><span>Click the scan button </span></span></span>
            </p>
            <p class="western"><span style="color: #333333;"><span
                    style="font-family: Roboto, Arial, sans-serif;"><span>Scan the QR code</span></span></span></p>
            <p class="western">&nbsp;</p>
            <p class="western"><span style="color: #333333;"><span
                    style="font-family: Roboto, Arial, sans-serif;"><span>For iPhone /Ipad users</span></span></span>
            </p>
            <p class="western"><span style="color: #333333;"><span
                    style="font-family: Roboto, Arial, sans-serif;"><span>Launch your Camera app</span></span></span>
            </p>
            <p class="western"><span style="color: #333333;"><span
                    style="font-family: Roboto, Arial, sans-serif;"><span>View the QR code</span></span></span></p>
            <p class="western">&nbsp;</p>
            <p class="western"><span style="color: #333333;"><span
                    style="font-family: Roboto, Arial, sans-serif;"><span>The App template is automatically launched</span></span></span>
            </p>
            <p class="western"><img src="https://exp-trkr.herokuapp.com/img/4.jpg" width="151" height="252" name="Image5" align="left" border="0"/></p>
     

          
            
##License
          
ExpensTracker is distributed under the <a href="http://opensource.org/licenses/MIT" target="_blank">MIT Open source license</a>.</span></span></span>
 

