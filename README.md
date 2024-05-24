# AI-Podcast-Generator
Ever wondered what a conversation between Rick Sanchez from "Rick and Morty" and Barack Obama would sound like? This project does just that using artificial itelligence. This project creates a short podcast where these two characters engage in lively banter. Just run the script, sit back, and enjoy the show!

## Additional Information

* **Supported Characters & Their FakeYou Voice IDs:**  
  - Rick Sanchez: `weight_0f762jdzgsy1dhpb86qxy4ssm`
  - Barack Obama: `weight_8f3r8hwt0j58j68ayzzfgsh8h`

## Project Description

This project uses AI to produce a podcast featuring Rick Sanchez from "Rick and Morty" and former U.S. President Barack Obama. By integrating Groq API, Llama 70b instruct, and FakeYou, it showcases the potential of AI in creating immersive and entertaining audio content.

## Features

* **Script Generation:**  
  - Uses Groq API and Llama 70b instruct to create a short script between Rick Sanchez and Barack Obama.
* **Dialogue Parsing:**  
  - Parses the script into individual dialogues for each character and assigns the appropriate voice IDs.
* **Audio Generation:**  
  - Converts dialogues into audio files using FakeYou with specified voice IDs, saving each dialogue as a separate WAV file.
* **Podcast Merging:**  
  - Combines individual WAV files into a cohesive podcast file.

## Usage

1. **Install Dependencies:**  
   - Install necessary Python libraries: `groq`, `fakeyou`.
2. **Set Up Credentials:**  
   - Obtain a Groq API key and provide your FakeYou email and password.
3. **Run the Script:**  
   - Execute the provided Python script in a Colab runtime to generate and save the podcast as `podcast.wav`.
   - 
