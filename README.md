# Subclipse JavaHL Plugins with Windows Binaries

[![Build Status](https://travis-ci.org/subclipse/javahl-windows.svg?branch=master)](https://travis-ci.org/subclipse/javahl-windows)

This repository contains the Subclipse plugin and fragments for JavaHL. This includes
the Windows DLL's in a plugin fragment and is contained in a separate repository from
Subclipse in order to keep the DLL's out of the main repository.

Currently the master branch is for SVN 1.10 as that is the current SVN LTS release and there
is a separate branch for SVN 1.11. These branches needs to be updated when there are new SVN
releases. At minimum, new Windows binaries need to be uploaded for the release but it is also
possible the Java component needs an update .. this is less frequent outside of the .0 release.

When a new commit is pushed to the branch a new snapshot build is created and published. Creating
a tag of the branch will publish it as a release.
