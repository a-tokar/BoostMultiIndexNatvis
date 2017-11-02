# Boost Multi Index Container Natvis
Provides nice visualization during debugging for `boost::multi_index_container` in Visual Studio. Helps to turn this:

![Raw View](images/raw_view.png)

into this:

![Refined View](images/natvis.png)

## Usage
Place corresponding `BoostMultiIndex.natvis` file into `%USERPROFILE%\My Documents\Visual Studio [version]\Visualizers`.

## Compatibility:
Visualizators are verified to work with following Boost and Visual Studio versions:

| Index type            | **boost** version | Visual Studio |
|:----------------------|:-----------------:|:-------------:|
| `ordered_index`       | 1.59 - 1.65       | &ge; 2013     |
| `ranked_index`        | 1.59 - 1.65       | &ge; 2013     |
| `sequenced_index`     | 1.50 - 1.65       | &ge; 2013     |
| `random_access_index` | 1.50 - 1.65       | &ge; 2015     |
| `hashed_index`        | 1.58 - 1.65       | &ge; 2015     |
