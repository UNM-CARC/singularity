# Singularity Tests
This repository contains test singularity recipes for Ubuntu and CentOS repository builds for
HPC systems at the UNM Center for Advanced Research Computing. These recipes are generally built
using Singularity Hub, which links to this repository, and are meant for debugging basic
container setups that are then used to develop other more complex recipes.

Note that these containers pull the CARC modules //into// the containers when they run so that 
code compiled outside the container can run inside the container. That's rarely something you want to
do, as one of the main point of containers is that they're stable and reproducible.
