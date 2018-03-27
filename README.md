# Metadata Sync Examples

Tutorials about different modes of syncing metadata.
There are 3 ways to attached metadata to data points using MALI CLI sync command.


## Examples

### case 1 : metadata file for each data point

In order to attached queryable metadata to a specific data point you need to create a metadata file for each file that consists the data point. The metadata file should be in the same folder as the data point.
e.g. 1.png and 1.png.metadata.json
[meta per file example](./meta%20per%20file)

### case 2 : one metadata file for entire folder

Instead of creating a metadata file for each data point there is a way to edit a single metadata file per folder.
the metadata file name should be folder.metadata.json 

when using a single metadata file per folder you need to add the filename as the key.

[meta per dir](./meta%20per%20dir)

!!! note
the metadata file only describes the specifiec folder without sub folders.
you need to create a metadata file for each synced folder.

### case 3 : metadata with annotations

The metadata files are used only for queryable metadata. if you need addinal metadata for the training purpose for example annotations you need to add that file to the data point. For more explanation read here <link>
[meta with annotations](./meta%20with%20annotations)
