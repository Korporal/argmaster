# argmaster
A unique command line parsing library for .Net console applications.

This command line parsing library is unique on Windows because it can retrieve arguments in two ways, either typed directly on the command line or (by invoking with a specific key sequence) by displaying an interactive navigable form that is drawn on the screen.

The form gives all your console applications a polished behavior in which novice users can easily see the names of all command argumnets as well as their types and restrictions.

The library is inspired by the s$parse_command utility subroutine found in Stratus's VOS OS, who's powerful support for comnand line parsing on dumb terminals was ahead of its time.

Argmaster is a .Net implementation of this concept and leverages .Net features to acheive similar capabilities. The interactive 'form' that is constructed (dynamically from the information passed at runtime to the API) makes it easy for users to remind themselves about available arguments, optional arguments and even get help information for any of the arguments.

If your organization relies on console applications for important data processing operations, then argmaster give you a basis to introduce a consistency across applications as well as greatly improving the usability of them, any command (when invoked as a form) can easily be cancelled should the user decide to not run the app.


