# sodestream at IETF 115

The [sodestream project](https://sodestream.github.io) aims to develop methods to improve distributed decision making in large organisations, using a combination of natural language processing and social network analysis.

This project relates to efforts to form a potential IRTF Research Group around "Researching Internet Standards Processes". A side meeting will be taking place on Thursday, November 10th, 15:30 to 16:30 (UTC+1) in-person (in Mezzanine 12) and online (via Zoom at https://uva-live.zoom.us/j/6365963924). Further information is available from https://pad.riseup.net/p/charterdiscussion-keep.
## Tools and datasets

The [ietfdata](https://github.com/glasgow-ipl/ietfdata) library provides a Python 3 interface to access the IETF Datatracker, RFC index, and mailing list archives. The library can also make use of a MongoDB instance as a cache, reducing the number of requests that are made directly to the Datatracker, improving performance, and reducing impact on the IETF's infrastructure. The library's README provides further setup information

We will provide on-site Hackathon attendees with a pre-populated MongoDB back-up, containing a snapshot of the mail archive and metadata fetched from the Datatracker.

An etherpad is available at https://pad.riseup.net/p/sodestream-IETF1115-Hackathon.

## Suggested Tasks

### Sentiment analysis of `ietf@ietf.org` postings

The `ietf@ietf.org` mailing list provides a forum for the broad discussion of IETF-related topics. Sentiment analysis techniques could be useful in characterising the tone, and levels of toxicity, in the interactions that take place on this, and other, IETF mailing lists. With historical data, these trends can be tracked over time, providing insight into how the IETF community is evolving.

### Entity resolution

The activities of IETF participants are spread across different datasets, including the Datatracker, mailing list archives, meeting minutes and attendance records, and GitHub repositories. In order to characterise the breadth of participant activity and interaction across these different sources, data about each individual needs to be linked together. This includes matching on names, and applying other heuristics.
  
### Characterising cross-area review

A broad base of reviewers is important for improving the quality of IETF documents. Mailing list data, combined with Datatracker records, allows us to determine the areas of expertise of participants. This can then be matched with formal (and informal) review notes to determine the extent to which documents receive cross-area review, and, further, at what point in the drafting process this occurs.

## Funding

The sodestream project is funded by the UK Engineering and Physical Sciences Research Council, under grants EP/S033564/1 and EP/S036075/1.
