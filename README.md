# DREDD Project

The DREDD project is a lexical linter for the Intersystems ObjectScript.
*Only classes are linted by DREDD; int and mac routines are not supported.*
The project is organized to attend various bases of code with different necessities. For this:
- Project: the container of jurisdictions.
- Jurisdiction: a group of rules that are applied on a project.
- Rule: the conference of some specific scope on the code
    - Persistent: are applied only on %Persistent classes.
    - Class: applied on the declaration of the classes.
    - Method: are applied on ClassMethods, Methods and ClientMethods.

