######################
Arches Release Process
######################

Starting with version 4.1.0, the Arches team began making available both feature (minor) and patch (micro) releases on a regular basis.

````````````````````````````
Feature Releases
````````````````````````````

Feature releases will introduce significant, new features to Arches and will be announced approximately every 6 months.
Feature releases may contain schema or API changes that may not be compatible with the previous feature release.
Each feature release will be incremented with the pattern `a.b`, where `a` represents the major release and `b` represents the feature (aka minor) release.
Each feature release will be placed in its own branch in git, named with its release number followed by an `x` representing the latest patch release. (e.g. stable/a.b.x).

````````````````````````````
Patch Releases
````````````````````````````

Following each feature release we will resolve bugs, performance, and security issues in the most recent feature release with patch releases.
A new patch release, if needed, will be announced every 1 to 3 months and will **not** include breaking changes with the previous patch release. Therefore, we encourage users to stay up-to-date with these releases.
Patch releases will be incremented as such: `a.a.b, a.a.c...` with `a` representing the feature release and `b` and `c` representing patch (aka micro) releases. In Git each patch release will identified in its feature release branch with a tag.

````````````````````````````
Release Support
````````````````````````````
We will release patches only for the latest feature release.
