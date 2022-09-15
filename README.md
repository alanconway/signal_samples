# Signal sample data

A collection of observability signal samples in JSON format.

*.json files: contain a series of JSON objects (not a JSON array, just the objects)
where each object represents a single instance of the given signal type.

Makefile: contains commands used to generate the data.
You need to be logged in to an openshift cluster as kubeadmin, with openshift logging installed.

The samples are not representative of the variety of signals, and are not well organized - this will improve
They are useful to get a feel for the basic structure of the signal data.

Formal data-model documentation (more coming as I track it down):

- ViaQ log format (upstream), used by openshift logging: https://github.com/ViaQ/documentation

