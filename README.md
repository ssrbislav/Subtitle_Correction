# Subtitle Correction

Generate .srt file from video material.

Correct the subtitle timing based on generated .srt file with Google Speech-To-Text 


Necessary tools:
  * Jupyter Notebook
  * Python 3.x
  * Use Python pip to install all necessary libraries (pysrt, pydub, pyaudio, ffmpeg... )
  
 Instructions:
  * Clone the project repository
  * Run final.ipynb in Jupyter Notebook
  * Click on each cell, then Run (Execute: *Video to audio conversion*,
                                           *Sound filtration*,
                                           *Graph ploting*)
  * Before executing fourth cell, audio file in .wav format (generated in first cell) must be uploaded to Google Cloud
  * After the upload, run the cell (*uri* must contain the link to where the file is located on Google server)
  * // Shifting Subtitle cell is used to showcase the the way we correct the subtitle later if no file with 
  wrong timing is present
  * Execute other cells in order
  * Done!
