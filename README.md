GitForDelphi 
=================================
Delphi bindings to libgit2 <https://github.com/libgit2/libgit2>


All function exports from git2-0.dll have been converted, including
necessary structures. Some of the tests from libgit2 have been
converted and are all passing.

git2-0.dll built from Visual C++ 2010 Express is in the `binary` branch,
you can use it while in the master branch like this

    git checkout origin/binary -- git2-0.dll; git reset git2-0.dll

See `LIBGIT2_sha` file for the libgit2 commit that the dll and code are currently based on.

