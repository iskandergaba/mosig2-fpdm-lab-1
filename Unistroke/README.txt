This is a short README file for the Unistroke dataset, used for the first lab of FPDM.

The unistroke dataset captures the following captial letters: A, E, H, L, O, Q. For each of these letters you have 50 files (numbered from 1 to 50). In each of the files you have a sequence of (x, y) coordinates of a pointer drawing a capital letter (among the ones listed before). Let us denote the coordinates in the file as x[t] and y[t], where t is the time index, corresponding to the rows in the text files. The coordinates (x[t],y[t]) correspond to the position of the pointer at time t. However, we will be working with the direction instead of the position. You need to compute the direction at time t, as the normalised vector from position (x[t],y[t]) to position (x[t+1],y[t+1]).

Suggestions/comments:
- Sometimes there are errors (during the capture). Be sure to plot all data and to clean it if necessary, before you start working with it.
- Since we are working in 2D, you can understand the meaning of the data coordinates. Be sure that you understand what x and y mean, and therefore what the associated normalised vector means.
- As suggested in the lab document, you can start with A, and then move ahead.
