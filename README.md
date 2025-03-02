### Desktop-Assistant-using-Python
# Create a new virtual environment
conda create -n assistant python=3.10
# Checkout the created virtual environment
conda env list
# Activate the virtual environment
conda activate assistant 

## first we need to setup your requirment 
SpeechRecognition
pyttsx3
PyAudio
wikipedia
streamlit
pipwin
gTTS
google-generativeai
# Run project  
streamlit run app.py
