# EDX
Useful functions for processing EDX measurement results
Usage: Source the file.
From a new R project, run
EDX()
to evaluate an EDX measurement pattern (cps ~ energy in keV).
Options:
wd = getwd(), smooth.deg = 1, min.peak.intensity = 100, peak.res = 12, bg.wm = 150, bg.ws = 200
wd is the working directory (the measurement files must be in the working directory, or the wd option must be set to the directory where the data is located)
smooth.deg is the degree of smoothing that is applied to the measured data
min.peak.intensity is the minimum intensity at which peaks are recognized as such
peak.res is the resolution at which peaks are searched for (i.e. the number of data points to compare a potential peak with)
bg.wm is the width of local window for minimization/maximization (background)
bg.ws is the width of local window for smoothing (background)
