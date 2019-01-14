# Metadata Sync Examples

Tutorials about different modes of syncing metadata.

These are the ways to attach metadata to data points using the `ml data sync` CLI command.

## Examples

### case 1 : metadata file for each data point

In order to attached queryable metadata to a specific data point you need to create a metadata file for each file that consists the data point.
The metadata file should be in the same folder as the data point. e.g. 1.png and 1.png.metadata.json

[meta per file example](./meta%20per%20file)

### case 2 : one metadata file for entire folder

Instead of creating a metadata file for each data point there is a way to edit a single metadata file per folder.
The metadata file name should be folder.metadata.json .

when using a single metadata file per folder you need to add the filename as the key.

[meta per folder](./meta%20per%20folder)

