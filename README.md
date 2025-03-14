# Run ollama on Google Colab

# Setup
- Login https://dashboard.ngrok.com/login
- Copy Authtoken `Side bar Getting Started --> Your Authtoken --> Copy`
- Open Google Colab https://colab.research.google.com
- Open Notebook Github --> https://github.com/ricardomerces/ollama_remote/blob/main/ollama_remote.ipynb
- Select GPU Machine T4 `(right menu bar) --> Dropdown Connect --> Change Runtime type --> T4 GPU --> Connect`
- Configure ngrok token `Side bar key icon --> add new secret --> Name : NGROK_AUTH_TOKEN , Value : your ngrok Authtoken --> Toogle notebook access`
- Run Notebook `Menu bar --> Runtime --> Run ALL`
- Get ngrok url `the last block of code will show the ngrok url --> Copy this`
- Install ollama on your local machine - https://ollama.com/download
- Configure remote ollama `Open terminal --> export export OLLAMA_HOST= your ngrok url`
- Run ollama (local machine) `ollama run gemma3`

# Recomendations
- After finish , disconnect and delete runtime
