# googol
alfred workflow for opening google sites with specific user.

## Why
As someone who is always logged-in to mutliple gmail accounts at any given time, accessing a particular google service with desired account is painstakingly inconvenient and unproductive. This Alfred workflow is my attempt to address the problem.

## How
The workflow does the trick by include a query parameter called `authUser` that is used to specified user's desired email account. For instance, to url to open mail using _harsilspatel@gmail.com_ would be </br> `https://mail.google.com/?authuser=harsilspatel@gmail.com`. </br> And the neat thing about this implementation is that even if you aren't logged-in using that email, it will open the site using the default user email account.

## Setup
1. Clone the repo. 
2. Drag and drop the .alfredworkflow to the workflows menu in Alfred app.
3. Key in your emails in _emails_ List Filter Input.

## to-do
- [ ] fuzzy search
- [ ] option to switch the arguments
- [ ] shortcut to execute the workflow
