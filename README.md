## Talk To ChatGPT

1. Download all Modules:
    - pip install openai
    - pip install pydub (https://github.com/jiaaro/pydub#installation)
        Manipulate audio with a simple and easy high level interface
    - pip install colorama (https://pypi.org/project/colorama/)
        Makes ANSI escape character sequences (for producing colored terminal text and cursor positioning) work under MS Windows
    - pip install sounddevice
        Play and Record sound with Python
    - pip install soundfile
        The soundfile module can read and write sound files
    - pip install gTTS. See: https://github.com/pndurette/gTTS/issues/31 for a list of language codes. Using different language codes also changes the voice type
    - brew install mpg321
2. Set Your OpenAI API Key in openaiapikey.txt
3. Set Your Eleven Labs API in elabaiapikey.txt. This should be found once you login in Eleven Labs, under Profile section
4. Go to https://api.elevenlabs.io/docs#/voices/Get_voices_v1_voices_get
5. Paste your Eleven Labs API Key in the designated field
6. Click on "Execute" button
7. Copy the `voice_id` value
4. Set Your Eleven Labs Voice ID under `voice_id` variable in `talk.py` script
5. Customize your chatbot.txt
6. Run talk.py
   1. open zshrc file by runnin in terminal: `nano ~/.zshrc`
   2. add this line: `alias voicegpt="python /Users/alexandru.dumitru/workspaces/talk-to-chatgpt/talk.py"`
   3. go to terminal and run `voicegpt`

## Resources
Eleven Labs API Documentation: https://api.elevenlabs.io/docs#/voices/Get_voices_v1_voices_get