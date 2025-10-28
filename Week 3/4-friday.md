# Friday Instructions

Today you will be learning about accessibility.

Morning (9am-12pm):
1. Watch the [accessibility videos](https://frontendmasters.com/courses/accessibility-v3/) up to Installing a Screen Reader. Complete the instructions to install a screen reader that are relevant to your machine and play around with it for 5-10 minutes (you will need headphones if you are in the office)
2. Continue the videos up to Screen Reader Only Content
3. Watch the Screen Reader Exercise video up to the pause point (1:09). Clone the project as instructed (`git clone https://github.com/jkup/learn-a11y.git`) and have a go at the exercise. You will need to follow the README.md instructions (the Using node.js section) before tackling the exercise. Once you have started the server with `http-server` you can access the site on `http://127.0.0.1:8080/aria.html` (paste this into your browser). The exercise is in the `screen-reader.html` file. Spend no more than 30 mins on this once set up
4. Watch the rest of the video to see his solution and think critically about yours
5. Watch the Focus Styles and Exercise video up to the pause point (2:17)
6. Complete the exercise and finish the video

Afternoon (1pm-5pm):
1. Watch up to the pause point in the tab-trapping exercise (1:16)
2. Complete the tab-trapping exercise. Spend no more than 30 mins on this exercise. The exercise is a little obscure so here are some hints:
    - Look in the `tab-trapping.html` file. You need to add a `handleTabKey` method. There is already an event listener for the escape key.
    - Look at [this page](https://developer.mozilla.org/en-US/docs/Web/API/UI_Events/Keyboard_event_key_values) on different key events to find the right key to capture a tab keypress
    - `console.log` the event to see what properties it has. One of those properties will allow you to see whether the tab was pressed with the shift key held down
    - You can use `document.activeElement` to get the currently focused element
    - He has a helper function `getFocusableElements()`. log it to the console with the modal open to see what it gives you
    - look up the `element.focus()` and `event.preventDefault()` methods
3. Watch the ARIA section up to the pause point in ARIA Labels & Roles exercise (1:37). Complete the exercise, spending no more than 15 minutes on it
4. Watch the color contrast videos and complete the exercise
5. Watch the Accessibility Tools video and the Accessibility Audit Exercise up to the pause point (1:16)
6. Complete the exercise. Keep rerunning after applying fixes and see how high you can get your score. You can spend as long as you like on this but give yourself half an hour to finish the rest of the videos
7. Finish the videos

If you finish all this in good time review [what to do if you get ahead](../Week%201/1-Intro/tips.md).

[Back](week-3-links.md)
