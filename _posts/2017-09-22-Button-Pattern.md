---
layout: post
title: Buttons
---
# Buttons
Use buttons to move though a transaction, aim to use only one button per page.

## Button text

Button text should be short and describe the action the button performs.

''''html
<a class="btn btn-primary" href="#" target="_self">Apply</a>
''''

## Button alignment

Align the primary action button to the left edge of your form, in the user’s line of sight

## Disabled buttons

Don’t disable buttons, unless there’s a good reason to
If you have to disable buttons, make sure they look like you can’t click them (use 50% opacity)
Use the aria-disabled attribute for older screen readers
An example of a useful disabled option is a calendar with greyed out days where no bookings are available
Provide another way for the user to continue, add an error message or text to explain why the button is disabled
