# apptainer
A JCU repository for apptainer provisioning.

This repository, created by JCU HPC staff, contains a few scripts and
metadata files that we have used to create almost 500 apptainers.  We
have focussed on automation, as much as possible.

In recent times, there has been a shift toward a "zero trust" security
model.  At JCU, a trusted source is an organisation with a focus on IT
security - e.g., where security advisaries & patches are routinely
issued.  Image repositories such as dockerhub, shpc, & biocontainers
are not (at this time) considered to be trusted sources.  Therefore,
JCU has adopted a policy of building all containers from a definition
file.

Sustainability is also important to JCU, so we have created a script
that builds a container image that uses untrusted conda environments.
In some cases this is unavoidable, because some software developers
choose to only document their software in a conda context.

Ultimately, this repository will contain every apptainer definition file
created by JCU HPC staff.  The scripts contained in this repository have
been created to generate definition files and/or apptainer images.  There
are many JCU HPC specific configuration items in this repository - this
is due to our "minimum viable product" approach.  For example, we build
ubuntu apptainers (ubuntu-*.sif) that are used to decrease the time it
takes for other apptainers to be built.


-------------------
REPOSITORY CREATORS

Dr. Whitney Mallett
Mr. Wayne Spagnol
-------------------
