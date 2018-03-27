# Metadata Sync Examples

Tutorials about how to sync different types of metadata.

(explain about metadata and datapoints)

## Examples

### case 1 : metadata file for each data point
in order to sync different metadata per datapoint,
you should have one metadata file for each data point.
e.g. 1.png and 1.png.metadata.json
[meta per file example](./meta%20per%20file)

### case 2 : metadata file for directory
in order to sync shared metadata per multiple datapoints, 
you should have one metadata file for the entire folder.
e.g. folder.metadata.json
[meta per dir](./meta%20per%20dir)

### case 3 : metadata with annotations
in order to sync annotations,
you should save them on seperate xml file.
[meta with annotations](./meta%20with%20annotations)

## Sync Command
```bash
mali data sync yourDataVolumeID --dataPath ./Data
```