# apptainer
A JCU repository for apptainer provisioning.

This repository, created by JCU HPC staff, contains a few scripts and
metadata files that we have used to create almost 500 apptainers.  We
have focussed on automation, as much as possible.

In recent times, there has been a shift toward a "zero trust" security
model.  At JCU, a trusted source is an organisation with a focus on IT
security - e.g., where security advisaries patches are routinely issued.
Image repositories such as dockerhub, shpc, & biocontainers are not (at
this time) considered to be trusted sources.  Therefore, JCU has adopted
a policy of building all containers from a definition file.

Ultimately, this repository will contain every apptainer definition file
created by JCU HPC staff.  The scripts contained in this repository have
been created to generate definition files and/or apptainer images.

REPOSITORY CREATORS

Dr. Whitney Mallett
Mr. Wayne Spagnol

