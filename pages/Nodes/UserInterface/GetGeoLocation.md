# Get geo-location
Get the current geo-location of the device.
### Node properties
##### Action
__Do not change__
##### Accuracy
Set the accuracy the geo location has to be placed in.
##### Label
Text to displayed somewhere, as of writing this it doesn’t show up anywhere

### Referencing
The node will return an array of coordinates, where the first entry ( coordinates[0] ) is the East/West longitude, the second entry (coordinates[1] ) is the North/South latitude and the third value (coordinates[2] ) is the zoom. But this third value will most likely return null (empty).
The node will also return the type of Geo-location

# Example:
_-_

