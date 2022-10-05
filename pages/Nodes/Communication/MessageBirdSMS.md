# Message Bird SMS
Send an SMS message using the MessageBird API

### Node properties
##### Originator
Where the SMS is sent from. This can be either a phone number or a text string with a maximum of 11 characters.
##### Body
The message to send
##### Recipients
The phone numbers to receive the SMS. Always add region codes to the numbers, but do not start them with the prefixes ‘+’ or ‘00’

    'PhoneNumber',
    'PhoneNumber2',

### Reference:
This node outputs a string whose values cannot be directly referenced.

# Example:
[Notifications](https://github.com/conneqtDocumentation/connectDocumentation/blob/main/Nodes/Examples/Notifications.md)
