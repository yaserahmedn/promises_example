# promises_example
Differentiating JS call and a Promise call


Game is clicking the button (That's not even a game, HAHAHAHAHA).

If button is clicked more than 5 times within 2 seconds since page load, you win.
Else you loose.

How promises work?

Promise has 3 states:
1. Unresolved- when the event is occuring or waiting for event to finish (Here, waiting for 2 seconds)
2. Resolved- Success condition. (Here, if button is clicked more than 5 times, its a success). We return resolve() on success and the listener executes .then() instance on call object.
3. Rejected- Fail condition. (Here, if button not clicked more than 5 times). We return reject() on failure and the listener executes .catch() instance on object.
