this collection holds a list of the specific needs for each region and subregion that has been documented in the historic needs assessment data.

- may want to include the frequency for updating this collection (via the current approach versus a future approach)

- It currently holds the following content-field types:
    1. survey
        - This is a relational field type noted as "Relation with _NeedsAssessment.Survey_" 
        - To populate this field in the needs collection, we need to have the associated Strapi id number of the specified survey from the survey collection.
    2. region
    3. subregion
    4. item
    5. amount
    6. needs_assessment_survey (need to get clarity on this field as it currently appears as a duplicate of survey)