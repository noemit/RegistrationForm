RegistrationForm
================

Just another code test! This form validates using basic angular validators and regex as you type. When all fields validate and you press submit, a pretty modal pops up. A couple custom form elements (submit button, select element and checkboxes) were also made by me.

###Tools:
1. AngularJS
2. Bootstrap (jQuery included but didn't use it.)

###This form validates:
 1. Name
   * Error shows up only after the input is dirtied, or submit is pressed.
   * Only requirement for name is that it is not blank.
   * Validates as you type.
 
 2. Birth Year
   * Error shows up only after submit is pressed.
   * No real validation for year because you are already limited by the options.
   * Custom drop down icon on select box. Works in FF 30. 

 3. Email
   * regex basically requires something@something.smthg
   * TLD is required, so root@localhost won't work. Thought this would be more appropriate. TLD is 2-5 characters long.
   * Validates as you type.

 4. Residency
   * Custom check box.
   * The "yes" label activates the checkbox.
   * Image for the checkbox is part of a sprite with unchecked, checked, and the select dropdown in one image.

5. Zipcode
   * Disabled and not required by default. Triggered via the checkbox.
   * Regex validation for California zip codes only! (90001 to 96162)
   * Error shows up only after the input is dirtied, or submit is pressed.
   * Error does not show up while the input is disabled.
   * Input is cleared when residency button is checked/unchecked.
   * Validates as you type.


Tested both form & modal:
 * iPhone (7.0.4)
 * Android (newest version, default browser).
 * FF, Safari, Chrome on OSX
 * FF on PC

> (used browser shots to glimpse at a couple more.)
