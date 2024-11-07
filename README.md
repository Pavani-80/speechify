from gtts import gTTS  # Correct import
from playsound import playsound

audio = "speech.mp3"
language = 'en'

# Create a gTTS object
sp = gTTS(text="Hello everyone, this is a great step towards my first project ", lang=language, slow=False)
sp.save(audio)

# Play the audio file
playsound(audio)
print("=====audio is playing=====")
