# BigNeuron reconstruction sample set

This directory contains a set of reconstructions provided by the 
[BigNeuron](alleninstitute.org/bigneuron/) collaborators. There are two sorts
of reconstruction:

1. manual, gold standard reconstructions originally available 
   [here](https://github.com/BigNeuron/docs/wiki/Neuron-Annotation-Data)
   their filenames start with prefix "00".
2. Automated reconstructions from up to 44 tools (including variants/updates
   of the same tool). They are ordered (the number prefix in the filenames)
   by increasing average neuron distance (calculated from Vaa3D) to the gold
   standard reconstructions. "01" indicates the reconstrcution that is closest to
   the ground truth (by the metric).

These were collated by Xiaoxiao Liu at the time of the [BigNeuron Analysis 
Hackathon at Imperial College](https://github.com/BigNeuron/docs/wiki/BigNeuron-Imperial-Discussion-Notes)
and distributed to participants on 2016-01-20.

## License

Please note that these data are unpublished, in-progress outputs of the BigNeuron project
and should be treated as such. Please see [BigNeuron wiki](https://github.com/BigNeuron/docs/wiki/Neuron-Annotation-Data) for further details.

The use of these data presented here is constrained by the Rules to Participate
the BigNeuron project, as documented at the BigNeuron website http://alleninstitute.org/bigneuron/terms/.
