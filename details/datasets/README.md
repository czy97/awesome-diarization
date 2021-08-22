# Diarization Datasets

## Diarization Datasets
| Audio | Diarization ground truth | Language | Pricing | Additional information |
| ----- | ------------------------ | -------- | ------- | ---------------------- |
| [2000 NIST Speaker Recognition Evaluation](https://catalog.ldc.upenn.edu/LDC2001S97) | [Disk-6 (Switchboard)](https://github.com/google/speaker-id/tree/master/publications/LstmDiarization/evaluation/NIST_SRE2000/Disk6_ground_truth), [Disk-8  (CALLHOME)](https://github.com/google/speaker-id/tree/master/publications/LstmDiarization/evaluation/NIST_SRE2000/Disk8_ground_truth) | Multiple | $2400.00 | [Evaluation Plan](https://www.nist.gov/sites/default/files/documents/2017/09/26/spk-2000-plan-v1.0.htm_.pdf) |
| [2003 NIST Rich Transcription Evaluation Data](https://catalog.ldc.upenn.edu/LDC2007S10) | Together with audios | en, ar, zh | $2000.00 | telephone speech, broadcast news |
| [CALLHOME American English Speech](https://catalog.ldc.upenn.edu/LDC97S42) | [CALLHOME American English Transcripts](https://catalog.ldc.upenn.edu/LDC97T14) | en | $1500.00 + $1000.00| [CH109 whitelist](https://github.com/google/speaker-id/blob/master/publications/LstmDiarization/evaluation/CALLHOME_American_English/ch109_whitelist.txt) |
| [The ICSI Meeting Corpus](http://groups.inf.ed.ac.uk/ami/icsi/) | Together with audios | en | Free | [License](http://groups.inf.ed.ac.uk/ami/icsi/license.shtml) |
| [The AMI Meeting Corpus](http://groups.inf.ed.ac.uk/ami/corpus/) | Together with audios (need to be processed) | Multiple | Free | [License](http://groups.inf.ed.ac.uk/ami/corpus/license.shtml) |
| [Fisher English Training Speech Part 1 Speech](https://catalog.ldc.upenn.edu/LDC2004S13) | [Fisher English Training Speech Part 1 Transcripts](https://catalog.ldc.upenn.edu/LDC2004T19)| en | $7000.00 + $1000.00 |
| [Fisher English Training Part 2, Speech](https://catalog.ldc.upenn.edu/LDC2005S13) | [Fisher English Training Part 2, Transcripts](https://catalog.ldc.upenn.edu/LDC2005T19) | en | $7000.00 + $1000.00 |
| [VoxConverse](https://github.com/joonson/voxconverse) | TBD | TBD | Free | VoxConverse is an audio-visual diarisation dataset consisting of over 50 hours of multispeaker clips of human speech, extracted from YouTube videos |

## Speaker Embedding Training Sets
| Name | Utterances | Speakers | Language | Pricing | Additional information |
| ---- | ---------- | -------- | -------- | ------- | ---------------------- |
| [TIMIT](https://catalog.ldc.upenn.edu/LDC93S1) | 6K+ | 630 | en | $250.00 | Published in 1993, the TIMIT corpus of read speech is one of the earliest speaker recognition datasets. |
| [VCTK](https://homepages.inf.ed.ac.uk/jyamagis/page3/page58/page58.html) | 43K+ | 109 | en | Free | Most were selected from a newspaper plus the Rainbow Passage and an elicitation paragraph intended to identify the speaker's accent. |
| [LibriSpeech](http://www.openslr.org/12) | 292K | 2K+ | en | Free | Large-scale (1000 hours) corpus of read English speech. |
| [LibriVox](https://librivox.org/) | 180K | 9K+ | Multiple | Free | Free public domain audiobooks. LibriSpeech is a processed subset of LibriVox. Each original unsegmented utterance could be very long. |
| [VoxCeleb 1&2](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/) | 1M+ | 7K | Multiple | Free | VoxCeleb is an audio-visual dataset consisting of short clips of human speech, extracted from interview videos uploaded to YouTube. |
| [The Spoken Wikipedia Corpora](https://nats.gitlab.io/swc/) | 5K | 879 | en, de, nl | Free | Volunteer readers reading Wikipedia articles. |
| [CN-Celeb](http://www.openslr.org/82/) | 130K+ | 1K | zh | Free | A Free Chinese Speaker Recognition Corpus Released by CSLT@Tsinghua University. |
| [BookTubeSpeech](https://users.wpi.edu/~jrwhitehill/BookTubeSpeech/index.html) | 8K | 8K | en | Free | Audio samples extracted from BookTube videos - videos where people share their opinions on books - from YouTube. The dataset can be downloaded using [BookTubeSpeech-download](https://github.com/wq2012/BookTubeSpeech-download). |
| [DeepMine](http://data.deepmine.ir/en/index.html) | 540K | 1850 | fa, en | Unknown | A speech database in Persian and English designed to build and evaluate speaker verification, as well as Persian ASR systems. |
| [NISP-Dataset](https://github.com/iiscleap/NISP-Dataset) | ? | 345 | hi, kn, ml, ta, te (all Indian languages) | Free | This dataset contains speech recordings along with speaker physical parameters (height, weight, ... ) as well as regional information and linguistic information. |

## Useful Information for Diarization

| Audio                                                        | Total Duration      | Avg Utt Duration | Utt # | Overlap Ratio | Spk# per Utt |
| ------------------------------------------------------------ | ------------------- | ---------------- | ----- | ------------- | ------------ |
| [2000 NIST Speaker Recognition Evaluation](https://catalog.ldc.upenn.edu/LDC2001S97) |                     |                  |       |               |              |
| [2003 NIST Rich Transcription Evaluation Data](https://catalog.ldc.upenn.edu/LDC2007S10) |                     |                  |       |               |              |
| [CALLHOME American English Speech](https://catalog.ldc.upenn.edu/LDC97S42) |                     |                  |       |               |              |
| [The ICSI Meeting Corpus](http://groups.inf.ed.ac.uk/ami/icsi/) |                     |                  |       |               |              |
| [The AMI Meeting Corpus](http://groups.inf.ed.ac.uk/ami/corpus/) | 108h (with silence) | 35m              | 2224  | Low           | 4            |
| [Fisher English Training Speech Part 1 Speech](https://catalog.ldc.upenn.edu/LDC2004S13) |                     |                  |       |               |              |
| [Fisher English Training Part 2, Speech](https://catalog.ldc.upenn.edu/LDC2005S13) |                     |                  |       |               |              |
| [VoxConverse](https://github.com/joonson/voxconverse)        |                     |                  |       |               |              |
