RegistrationForm
================

Just another code test!

###Tools:
1. AngularJS
2. Bootstrap (jQuery included but didn't use it.)

###This form validates:
 1. Name
   * Error shows up only after the input is touched, or submit is pressed.
   * Only requirement for name is that it is not blank.
 
 2. Birth Year
   * Error shows up only after submit is pressed.
   * No real validation for year because you are already limited by the options.
   * Custom drop down icon on select box. Works in FF 30. 

 3. Email
   * regex basically requires something@something.smthg
   * TLD is required, so root@localhost won't work. Thought this would be more appropriate. TLD is 2-5 characters long.

 4. Residency
   * Custom check box.
   * The "yes" label activates the checkbox.
   * Image for the checkbox is part of a sprite with unchecked, checked, and the select dropdown in one image.

5. Zipcode
   * Disabled and not required by default. Triggered via the checkbox.
   * Regex validation for California zip codes only! (90001 to 96162)
   * Error shows up only after the input is touched, or submit is pressed.
   * Error does not show up while the input is disabled.
   * Input is cleared when residency button is checked/unchecked.

Cross-Browser Compatibility:


Tested both form & modal:
 * iPhone (7.0.4)
 * Android (newest version, I think).
 * FF, Safari, Chrome on OSX
 * FF on PC
> (used browser shots to glimpse at a couple more.)
