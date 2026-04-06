> [!IMPORTANT]
> Before setting up your own server for Turtle, please check the LICENSE (Above, second tab)

# Turtle Terminal
<img src="https://github.com/detectivesheepy/turtleterminal/blob/main/logo.png?raw=true" height="150" align="right"/>
A free-to-use terminal for your projects, with a windows app because I felt like it <br> <br> <br>

## Using
Embed `https://turtleterminal.vercel.app` into your website

## Commands
To get a command list, run `help` in the Turtle CLI



# Languages and other systems
Jump to...
- [Ollama](https://github.com/detectivesheepy/turtleterminal/tree/main#ollama-support)
- [LSL](https://github.com/detectivesheepy/turtleterminal/tree/main#lsl-support)
- [Question](https://github.com/detectivesheepy/turtleterminal/tree/main#question)
- [JavaScript](https://github.com/detectivesheepy/turtleterminal/tree/main#javascript)


## Ollama support
<img src="https://sjvision.co.uk/wp-content/uploads/2025/08/ollama-white.png" height="50" align="right"/>

Turtle supports Ollama thanks to [Greedy Allay's Ollama PenguinMod port](https://github.com/GreedyAllay/extensions/blob/main/resources/extensions/ollama.js). We have a fork at [turtleollama.js](https://github.com/detectivesheepy/turtleterminal/blob/main/turtleollama.js) in this repo. <br>
Ollama commands
- `ollama on` Toggle ollama mode on
- `ollama off` Toggle ollama mode off
- `ollama set server (address)` Set your ollama server address
- `ollama set model (name)` Set the ollama model


## LSL support
<img src="https://github.com/detectivesheepy/turtleterminal/blob/main/LSL.png?raw=true" height="50" align="right"/>

Turtle supports LSL but only partially. Since LSL is made for running on iFrames and game backends it is not primarally used to running in a CLI. <br> Because of that, LSL may not always function. You can find the [LSL documentation here](https://lorenzolikesstuff.gitbook.io/l.ide-docs/running-lsl-in-web).


## Question
<img src="https://cdn-icons-png.flaticon.com/512/10264/10264076.png" height="50" align="right"/>

Question is a an array type for making script-running and user commands easier. <br> 
You can use a command in each slot of an array: <br>
`["fullscreen","dial 1800 931 664","print You just ran code from","httpsend https://turtleterminal.vercel.app/testquestion.json"]` <br>
1. `fullscreen` runs the fullscreen command
2. `dial 1800 931 664` runs itself
etc, etc <br>
To run a Question in Turtle, use ? followed by the address to the question. Example: `?https://turtleterminal.vercel.app/testquestion.json`


## JavaScript
<img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" height="50" align="right"/>

Turtle supports JavaScript thanks to Greedy Allay once more using the custom JavaScript block in his Tiles extension.
