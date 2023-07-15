# audio_data
# Step 1 : Speaker Diarization
speaker_diarization.py, takes a YouTube URL as input, generates audio files (.wav) as output clustered according to speakers

**Requirements**

pydub library
yt_dlp library

Example usage :
python speaker_diarization.py https://www.youtube.com/***

# Step 2 : Speaker folder generation

Put all the audios belonging to one speaker in a folder

# Step 3 :  1 min chunk
1min_chunk.py converts the collected data of speaker in  folder into 1 min chunks takes folder name as input 

**Requirements**

pydub library

Example usage :
python 1min_chunk.py Elon_musk

