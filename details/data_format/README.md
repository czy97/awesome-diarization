# The Data Format for Diarization Labels

The original defination of the Rich Transcription Time Marked (RTTM) files is in  [NIST RT-09 evaluation plan](https://web.archive.org/web/20100606041157if_/http://www.itl.nist.gov/iad/mig/tests/rt/2009/docs/rt09-meeting-eval-plan-v2.pdf) (which is no available now). The description below is refered from [RTTM](https://github.com/nryant/dscore#rttm).

### RTTM

Rich Transcription Time Marked (RTTM) files are space-delimited text files containing one turn per line, each line containing ten fields:

- `Type` -- segment type; should always by `SPEAKER`
- `File ID` -- file name; basename of the recording minus extension (e.g., `rec1_a`)
- `Channel ID` -- channel (1-indexed) that turn is on; should always be `1`
- `Turn Onset` -- onset of turn in seconds from beginning of recording
- `Turn Duration` -- duration of turn in seconds
- `Orthography Field` -- should always by `<NA>`
- `Speaker Type` -- should always be `<NA>`
- `Speaker Name` -- name of speaker of turn; should be unique within scope of each file
- `Confidence Score` -- system confidence (probability) that information is correct; should always be `<NA>`
- `Signal Lookahead Time` -- should always be `<NA>`

For instance:

```
SPEAKER CMU_20020319-1400_d01_NONE 1 130.430000 2.350 <NA> <NA> juliet <NA> <NA>
SPEAKER CMU_20020319-1400_d01_NONE 1 157.610000 3.060 <NA> <NA> tbc <NA> <NA>
SPEAKER CMU_20020319-1400_d01_NONE 1 130.490000 0.450 <NA> <NA> chek <NA> <NA>
```

