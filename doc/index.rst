.. Example documentation master file, created by
   sphinx-quickstart on Sat Sep 23 20:35:12 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to CARC's QuickBytes!
=============================

Linux introduction
------------------
.. toctree::
   :maxdepth: 2

   linux_intro.md

Running jobs
------------
.. toctree::
   :maxdepth: 2

   logging_in.md
   ssh_keygen_config.md
   transfer_data.md
   pbs-torque.md
   pbs_scripts2.md
   submitting_jobs.md
   checking_on_running_jobs.md
   module_management.md
   Intro_to_slurm.md
   pbs2slurm.md
   slurm_accounting.md
   GNU%20Parallel.md

Applications software
---------------------
.. toctree::
   :maxdepth: 2

MATLAB
^^^^^^
.. toctree::
   :maxdepth: 2

   running_matlab_jobs.md
   ParallelMatlabServer.md
   Parallel%20MATLAB%20profile%20setup%20and%20batch%20submission.md
   Using%20GPUs%20on%20Xena%20with%20MATLAB.md
   MATLAB%20Deep%20Learning%20on%20Xena.md

JupyterHub
^^^^^^^^^^
.. toctree::
   :maxdepth: 2

   parallelization_with%20Jupyterhub_using_mpi.md
   Conda_JupyterHub.md
   julia_with_jupyterhub.md

Conda
^^^^^
.. toctree::
   :maxdepth: 2

   anaconda_general_intro.md
   anaconda_intro.md
   anaconda_pip_channels.md

R
^
.. toctree::
   :maxdepth: 2

   R_usage.md
   R_at_CARC)
..   Parallel_R_with_Future.ipynb
   Gurobi%20optimizer%20with%20R.md

Machine Learning
^^^^^^^^^^^^^^^^
.. toctree::
   :maxdepth: 2

   Tensorflow_documentation.md
   PyTorch_1.9_Xena.md
..   PyTorch_Classifier_Xena%20.ipynb
..   multiGPU_tensorflow_tutorial.ipynb
   parallel_jupyterhub_with_dask_and_scikit-learn.md

Bioinformatics
^^^^^^^^^^^^^^
.. toctree::
   :maxdepth: 2

   GATK_QuickByte.md
   genome_evaluation.md
   psmc_quickbyte.md
   Stacks_quickbyte.md
   Metabarcoding.md
   Beast_at_CARC.md
   msprime_quickbyte.md

Computational Chemistry
^^^^^^^^^^^^^^^^^^^^^^^
.. toctree::
   :maxdepth: 2

   orca_wheeler_taos.md
   alphafold.md

Computational Immunology
^^^^^^^^^^^^^^^^^^^^^^^^
.. toctree::
   :maxdepth: 2

   SimCov.md

Astronomy
^^^^^^^^^
.. toctree::
   :maxdepth: 2

   mpiCASA.md

Paraview
^^^^^^^^
.. toctree::
   :maxdepth: 2

   paraview.md
   Paraview_Hopper.md
   
General
^^^^^^^
.. toctree::
   :maxdepth: 2

   singularity-markdown-version.md
   haskell.md
   X11_forwarding.md
   spark.md
..   CuPy_on_CARC.ipynb
   install_perl_libraries.md
