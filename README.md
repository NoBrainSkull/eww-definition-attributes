## Describe the bug
When data is fetched with script-var and passed to a user-defined widget through an attribute, the widget is not re-rendered when the variable is updated.

## Reproducing the issue
* Create an easy-to-refresh script-var
* pass it to a defined-widget through an attribute
* Update it
* Widget wont be updated

Or don't and just clone my reproduction repo :
[https://github.com/RaisonBlue/eww-definition-attributes](https://github.com/RaisonBlue/eww-definition-attributes)

## Expected behaviour
I'm expecting to pass variable to definitions through attributes so I can reuse my definitions.
