# Boost Multi Index Container Natvis
Provides nice visualization during debugging for `boost::multi_index_container` in Visual Studio. Helps to turn this:

<img src="./images/raw_view.png"/>

into this:

<img src="./images/natvis.png"/>

## Usage
Place corresponding `BoostMultiIndex.natvis` file into `%USERPROFILE%\My Documents\Visual Studio [version]\Visualizers`.

**Note:** for `random_access_index` and `hashed_index_node` Visual Studio 2015 or above is requred.
