.. _api:

API
===


.. module:: pyaccurev

This part of the documentation covers all available functions for executing some of `AccuRev` commands.


AccuRev Class
-------------

.. autoclass:: AccuRev
   :members: 


AccuRev Workspace
-----------------

.. autoclass:: ARWorkspace
   :members:
   :exclude-members: workspace_dir_required, workspace_name_required

   .. automethod:: info()
   .. automethod:: change_stream(name)
