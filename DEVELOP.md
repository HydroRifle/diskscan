# Developing

## Debug build

To create a debug build you can tell cmake:

    cmake -DCMAKE_BUILD_TYPE=DEBUG .

## Updating Libraries

Update libscsicmd:

    git subtree pull --squash --prefix libscsicmd https://github.com/baruch/libscsicmd master

Update libprogressbar:

    git subtree pull --squash --prefix progressbar https://github.com/doches/progressbar master

Update HdrHistogram:

    git subtree pull --squash --prefix hdrhistogram https://github.com/HdrHistogram/HdrHistogram_c master
