RegistrationForm
================

Just another code test!

This form validates:
1. Name
..1. Error shows up only after the input is touched, or submit is pressed.
..2. Only requirement for name is that it is not blank.

2. Birth Year
..1. Error shows up only after submit is pressed.
..2. No real validation for year because you are already limited by the options.
..3. Custom drop down icon on select box. Works in FF 30. 

3. Email
..1. regex basically requires something@something.smthg
..2. TLD is required, so root@localhost won't work. Thought this would be more appropriate. TLD is 2-5 characters long.

4. Residency
..a. Custom check box.
..b. Connected label is not the question, but the "Yes" label.
..c. Image for the checkbox is part of a sprite with unchecked, checked, and the select dropdown in one image.

5. Zipcode
a. Disabled and not required by default. Triggered via the checkbox.
b. Regex validation for California zip codes only! (90001 to 96162)
c. Error shows up only after the input is touched, or submit is pressed.
d. Error does not show up while the input is disabled.
e. Input is cleared when residency button is checked/unchecked.

Cross-Browser Compatibility:
Tested iPhone (7.0.4) and Android (newest version, I think). FF, Safari, Chrome on OSX & FF on PC. Used Browsershots occaisonally for the rest.
