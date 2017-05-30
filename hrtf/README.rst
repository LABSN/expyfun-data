These files each contain all fo the information necessary to interpolate
between known BRIRs from the cipic library. In some pairs there were phase
errors due to unwrapping. These could not be corrected generally so they have
been manually corrected by subtracting 2pi from all points after the
problematic index.

The files contains the following lists which each contain information for one 
pair of angles:
    hrtf_phase      Unwrapped phase for each HRTF
    hrtf_amp        Magnitude of each HRTF
    pairs           Known angles of the two HRTFs (derived from BRIRs in the
                                                   cipic library)
Also included in the files are:
    fs              Sampling frequency of the BRIRs
    angles          List of angles for the original BRIRs
    
For python code used to generate the files see this gist:
https://gist.github.com/maddycapp27/f39ebeeeb16cbd4eb69d74088f2fafd3