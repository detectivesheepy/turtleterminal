# Turtle Terminal
A free-to-use terminal for your projects, with a windows app because I felt like it
## Using
Embed `https://turtleterminal.vercel.app` into your website
## Question
Question is a an array type for making script-running and user commands easier. <br> 
You can use a command in each slot of an array: <br>
`["fullscreen","dial 1800 931 664","print You just ran code from","httpsend https://turtleterminal.vercel.app/testquestion.json"]` <br>
1. `fullscreen` runs the fullscreen command
2. `dial 1800 931 664` runs itself
etc, etc <br>
To run a Question in Turtle, use ? followed by the address to the question. Example: `?https://turtleterminal.vercel.app/testquestion.json`
## Commands
To get a command list, run `help` in the Turtle CLI
## Ollama support
Turtle supporta Ollama thanks to [Greedy Allay's Ollama PenguinMod port](https://github.com/GreedyAllay/extensions/blob/main/resources/extensions/ollama.js). We have a fork at [turtleollama.js](https://github.com/detectivesheepy/turtleterminal/blob/main/turtleollama.js) in this repo. <br>
Ollama commands
- `ollama on` Toggle ollama mode on
- `ollama off` Toggle ollama mode off
- `ollama set server (address)` Set your ollama server address
- `ollama set model (name)` Set the ollama model
