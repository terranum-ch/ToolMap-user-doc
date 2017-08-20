Attribution
======================

This topic relate all the strategies concerning the attribution issues.

.. tip:: Since the ToolMap version *"Nendaz 2.5"* The object kind attribution system has been remodeled. The new principle is not to replace the attribution anymore but to modify it adding consecutively new objects.


Shortcuts
----------------------------

This change of approach makes the use of the shortcuts much more versatile. Previously you had to anticipate the features with multiple objects to create the appropriate shortcuts. While now, the shortcuts will only add their object(s) to the selected feature(s) giving you a greater liberty of use. They can also be used in series, if you hit three different shortcuts on the same selection it will recieve all the attributes defines by the shortcuts.

How and how much shortcuts you create shall be really dependent of your vectorization style, but it is hardly a lost of time to create a few on the most current objects.

Batch attribution
----------------------------

In the case you have a large quantity of small features which have attributes, it can be humdrum to do it one after the other. To prevent such boring work, you can select all the features with the same characteristics to attribute them at the same time using the option :ref:`object-attribute-batch` :kbd:`Ctrl+Alt+A)`.

You could differenciate two possible cases where this option could become very profitable:

  * You have some features, the characteristics are the same for all of them: Select all the features using a query and attribute them.
  * You have a lot of features, the biggest part of them have the same characteristics: Select all the features and give them the most usual attributes. Rework afterward the few having a different attribution.

