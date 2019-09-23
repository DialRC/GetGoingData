# GetGoingData

## Introduction
This repository contains data we collected via the GetGoing phone dialogue system starting from May 3 2019. This dataset includes Google ASR transcriptions and recordings for each call. For the first public version, we removed all calls from our developers (including advisors) and calls that have empty user speech. Some calls may be spam (machine speech), these are to be removed in the next version. 

To talk to the system, you can call +1(412)259-5311.

Please note the license for use of this data [License](#license). Please agree to this license before downloading the data.


## Description

Directory GGMASTER contains data from real users, and directory PhoneLetsGo contains data from paid (AMT) users. They both share the same directory structure as follows (an example for GGMASTER):

The dataset is divided by months. Each month of data has the following directory structure (an example for July, 2014):
```
GGMASTER  
│
└──logs
   │
   └───130b95bea148774bba89776aa1092b1 (a directory for each call)
   │    │   log.json (Google ASR transcription, system speech starts with TTS, and user speech start with USER)
   │    │   metadata.json (call information including uuid, encrypted phone number, and call date)
   │    │   recording.wav (recording in LINEAR16 encoding, 8000 sample rate Hertz)
   │
   └───2ccb37f8316b17fc8ea7260afb6550da
   |    |...
   |    |...
   |    |...
   │
   │
   └─── ...
```

## License
Please download and agree to the [`License`](LICENSE).

If you download and use the Let's Go data, you agree that you will cite it in all publications resulting from its use.

## Contacts
If you have more questions about the Let's Go systems and dataset. Please contact us:

[Alan W. Black](http://www.cs.cmu.edu/~awb/) (Carnegie Mellon University)

[Maxine Eskenazi](http://www.cs.cmu.edu/~max/) (Carnegie Mellon University)

[Yulan Feng](http://www.cs.cmu.edu/~yulanf/) (Carnegie Mellon University)

[Shikib Mehri](http://shikib.com) (Carnegie Mellon University)

## References
Shikib Mehri, Alan W Black, Maxine Eskenazi. [**CMU GetGoing: An Understandable and Memorable Dialog System for Seniors**](https://arxiv.org/pdf/1909.01322.pdf) In Workshop on Dialog for Good (DiGo) in SIGDIAL, 2019.
