# h5browsegrid
How to create a browse grid in Clarion H5 (Clarion 11.0.13401

Update to the Browse Grid example. 18 Nov 19

This is using Clarion 11.0.13401

There are some templates included that will need to be registered if you want to use them.

Things to know.

The skeleton for the GridCell control needs to be grid.htm (supplied with the appbroker)


The navigation bars don't work with the browse grid control.
You can place buttons on the GridCell group control (these can be within button groups as well).

*Note:- to get the full grid effect you need to define the the length of the lists using the following;

?Browse:1{PROP:Height} = 4000 (or whichever number you choose).
It is also possible to set the width using ?Browse:1{PROP:WIDTH} = 1000


For example if you want five columns across then makes sure that the GridCell control is at least a fifth of the width of the list box.
