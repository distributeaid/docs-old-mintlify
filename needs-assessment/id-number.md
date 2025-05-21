not sure if we need this one. Created this to add info relating to id numbers and if there needs to be a distinction between id and id number (or if document id comes into play here).

The Strapi id number is a unique id assigned to each entry upon creation. It is usually the first field you will see of each entry line. It's value is different than the document id that is also assigned to each entry in Strapi. When accessing a relation field from a separate collection, this id number is what will be required in order to populate the specific relation field type value in the desired collection.  

For example:
* the **item** for a specifc need in the _NeedsAssessment.Need_ collection will exist in the _Product.Item_ collection.
In order to populate the item field in the needs collection, you must first get the id number for that item from the _Product.Item_ collection.
Then use that id number in the GET and POST method of the scripts in order to check if the need already exists, and if not, create the new need that populates the item field using that id number.