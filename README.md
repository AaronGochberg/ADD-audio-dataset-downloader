# ADD: audio-dataset-downloader
Simple Python CLI script for downloading N-hours of audio from Youtube, based on a list of music genres.



### Installation instructions:

> pip install -r requirements.txt

### Run the script:

> python add.py

### NOTE (as of Oct 2024)
Due to changes in the YouTube platform, pytube may throw an 'RegexMatchError', preventing downloading when running the add.py script.

To fix this, edit cipher.py in the pytube package, following this comment https://github.com/pytube/pytube/issues/1954#issuecomment-2218287594
