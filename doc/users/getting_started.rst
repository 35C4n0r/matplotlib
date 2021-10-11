Getting started
===============

Installation
------------

.. container:: twocol

    .. container::

        Install using pip:

        .. code-block:: bash

            pip install matplotlib

    .. container::

        Install using conda:

        .. code-block:: bash

            conda install matplotlib

Further details are available in the :doc:`Installation Guide </users/installing>`.

Choosing a backend
------------------

Matplotlib needs a "backend" to render your figure, either in its own GUI window,
as part of a notebook, or saved as an image to disk.  If you need more information on 
choosing a backend, see :ref:`backends`.

Draw a first plot
-----------------

Here is a minimal example plot you can try out:

.. plot::
   :include-source:
   :align: center

   import matplotlib.pyplot as plt
   import numpy as np

   x = np.linspace(0, 2 * np.pi, 200)
   y = np.sin(x)

   fig, ax = plt.subplots()
   ax.plot(x, y)
   plt.show()


Where to go next
----------------

- Check out :doc:`Plot types </plot_types/index>` to get an overview of the
  types of plots you can create with Matplotlib.
- Learn Matplotlib from the ground up in the
  :doc:`Quick-start guide </tutorials/introductory/usage>`.
