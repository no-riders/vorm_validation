# vorm_validation
Form Validation

Form must be validated during typing, but no errors are shown prior to user started ty filling the form.
Form can not be sent if it contains any mistakes.
In case of any errors, the Send button should stay inactive (inactive button is commented out)
*Require filds are marked.

Fields containing error should be hilighted.

Common errors: 
- Required field is empty;
- Email typo;
- Email is taken(check against email list on the server);
- Password to short (up to 5 chars);
- Password is too simple (just digits, and just words);
- Password contains forbidden chars;
- Telephone number is not entered in valid international format;
- Box hasn't been ticked;

Server side validation: email request to be sent to https://aqueous-reaches-8130.herokuapp.com51
No jQuery, no synchronous requests.
