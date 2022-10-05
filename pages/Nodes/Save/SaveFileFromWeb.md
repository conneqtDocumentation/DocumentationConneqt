# Save file from the web

Uploads a file from a given HTTP URI to conneqt. The node result is a reference to the uploaded file, usable as a property value.

### Node properties 

##### Uri
The URI of the file you want to upload.
E.g. https://example.org/images/image.png

### Return:
The node returns 5 bits of information.
- ContentType: Returns the type of content and the way it's saved.
- Size: Returns the size of the file in bytes.
- Base64Thumbnail: Returns the image in a Base64 encryption. This is the return data you want to reference to use the image.
- Identifier: The identifier under which the file is stored in the database.
- Name: Returns the name of the image

# Example:
[Using an image](https://github.com/conneqtDocumentation/connectDocumentation/blob/main/Nodes/Examples/UsingAnImage.md)
