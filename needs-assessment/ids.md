not sure if we need this one. Created this to add info relating to ids and if there needs to be a distinction between id and id number (or if document id comes into play here).

Will need to discuss different id references to distinguish them from each other and what ids we use where

- In scripts, we currently use the Strapi id number for each entry.
- In tests, we utilize both the Strapi id number and the document id for each entry.

It is noted in the [Strapi documentation](https://docs.strapi.io/cms/migration/v4-to-v5/breaking-changes/use-document-id) that use of the id number will be phased out and it is now recommended to use the document id instead in API calls.