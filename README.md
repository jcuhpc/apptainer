# apptainer
A JCU repository for apptainer provisioning.

In 2019, a decision was made to containerise as many HPC workflows as
possible.    The primary driver was to support reproducible research.  
This repository, created by JCU HPC staff, contains a few scripts and
metadata files  that have been used to create  almost 500 apptainers.  
Zero trust and sustainability were key considerations.

We consider Ubuntu repositories to be a high trusted source.  Conda
repositories are a conditionally trusted source.  We have no choice
but to trust research software sources/binaries.  As a last resort,
when a build seems impossible, we download binary apptainer images.

We build base apptainer images (Ubuntu, Mamba, Python, & R) to speed
up the build of apptainers we deliver for researchers to use.  Also,
we have created a few scripts that  build apptainer definition files
for you.  In many cases, the definition files created simply provide
a starting point that requires modification.

This repository will contain every apptainer definition file created
for researchers using the JCU HPC cluster.  Modification will likely 
be required for non-JCU people wishing to use this repository.  This
is due to our "minimum viable product" approach to development.

-------------------
REPOSITORY CREATORS

Dr. Whitney Mallett

Mr. Wayne Spagnol
