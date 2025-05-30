.. cellpose master

cellpose
===================================

cellpose is an anatomical segmentation algorithm written in Python 3. For support, please open 
an `issue`_. We make pip installable releases of cellpose available on `pypi`_. You
can install it as ``pip install cellpose[gui]``.

**Cellpose-SAM: superhuman generalization for cellular segmentation** now available!

- run Cellpose-SAM in the cloud (no install) at `Hugging Face <https://huggingface.co/spaces/mouseland/cellpose>`_. 
- `paper <https://www.biorxiv.org/content/10.1101/2025.04.28.651001v1>`_ on biorxiv
- `talk <https://www.youtube.com/watch?v=KIdYXgQemcI>`_



**See details on migrating from Cellpose 3 to 4 in** :ref:`Settings`

Old releases:
-----------------------------

Cellpose3: one-click image restoration for improved cellular segmentation

- `paper <https://www.biorxiv.org/content/10.1101/2024.02.10.579780v1>`_ on biorxiv
- `thread <https://neuromatch.social/@computingnature/111932247922392030>`_

Cellpose 2.0: how to train your own model

- `paper <https://www.biorxiv.org/content/10.1101/2022.04.01.486764v1>`_ on biorxiv
- `talk <https://www.youtube.com/watch?v=3ydtAhfq6H0>`_
- twitter `thread <https://twitter.com/marius10p/status/1511415409047650307?s=20&t=umTVIG1CFKIWHYMrQqFKyQ>`_
- human-in-the-loop training protocol `video <https://youtu.be/3Y1VKcxjNy4>`_

Cellpose: a generalist algorithm for cellular segmentation

- `paper <https://www.biorxiv.org/content/10.1101/2020.02.02.931238v1>`_ on biorxiv (see figure 1 below) and in `nature methods <https://t.co/kBMXmPp3Yn?amp=1>`_
- twitter `thread <https://twitter.com/computingnature/status/1224477812763119617>`_
- Marius's `talk <https://www.youtube.com/watch?v=7y9d4VIKiS8>`_

.. image:: _static/fig1.PNG
    :width: 1200px
    :align: center
    :alt: fig1

.. _cellpose.org: http://www.cellpose.org
.. _issue: https://github.com/MouseLand/cellpose/issues
.. _pypi: https://pypi.org/project/cellpose/


.. toctree::
   :maxdepth: 3
   :caption: Basics:

   installation
   gui
   inputs
   settings
   outputs
   do3d
   models
   restore
   train
   benchmark
   distributed
   openvino
   faq

.. toctree::
   :maxdepth: 3
   :caption: Examples:

   notebook
   command
   

.. toctree::
   :caption: Reference:

   api
   cli
