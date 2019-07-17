=============================
lenstronomy_extensions
=============================


Deploys lenstronomy applications, examples and analysis scripts for lens modelling

Acompanies lenstronomy release version 0.9.0. ``lenstronomy`` is available through the pypi packaging index:
>>> pip install lenstronomy --user
If you are using the GitHub branch of ``lenstronomy``, you may be a bit ahead of the notebooks.
Get in touch with Simon Birrer (sibirrer@gmail.com) if you encounter problems.




Example notebooks
-----------------

We have made an extension module available here.
You can find simple examle notebooks for various cases.

* `Quadrupoly lensed quasar modelling <https://github.com/sibirrer/lenstronomy_extensions/blob/master/lenstronomy_extensions/Notebooks/quad_model.ipynb>`_
* `Double lensed quasar modelling <https://github.com/sibirrer/lenstronomy_extensions/blob/master/lenstronomy_extensions/Notebooks/double_model.ipynb>`_
* `Time-delay cosmography <https://github.com/sibirrer/lenstronomy_extensions/blob/master/lenstronomy_extensions/Notebooks/time-delay%20cosmography.ipynb>`_
* `Source reconstruction and deconvolution with Shapelets <https://github.com/sibirrer/lenstronomy_extensions/blob/master/lenstronomy_extensions/Notebooks/shapelet_source_modelling.ipynb>`_
* `Solving the lens equation <https://github.com/sibirrer/lenstronomy_extensions/blob/master/lenstronomy_extensions/Notebooks/shapelet_source_modelling.ipynb>`_
* `Measuring cosmic shear with Einstein rings <https://github.com/sibirrer/lenstronomy_extensions/blob/master/lenstronomy_extensions/Notebooks/EinsteinRingShear_simulations.ipynb>`_
* `Fitting of galaxy light profiles, like e.g. GALFIT <https://github.com/sibirrer/lenstronomy_extensions/blob/master/lenstronomy_extensions/Notebooks/galfitting.ipynb>`_
* `Quasar-host galaxy decomposition <https://github.com/sibirrer/lenstronomy_extensions/blob/master/lenstronomy_extensions/Notebooks/quasar-host%20decomposition.ipynb>`_
* `Hiding and seeking a single subclump <https://github.com/sibirrer/lenstronomy_extensions/blob/master/lenstronomy_extensions/Notebooks/substructure_challenge_simple.ipynb>`_
* `Mock generation of realistic images with substructure in the lens <https://github.com/sibirrer/lenstronomy_extensions/blob/master/lenstronomy_extensions/Notebooks/substructure_challenge_mock_production.ipynb>`_
* `Mock simulation API with multi color models <https://github.com/sibirrer/lenstronomy_extensions/blob/master/lenstronomy_extensions/Notebooks/simulation_api.ipynb>`_
* `Example of numerical ray-tracing and convolution options <https://github.com/sibirrer/lenstronomy_extensions/blob/master/lenstronomy_extensions/Notebooks/lenstronomy_numerics.ipynb>`_


Mailing list
------------

You can join the **lenstronomy** mailing list by signing up on the
`google groups page <https://groups.google.com/forum/#!forum/lenstronomy>`_.

The email list is meant to provide a communication platform between users and developers. You can ask questions,
and suggest new features. New releases will be announced via this mailing list.

If you encounter errors or problems with **lenstronomy**, please let us know!


Shapelet reconstruction demonstration movies
--------------------------------------------

We provide some examples where a real galaxy has been lensed and then been reconstructed by a shapelet basis set.

* `HST quality data with perfect knowledge of the lens model <http://www.astro.ucla.edu/~sibirrer/video/true_reconstruct.mp4>`_
* `HST quality with a clump hidden in the data <http://www.astro.ucla.edu/~sibirrer/video/clump_reconstruct.mp4>`_
* `Extremely large telescope quality data with a clump hidden in the data <http://www.astro.ucla.edu/~sibirrer/video/TMT_high_res_clump_reconstruct.mp4>`_



Attribution
-----------
The design concept of ``lenstronomy`` are reported in
`Birrer & Amara 2018 <https://arxiv.org/abs/1803.09746v1>`_. Please cite this paper whenever you publish
results that made use of ``lenstronomy``. Please also cite `Birrer et al 2015 <http://adsabs.harvard.edu/abs/2015ApJ...813..102B>`_
when you make use of the ``lenstronomy`` work-flow or the Shapelet source reconstruction. Please make sure to cite also
the relevant work that was implemented in ``lenstronomy``, as described in the release paper.
