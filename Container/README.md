# Container

This is the start of the container specification for bioschemas, giving us the
ability to represent a Container via a plugin to [schemas.org](https://www.schemas.org).
I am following instructions [here](https://github.com/BioSchemas/map2model#advanced-users-documentation)
that are linked from [here](https://www.github.com/bioschemas/specifications)
From the shared Google Drive I found a `_templates_` folder with 
[these instructions](https://docs.google.com/document/d/1i_ienpNed_kthaXzSS82OE0WddcM0ypcm8opTY3KqM4/edit)
to use [this original spreadsheet](https://docs.google.com/spreadsheets/d/1OMBiB8SXiRe1b3Cl91IuNlHbJ9_UXHg8B-GY0MYRSaY/edit#gid=1261485211) to generate a specification mapping.

The following groups are important to be heard from in working on this:

 - [bioschemas](https://www.bioschemas.org) since the specification is added here
 - [schemas.org](https://www.schemas.org) for the same reason
 - [open container initiative](https://github.com/opencontainers): I will post to the appropriate boards (e.g., runtime vs. image specification developers) to get feedback here.

## Important Things

 - The specification here should use the maximal possible from the OCI. We don't want to create **another** standard, but rather harness the work of the primary maintainers here!
 - It is imperative that this contribution not be "overfit" to the details of a container runtime or similar. For example, while the OCI image specification includes a representation of image layers (e.g., Docker) it may be sufficient for the use cases here (at least to start) to represent just the hash of the assembled final thing.

## Content
The following contents are included:

 - [configuration.yml](configuration.yml) was copied from the map2sec repository, as the entire directory called 
[spec2map](https://github.com/BioSchemas/map2model/tree/master/spec2model)
 - [_templates_](https://drive.google.com/drive/u/1/folders/0Bw_p-HKWUjHoQ2RkUUthWVd3RG8) was downloaded from the linked Google Drive Folder. This author does not have access to the content so I am providing it for review with this Pull Request and it can be added to where it needs to go.

## Issues in Doing This

 - It wasn't clear since I don't have access to the Google Drive how the folder and templates would be added there, or even who to contact to ask.
 - If you take a look at the first paragraph about the bread crumbs I followed to (maybe?) figure out how to do this contribution, there wasn't a super clear path. It would be really great if there were a single markdown somewhere that clearly walked through these steps!
 - In [this folder](https://drive.google.com/drive/u/1/folders/0Bw_p-HKWUjHoQ2RkUUthWVd3RG8) there are three copies of the same `Simplified _Bioschemas mapping template_(1-3).xlsx` I'm not sure which one I should be looking at / why the copies?
