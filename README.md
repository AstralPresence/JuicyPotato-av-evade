# JuicyPotato_av_evade

the publicly available binary file is detected by the McAfee AV. 

The AV signature is based on the embedded string that contains the path to the generated PDB file.

As this is an artifact of the compilation process, detection can be evaded by compiling JuicyPotato without the /DEBUG flag. 

The exe in this repo has been Compiled without the /DEBUG option.
