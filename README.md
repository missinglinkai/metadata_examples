# Metadata Sync Examples

This repo presents tutorials about different modes for syncing metadata.

There are three ways to attach metadata to data points using the MissingLink CLI `ml sync` command.


## Examples

### Case 1: Metadata file for each data point

In order to attached queryable metadata to a specific data point you need to create a metadata file for each file that consists the data point.
The metadata file should be in the same folder as the data point. For example: 1.png and 1.png.metadata.json

[meta per file example](./meta%20per%20file)

### Case 2: One metadata file for entire folder

Instead of creating a metadata file for each data point, there is a way to edit a single metadata file per folder.
The metadata file name should be folder.metadata.json.

When using a single metadata file per folder, you need to add the filename as the key.

[meta per folder](./meta%20per%20folder)


##### The metadata file only describes the specific folder without subfolders. You need to create a metadata file for each synced folder.

### Case 3: Metadata with annotations

The metadata files are used only for queryable metadata. If you need additional metadata for the training purposes, for example annotations, you need to add that file to the data point. 

[meta with annotations](./meta%20with%20annotations)
