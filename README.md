# ead2mods

Guideline for generating MODS records from an EAD finding aid to populate metadata for Islandora records.

1. Procure an EAD finding aid. The easiest method is to search for the collection in the XTF collection search, click on the “View XML” link, and save the page as an xml file.
2. Use Kernow to apply the stylesheet to the finding aid. This will create directories for the new MODS files
3. Zip the MODS files
4. Ingest into Islandora using the batch function
