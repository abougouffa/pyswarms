========
Features
========


Single-Objective Optimizers
---------------------------

These are standard optimization techniques that aims to find the optima of a single objective function.

Continuous 
~~~~~~~~~~

Single-objective optimization where the search-space is continuous. Perfect for optimizing various
functions.

* :mod:`pyswarms.single.global_best` - classic global-best Particle Swarm Optimization algorithm with a star-topology. Every particle compares itself with the best-performing particle in the swarm.

* :mod:`pyswarms.single.local_best` - classic local-best Particle Swarm Optimization algorithm with a ring-topology. Every particle compares itself only with its nearest-neighbours as computed by a distance metric.


Discrete 
~~~~~~~~

Single-objective optimization where the search-space is discrete. Useful for job-scheduling, traveling
salesman, or any other sequence-based problems.

* :mod:`pyswarms.discrete.binary` - classic binary Particle Swarm Optimization algorithm without mutation. Uses a ring topology to choose its neighbours (but can be set to global).


Utilities
---------

Test Functions
~~~~~~~~~~~~~~

These functions can be used as benchmark tests for assessing the performance of the optimization
algorithm.

* :mod:`pyswarms.utils.functions.single_obj` - single-objective test functions
