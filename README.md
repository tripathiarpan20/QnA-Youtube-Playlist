# Youtube-Playlist-QA


## Introduction  

Have you ever found a great playlist on YouTube that intruiging to you because of the rich information it holds about a certain topic & wished that you could get answers to your questions at your convenience without rewatching the whole playlist?  

Well look no further, the notebook provided in this repo works as follows:
* Generate an API key for [Youtube Data API v3](https://developers.google.com/youtube/v3) (follow the Step 1 in [this guide](https://developers.google.com/youtube/v3/quickstart/python?authuser=1)).
* Open the notebook, enter your API key and Playlist ID (details given in the notebook).
* Run the notebook.
* Get answers to your questions and have fun!


## Getting Started

Link to notebook: 

<a href="https://colab.research.google.com/gist/tripathiarpan20/d9a8476f5e7cb02ee35e47f99971a49f/-github-youtube-playlist-captions-question-answering.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/></a>
 
## Limitations

* Due to the traffic detection by Google, only playlists with <200 videos can be queried without missing any videos ([reference](https://github.com/jdepoix/youtube-transcript-api/issues/79)).
* The notebook works by fetching the publicly available English subtitles in the videos, which might have some issues related to auto-captioning, or might not have captions at all.
* The answers to the questions have to be present within the context of the Playlist videos for best results, although the notebook uses pretrained generative Transformer models from HuggingFace, hence it might be able to answer common questions.


## References
* [Haystack](https://github.com/deepset-ai/haystack)
* [youtube-transcript-api](https://github.com/jdepoix/youtube-transcript-api)
* [youtube-channel-transcript-api](https://github.com/danielcliu/youtube-channel-transcript-api)
* [HuggingFace](https://huggingface.co/)
* [Western Philosophy - Ted Ed](https://www.youtube.com/watch?v=SWlUKJIMge4&list=PLwxNMb28XmpeypJMHfNbJ4RAFkRtmAN3P)
* [Dark Souls 3 Lore - Vaatividya](https://www.youtube.com/watch?v=8UNdFzs0iqg&list=PLWLedd0Zw3c7TTg9J6yA5fd-554ojNlrF)