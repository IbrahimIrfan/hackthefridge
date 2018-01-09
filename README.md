# hackthefridge

Hack the Fridge is a smart fridge which takes a picture of each food item as it is placed in the fridge and compiles a list of possible recipes based on that item and the items already in the fridge. It also records the date each food was added and keeps track of their expiry.

We took pictures using a Raspberry Pi camera with Python and sent them to a Node.js server on AWS. Each food item was stored as an object using MongoDB, the data was then presented on an iOS app.

