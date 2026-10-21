# SignTempo Player Releases

This public repository stores immutable, generated SignTempo player release artifacts.

Release files are produced by the player release workflow in `SignTempo/euroscreen-artistry`. Application source code and manually generated binaries do not belong in this repository.

Reviewed publish pointers live in `manifests/test` and `manifests/live`. Merging a
generated manifest pull request publishes that exact immutable release to Discover
or LIVE. Never edit an existing GitHub Release asset or move an existing release tag.
