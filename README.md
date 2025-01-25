# OpenAI Realtime Console Desktop Hack

A super hacky way to get to talk to openai advanced voice on your desktop using a modified version of [Openai Realtime Console](https://github.com/openai/openai-realtime-console)

This run the application in the background when starting the command and runs the react app in a headless browser so you don't need to open it yourself but you can start talking to the advanced voice

# Install

```sh
# Download
curl https://raw.githubusercontent.com/lyr-7d1h/openai-realtime-console/master/openai-voice > openai-voice
chmod +x openai-voice

# Update to latest version
openai-voice update
```

# Usage

Run an advanced voice session and start listening

```sh
OPENAI_API_KEY='<your key>' ./openai-voice
```

To stop the session run

```sh
./openai-voice stop
```

# Keybinding 

I have a keybind for both starting and stopping using these commands.

You can [set custom keybinds on gnome](https://help.gnome.org/users/gnome-help/stable/keyboard-shortcuts-set.html.en)