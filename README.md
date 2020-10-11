# DOREMI
## MIDI-REMI-TXT-REMI-MIDI bi-directional MIDI processor for music generation/composition with NLP-based Music AI architectures.
***
### Based on the absolutely fantastic proposal/repo/code by Yating Music https://github.com/YatingMusic/remi
***

Original REMI description and original citation is below:

REMI, which stands for REvamped MIDI-derived events, is a new event representation we propose for converting MIDI scores into text-like discrete tokens. Compared to the MIDI-like event representation adopted in exising Transformer-based music composition models, REMI provides sequence models a metrical context for modeling the rhythmic patterns of music. Using REMI as the event representation, an AI model can be trained to generate minute-long Pop piano music with expressive, coherent and clear structure of rhythm and harmony, without needing any post-processing to refine the result. The model also provides controllability of local tempo changes and chord progression.

@inproceedings{huang2020pop,
  title={Pop music transformer: Beat-based modeling and generation of expressive pop piano compositions},
  author={Huang, Yu-Siang and Yang, Yi-Hsuan},
  booktitle={Proceedings of the 28th ACM international conference on Multimedia},
  year={2020}
}
