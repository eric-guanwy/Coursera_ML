If your get errors like "JSONparser:invalidFormat: Outer level structure must be an object or an array" 
or "jsonBody value is not a valid JSON String" when you are using Octave 4.0.0
https://www.coursera.org/learn/machine-learning/discussions/vgCyrQoMEeWv5yIAC00Eog

This patch works around the defective printf() function in Octave 4.0.0

Instructions:

1) Extract the contents of this zip file to the "machine-learning-ex?/ex?/" folder 
for each programming exercise.  Be sure you preserve the folder attributes and the
other files in that subfolder.

This patch will overwrite these two existing files:
  lib/makeValidFieldName.m
  lib/jsonlab/loadjson.m
It will add the following new file:
  lib/xxNumToHexStr.m

2) Restart Octave or MATLAB after installing the patch.
