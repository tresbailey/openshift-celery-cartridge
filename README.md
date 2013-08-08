openshift-celery-cartridge
==========================

Cartridge to Expose Celery as a Daemon on OpenShift

Environment Variables
---------------------

- OPENSHIFT_CELERY_IMPORTS : Defines the modules that celery should import.  Currently only supports 1 module import path

Currently only supports MongoDB as backend for queues, but in progress to support more environment variables to allow vairous backends and configurations.
