# googol
alfred workflow for opening google sites with specific user.

## Why 💭
As someone who is always logged-in to mutliple gmail accounts at any given time, accessing a particular google service with desired account is painstakingly inconvenient and unproductive. This Alfred workflow is my attempt to address the problem.

## How 💡
The workflow does the trick by including a query parameter called `authUser` that is used to specified user's desired email account. For instance, to url to open mail using _harsilspatel@gmail.com_ would be </br> `https://mail.google.com/?authuser=harsilspatel@gmail.com`. </br> And the neat thing about this implementation is that even if you aren't logged-in using that email, it will open the site using the default user email account.

## Setup 🛠
1. Clone the repo. 
2. Drag and drop the .alfredworkflow to the workflows menu in Alfred app.
3. Key in your emails in _emails_ List Filter Input.
4. Configure the hotkey to execute the workflow (optional)


## Usage 🖱
<img src="screencaptures/usage.gif" width="60%">

</br>

## Supported sites 💻
<img src="src/List%20Filter%20Images/08e2efe620ad127030467c523eb94613429fd144.png" width="5%"> <img src="src/List%20Filter%20Images/0ea5253ba8b4c22388b9534624a1aec743c84483.png" width="5%"> <img src="src/List%20Filter%20Images/228e1954033f173dd0e0855e07c09250fabf8e37.png" width="5%"> <img src="src/List%20Filter%20Images/61b940d85bbe12c436da1eaeac91b1fe8314974b.png" width="5%"> <img src="src/List%20Filter%20Images/6ed7fcf7bacabe629d10613233bedc1c5ebff5be.png" width="5%"> <img src="src/List%20Filter%20Images/8d933643a3a5fa2af913585c1ec123665e9af93a.png" width="5%"> <img src="src/List%20Filter%20Images/a978de5140cae7c3a90b31ad6c256f4505e7440b.png" width="5%"> <img src="src/List%20Filter%20Images/db61cb3201fa3fadb9eb9f996c4806e051631f1b.png" width="5%"> <img src="src/List%20Filter%20Images/dc91cc263c786bfeb641a6b9f7b91b8673a01fcf.png" width="5%">

</br>


## to-do 📝
- [ ] fuzzy search
- [ ] option to switch the arguments
- [x] shortcut to execute the workflow
