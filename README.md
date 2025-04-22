🎙️ Speech Recognition & Acoustic Analysis Using Python

This project is a complete walkthrough of fundamental speech signal processing tasks using Python. It demonstrates how to extract useful acoustic features from audio files, visualize speech signals, convert speech to text, detect the language, and reduce noise in audio recordings.


📌 Project Highlights

🔊 1. Audio Signal Loading & Playback
- Load '.wav'files using Librosa
- Play audio directly in notebook using IPython.display

📈 2. Acoustic Feature Extraction
Extract key audio features including:
- Pitch (Fundamental Frequency) – Represents tone
- Spectral Centroid – Indicates brightness of the sound
- RMS Energy – Reflects loudness

📊 3. Signal Visualization
- Waveform Plot – Shows time-domain representation
- Spectrogram Plot – Visualizes frequency content over time

🗣️ 4. Speech-to-Text Transcription
- Uses 'speech_recognition' with Google Speech Recognition API
- Automatically converts spoken audio into text

🌍 5. Language Detection
- Uses 'langid' to detect the language of the transcribed text

🔇 6. Noise Reduction
- Reduce background noise using 'noisereduce' library
- Compare original vs cleaned audio with waveform plots


📂 Files Used

| File Name                         | Description                               |
|-----------------------------------|--------------------------------------------|
| 'BAK.wav'                         | Sample clean speech audio                  |
| '4 (1).wav'                       | Audio for speech recognition               |
| 'crowd-noise-284490 (1).wav'      | Noisy background audio for noise reduction |



🧪 Technologies & Libraries

- 'librosa' – For audio loading & feature extraction
- 'matplotlib' – Visualization (waveform, spectrogram)
- 'IPython.display' – To play audio inside notebook
- 'speech_recognition' – For converting speech to text
- 'langid' – Language classification
- 'noisereduce' – Denoising audio
- 'soundfile' – Saving audio to file
- 'warnings', 'numpy', 'torch' – Supporting libraries



🚀 How to Run

1. Clone the repository
   
   git clone https://github.com/yourusername/speech-recognition-analysis.git
   cd speech-recognition-analysis
   

2. Install required libraries
   
   pip install -r requirements.txt
   

3. Open the Jupyter Notebook
   
   jupyter notebook
   

4. Run each cell step-by-step to:
   - Load and visualize audio
   - Extract acoustic features 
   - Transcribe speech
   - Detect spoken language
   - Apply noise reduction and compare results


🖼️ Sample Outputs

- ✅ Acoustic Feature Values
  - Pitch: 124.78 Hz
  - Spectral Centroid: 2483.42 Hz
  - Volume (RMS): 0.0361

- ✅ Transcription
  📝 Recognized Text: "Hello, this is a speech recognition demo."
  

- ✅ Language Detection
  🌍 Detected Language: en
  

- ✅ Waveform Visuals
  - Cleaned vs Noisy signal comparison





