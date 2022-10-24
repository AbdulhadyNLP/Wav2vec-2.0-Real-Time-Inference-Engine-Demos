# Wav2vec-2.0-Real-Time-Inference-Engine-Demos
demo VAD real time python microphone project install library requirement:
!pip install torch
!pip install transformers
!pip install speechrecognition

step install pyaudio from ubuntu 20.4
First we need to install portaudio modules: sudo apt-get install libasound-dev

  Download the portaudio archive from: http://files.portaudio.com/download.html

    Unzip the archive: tar -zxvf [portaudio.tgz]

    Enter the directory, then run: ./configure && make

    Install: sudo make install

    And finally: pip/pip3 install pyaudio

    Check the version of pyaudio, it should be 0.2.9

