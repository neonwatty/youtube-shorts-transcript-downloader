[![HuggingFace Space](https://img.shields.io/badge/🤗-HuggingFace%20Space-cyan.svg)](https://huggingface.co/spaces/neonwatty/youtube_shorts_transcript_downloader)  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jermwatt/youtube_transcript_downloader/blob/main/transcript_downloader_walkthrough.ipynb)
<a href="https://www.youtube.com/watch?v=Z7Zm3GQ8q-U" target="_parent"><img src="https://badges.aleen42.com/src/youtube.svg" alt="Youtube"/></a> [![Python application](https://github.com/neonwatty/youtube_shorts_transcript_downloader/actions/workflows/python-app.yml/badge.svg)](https://github.com/neonwatty/youtube_shorts_transcript_downloader/actions/workflows/python-app.yml/python-app.yml)


# A free app for downloading YouTube Shorts transcripts

Built with Python and Streamlit.  Easily self-host.

Download transcripts for Youtube Shorts by dragging and dropping a text file containing valid Youtube Shorts urls into a simple streamlit app (shown below).

<img align="center" src="https://github.com/jermwatt/readme_gifs/blob/main/yt_shorts_demo.gif" height="325">

This repo also illustrates how to pull transcripts step-by-step in the `transcript_downloader_walkthrough.ipynb` notebook.

## Install instructions

To get setup to run the notebook and strealit demo first install the requirements for this project by pasting the below in your terminal.

```python
pip install -r requirements.txt
```


## Instructions for using the streamlit app

Use in browser directly by clicking here [![HuggingFace Space](https://img.shields.io/badge/🤗-HuggingFace%20Space-cyan.svg)](https://huggingface.co/spaces/neonwatty/youtube_shorts_transcript_downloader).

Start the streamlit app up locally

```python
python -m streamlit run youtube_shorts_transcript_downloader/app.py
```

In either case you can now drag and drop `.txt` files containing Youtube Shorts urls - one url per line - into the app for batch transcript fetching.
