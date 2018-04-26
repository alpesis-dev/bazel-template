##############################################################################
Utilities: Bazel
##############################################################################

::

    $ bazel build //<folder>:<binary>
    $ bazel query --nohost_deps --noimplicit_deps 'deps(//hello:hello)' --output graph
