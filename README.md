# sign-up-form-TOP

A sign-up page built with HTML and CSS, based on the design from The Odin Project's forms lesson. It has a background photo with a branded overlay on the left and a sign-up form on the right.

## Features

- Left panel with a background image, a semi-transparent "Odin" logo banner centered over it, and a photo credit pinned to the bottom corner using absolute positioning.
- Form fields for first name, last name, email, phone number, password and confirm password, grouped with fieldsets and labels.
- Built-in browser validation: email format, a 10-character phone number, and 6-12 character passwords.
- Input styling for states: a light border by default, a blue border and soft shadow on focus, and a red border when a value is invalid.
- Password hint messages that appear only after the user has typed something invalid, using the `:user-invalid` pseudo-class.

## Technologies

- HTML
- CSS


## Notes

This project is part of the Odin Project curriculum. Layout and positioning were the hardest part for me. 
Working through the overlay on the left side helped me understand how `position: relative` on a parent controls where an `absolute` child is placed. 
I also learned the difference between `width` and `max-width`, and how `:invalid` and `:user-invalid` behave differently.
