# youtube-bulk-transcript
A script that downloads all the available transcriptions for a specific YouTube channel or playlist.  

Use ```python collect_transcript.py --help``` to learn about the usage, but probably it's going to be something like:  

<code>python collect_transcript.py --type channel "https://www.youtube.com/@BenEater/videos" --folder ./ben-srt --format srt </code>

or 

<code>python collect_transcript.py --type playlist "https://www.youtube.com/playlist?list=PLk0fS18dI3_NAd8ZCopvIvvuSrR3bq_PL" --folder ./3blue1brown-fuzzy-txt --format pretty </code>


It's built on top of the [Youtube Transcript API](https://github.com/jdepoix/youtube-transcript-api/tree/master), which is the right choice to download single video transcripts.


