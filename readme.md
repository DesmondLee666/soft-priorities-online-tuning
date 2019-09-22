  ##Real-time tuning soft task priorities with quadratic programming.

  Abstract— When robot simultaneously executes multiple
tasks with potential incompatibilities, in order to realize objectives and satisfy constraints, how to assign appropriate
priorities to each task is an open research problem. Most of
the existing methods are only aimed at tuning task weights in
static scenario. In this paper, for the scenario with randomly
dynamic factors, we propose a real-time task priorities tuning
method based on global objectives and constraints to deal with
conflicting tasks for adapting environmental changes. The soft
task priorities are real-time computed by a constrained optimization problem at each time point. For fast computation and
smooth transition to task weights, we transform the problem to
the formation of quadratic programming. We benchmark our
method on a simulated 6 DOF UR5 arm comparing with realtime Bayesian Optimization tuning and no-tuning. And we also
validate the effectiveness of our method in experiments with
randomly dynamic obstacle or target.
