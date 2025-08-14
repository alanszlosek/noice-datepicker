# noice-datepicker

Fewer clicks, taps, swipes, and scrolls. Here's my attempt at a date/time picker that tries to stay out of your way.

![Screenshot of the noice-datepicker day/calendar view](./noice.png)

[Click here for a demo](https://alanszlosek.com/files/noice-datepicker.html). Select the tabs (month, day, year, hour, minute) at the top to change those values.

Sometimes (often?) user interfaces don't need to mimic things from the real world. A date/time picker doesn't need to mimic a calendar or a clock.

Note: it needs more work to make easy to integrate with your existing code. If you have suggestions or PRs, I'd be happy to consider them.

## Features

* No swiping, scrolling or typing required to select a date and time
* No third-party requirements libraries (not based on React, etc).

## Regarding the name

I don't regularly exclaim "Noice!" ... it's just not my style. But since I am squarely in favor of the ethical and just treatment of my fellow human beings, you can consider the name to be exclaiming "No ICE!" instead.

Thank you for your attention to the matter, and for taking part in the fight for ethics, kindness, and justice. The moral arc of the universe depends on it.

## Todo

* Make colon and "@" not clickable
* Make it easier to integrate. Perhaps: separate JS, CSS and HTML into separate files
* Merge tab logic and date picking logic together (currently they're separate concerns)
* Ability to have more that 1 on a page. Accept DOM container and callback function into the init() call.

That's all for now.
