# README

This is a DVC data registry of intermediate geophysics data for my projects.


## Garbage collection rules

Garbage collection is regularly carried out, please read and follow the rules below:

- Only the version of tagged commits will be preserved.
- This means, `dvc gc -cT` will be executed regularly; please make tags if you think the data at a certain commit should be preserved in the history.
