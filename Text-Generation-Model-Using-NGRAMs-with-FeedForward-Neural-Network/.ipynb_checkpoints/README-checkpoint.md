# N-Gram Language Model with Feedforward Neural Network

## Project Overview

This project creates a tool that learns to predict the next word in a song based on the words before it, using a simple artificial intelligence system known as a feedforward neural network. Imagine a lyric-writing assistant: you say “I love to,” and it guesses “sing.” It’s trained on one song’s lyrics, but the concept could grow to handle more songs or other texts. Plus, it includes a visual way to see how words relate after learning.

**Goal:** Teach a computer to guess the next word in a song and generate new lyrics.
**Input:** Lyrics from a single song.
**Features:** Predicts words, writes text, and shows word groupings visually.

## What You Need

You’ll need a computer with some standard tools for artificial intelligence and data work—things that process numbers, handle text, and draw pictures. These are easy to find and set up if you’re comfortable with tech basics.

## How It Works

### Breaking Down the Song

It starts by taking a song—like “I love to sing in the rain”—and chopping it into individual words. Each word gets turned into a number, since computers work better with numbers than words. A special “unknown” word is added to handle anything unexpected later.

### Grouping Words

The words are then bundled into small sets called n-grams. For example, with pairs, it might take “I love” and aim to predict “to.” With triplets, it could use “I love to” to guess “sing.” These sets are what the system learns from.

### The Learning System

At the heart is a neural network, like a basic brain with layers. It turns each word’s number into a detailed description that captures its meaning. Then, it combines those descriptions, refines them, and guesses the next word from all the options in the song’s word list.

### Teaching Process

The system learns by going over the word groups many times—up to 100 rounds or however long you choose. It guesses the next word, sees how wrong it was, and tweaks itself to improve. It tracks its mistakes and occasionally tries writing a snippet of lyrics to show progress. The learning pace is steady, with an option to slow it down over time, though that’s not fully active yet.

### Writing Lyrics

After learning, it can generate new text. Starting with a few words from the song, it predicts the next one, adds it, and keeps going for up to 100 words, creating a string of lyrics that might echo the original song.

### Visualizing Words

Finally, it takes the word descriptions it learned and squashes them into a 2D picture. Each word becomes a dot, with the first 20 labeled so you can read them. This shows how words cluster—similar ones should be close together if the learning worked.

## How to Use It

Start with your own song lyrics as one line of text. Use a notebook-style tool—think of it as an interactive document—to run the project. You can adjust settings like how many words to consider before guessing or how detailed the word descriptions are. Once set up, it processes the song, learns, writes new lyrics, and draws the word picture.

## What You’ll See

* **New Lyrics:** After learning, it produces a sequence of words that might feel song-like, depending on how well it trained.
* **Word Picture:** A dot plot showing where words land in 2D space, with some labeled to spot patterns.

## Limits

It only looks at a small handful of words at a time, so it misses longer connections in the song. It’s a basic setup compared to more advanced systems that could remember more. Also, with just one song, it might get too focused on those words alone.

## Ideas for Growth

Try it with more songs for variety, explore fancier learning systems, or add a smarter way to choose words when writing. There’s lots of potential to make it even better!

## Final Thoughts

This is a fun, hands-on way to teach a computer about song lyrics, built simply from the ground up. Feel free to use it or tweak it however you’d like!

Created by [Faizan Saleem Siddiqui] , March 19, 2025.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this software as you see fit, provided you include the original copyright and license notice.


