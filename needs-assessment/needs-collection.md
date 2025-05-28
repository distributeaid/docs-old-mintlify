Strapi **_NeedsAssessment.Need_** collection
---
This collection holds a list of the specific needs for each region and subregion that has been documented in the historic needs assessment data.

- may want to include the frequency for updating this collection (quarterly, yearly, etc)
- may want to include the approach for updating this collection (the current approach versus a future approach)

- It currently holds the following content-field types:
    1. survey
        - This is a relational field type noted as "Relation with _NeedsAssessment.Survey_" 
        - To populate this field in the needs collection, we need to have the associated Strapi id number of the specified survey from the survey collection.
    2. region
        - This is a relational field type noted as "Relation with _Geo.region_" 
        - To populate this field in the needs collection, we need to have the associated Strapi id number of the specified region from the region collection.
    3. subregion
        - This is a relational field type noted as "Relation with _Geo.subregion_" 
        - To populate this field in the needs collection, we need to have the associated Strapi id number of the specified subregion from the subregion collection.
    4. item
        - This is a relational field type noted as "Relation with _Product.Item_" 
        - To populate this field in the needs collection, we need to have the associated Strapi id number of the specified item from the item collection.
    5. amount
        - This is the amount of items requested for the specific need.
        - It comes straight from the json data and does not have an id from another collection.
        - It is the `need` property in the historic data and was changed to "amount" in the [Need type](./types.md) for the script in order to align with this content-field type in the Strapi need collection.
    6. needs_assessment_survey (need to get clarity on this field as it currently appears as a duplicate of survey)