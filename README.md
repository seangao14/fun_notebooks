# fun_notebooks  

### note: some of the models are too big so I'm storing them all in a folder "models" and they are gitignored, but the training loops should be in all the notebooks

- smart_stonks: using LSTM to predict stocks, in progress.
- hans_zimmer: using LSTM to generate coggers music.
  - wav files are hard to work with, generated somewhat audible music ([schlong_gen](https://github.com/seangao14/fun_notebooks/blob/master/data/hans_zimmer/schlong_gen.wav))
  - currently only able to feed 1 second of sequence (downsampled from 44.1khz to 8khz) on a RTX 2080 before running out of VRAM
  - with more compute better music may be generated, although I would not recommend working directly with wav files
