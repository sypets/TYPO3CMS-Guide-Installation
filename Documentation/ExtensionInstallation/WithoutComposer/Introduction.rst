.. include:: /Includes.txt

============
Introduction
============

.. tip::

   If you have installed TYPO3 with Composer, you should also
   :ref:`install extensions with Composer <install-extension-with-composer>`.

Common terms
============

In the context of the TYPO3 extension manager ("EM"), the words "install" and "uninstall" differ from their mainstream
meaning. To avoid mixing these terms up with the other EM verbs, here is a clarification:

Import
  Downloading an extension from TER and copying it to :file:`typo3conf/ext/`.

Install
  Activating the already imported extension inside the extension manager and performing database changes mandated by the extension.

Uninstall
  Deactivating an extension, but leaving it on the disk.

Remove
  Deleting extension files permanently from disk.
