# Clineza's Nerdy Nights Follow Along with ca65
This repository is not a tutorial series or demonstration but rather **my personal journey** through the [Nerdy Nights](https://nerdy-nights.nes.science/) series, showcasing my work and progress in NES development using the 6502 processor with the ca65 assembler. Here, you'll find:
- My implementations and experiments.
- Notes and reflections on my learning process.
- A chronicle of challenges faced and solutions discovered.

Additionally, each week's folder will include its own README packed with  images and text detailing my process for that specific week.

## Introduction
Hi, I am Clineza! I'm inviting you to step away from the abstraction and complexity of modern engines and dive into the nostalgic world of NES development with me. If you've ever wished you could go back to the early days of computing, like many of us that grew up in the early 2000s, don't be afraid! You still can! This repository is my journey through the Nerdy Nights series, where I share my code, notes, and experiences to inspire you to explore this retro tech too.

### 🔭 Today's Perspective
If you're like me, you might be seen as an outlier from today's perspective. I didn't grow up when the 6502 was at its peak, yet I am quite fascinated by hardware and low-level software. My journey began in web programming where I learned JavaScript, HTML, CSS, and PHP. While exciting, it left me wanting more—I craved to understand how computers work under all of the abstraction. How is data stored in an SSD? What are memory addresses? What is binary? What are transistors? And most importantly, how can I begin to program all of that?

### 🔧 Why did I choose the 6502 processor, and why should you too?
Firstly, it became popular back in 1975 due to its low cost compared to its competitors. This popularity has remained, making it a favorite among retro hobbyists even in modern day. Secondly, the 6502 features a small, simple instruction set with only 56 instructions, along with a 16-bit address bus and an 8-bit data bus. These limitations and simplicity make the 6502 an ideal chip for learning the fundamentals of computing.

Also let's not forget, the 6502 is no slouch! Variations of this processor were used in numerous iconic machines like the Atari 2600, Commodore 64, the infamous Apple II, and of course, the NES. There are plenty more, but these are some of the most notable ones.

### 🗺️ Venturing On
Prior to this venture, I was learning how to make games with more modern technologies such as Lua with [Love2D](https://love2d.org/), Golang with [Ebiten](https://ebitengine.org/), or even using a full engine like [Godot](https://godotengine.org/). I wanted to remake favorite games from my childhood in a retro aesthetic with my own pixel art. While these game frameworks and engines are fantastic for modern choices, what better way to create a truly retro game than to use no engine at all, one that can be run on the NES (Nintendo Entertainment System)? I hope I've encouraged you to take that leap into the beautiful world of retro game development on the NES!

## Nerdy Nights Overview
Nerdy Nights is a tutorial series to help people write games for the NES. It introduces the concepts in a user-friendly way, and for years has been the go-to solution for many people to learn NES programming. It was originally written by Brian Parker (aka BunnyBoy), with some additional audio tutorals written by MetalSlime. 

(*description taken from* https://nerdy-nights.nes.science/)

### What happened to the Week 1 & 2 Folders in the repository?
The first two weeks of the Nerdy Nights tutorial series don't contain any code. 
- Week 1 provides an introduction to the binary and hexadecimal number system.
- Week 2 shifts the focus to an overview of the NES Architecture.
  
Both are fundamental concepts that will need a solid foundation before diving into the programming aspects of NES development.

### Which assembler should you use? ca65 vs NESASM

My follow along uses the ca65 Assembler which is a part of the [cc65](https://cc65.github.io/) package. The original Nerdy Nights tutorial series uses NESASM, which is the NES assembler. It's important to take note of which assembler you'll use since the process and syntax will be slightly different. ca65 is more modern and can be used for other 6502 projects that aren't related to the NES. That's the main reason I chose to use ca65.

If you'd like to know more, then I suggest taking a look at the [Nerdy Nights ca65 Remix](https://github.com/ddribin/nerdy-nights/tree/master) GitHub repository


## Additional Resources
These are some additional resources and websites that have helped me to get a good grasp on programming the 6502 for the NES
- [NES Dev](https://www.nesdev.org/)
- [Nerdy Nights Tutorial](https://nerdy-nights.nes.science/)
- [Nerdy Nights ca65 Remix](https://github.com/ddribin/nerdy-nights/tree/master) - GitHub Repository
- [Nerdy-Nights-ca65-Translation](https://github.com/JamesSheppardd/Nerdy-Nights-ca65-Translation) - GitHub Repository
- [Easy 6502](https://skilldrick.github.io/easy6502/)

Resources for making games on the NES
- [FCEUX - NES Emulator](https://fceux.com/web/home.html)
- [Aseprite Pixel Art Software](https://www.aseprite.org/)
- [YY-CHR - CHR File creator for Tilesets](https://www.nesdev.org/wiki/YY-CHR)
