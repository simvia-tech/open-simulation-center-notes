# Version explanations

This page explains the differences between the installer available on https://open-simulation-center.org. It does not explain the difference from one version of the software to another. For this we refer the interested user to the changelogs of the code on their official website.

## Software supported

On open-simulation-center, we provide installer for:

- code_aster: https://code-aster.org. You can find the difference between the versions [here](./code_aster/installers.md).
- code_saturne: https://code-saturne.org. You can find the difference between the versions [here](./code_saturne/installers.md).
- openTELEMAC: https://www.opentelemac.org. You can find the difference between the versions [here](./opentelemac/installers.md).
- salome_platform: https://www.salome-platform.org. You can find the difference between the versions [here](./salome/installers.md).


## Standard installer formats

For most of the codes and their versions, you will find on open-simulation-center.org the following installers:

- xxxx.msi : this extension stands for microsoft installer. It is an executable that will automatically install on your computer the code, and that will ask for customization options.
- xxxx.tar.gz : this extensions is the installer for the linux packages. It allows to download in local all of the compiled binaries file of the codes.
- Docker / Singularity : docker and singularity are containers manager. A container is a process you can run to have a ready to use access to the code. However, containers cannot be modified, and any change made inside the container is discarded at the end of the session. All of the containers have an entry point, allowing you to save files locally. Docker and singularity are more naturally used on Linux.