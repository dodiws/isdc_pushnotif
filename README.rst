=========
pushnotif
=========

Send notification email to users regarding flood, avalanche, earthquake event.
Optional Module for ASDC

Quick start
-----------

1. Add "pushnotif" to your ISDC_ADDITIONAL_APPS setting like this:

   ISDC_ADDITIONAL_APPS = [
       ...
       'pushnotif',
   ]

   For development in virtualenv add pushnotif_PROJECT_DIR path to VENV_NAME/bin/activate:
       export PYTHONPATH=${PYTHONPATH}:\
       ${HOME}/pushnotif_PROJECT_DIR
