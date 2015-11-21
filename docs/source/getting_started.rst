Getting Started
==============


::

    Pkg.add("Quandl")

Quick Start
-----------

To call Quandl, do as follows:

    using Quandl
    
You can add your unique Quandl download token if you choose. If you skip
this step, your calls will be anonymous.

::

    julia> set_auth_token("myauthtoken") # if you choose to use your unique Quandl.com token
