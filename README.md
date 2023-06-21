# InstaAudio

- [Why](#why)
- [Problem](#problem)
- [Solution](#solution)
- [Architecture](#architecture)

Prototype of an easy to use text to speech application that improves the generated
audio quality through a text preprocessing step and provides great UX.

## Why

- Audiobooks, podcasts, and other audio content can be a great way to reduce eye strain and improve accessibility. For people who spend a lot of time looking at screens, listening to audio can be a welcome break for their eyes. It can also be helpful for people with vision impairments who are unable to read traditional books or articles.
- In addition to reducing eye strain, audio content can also improve accessibility for people who are deaf or hard of hearing. By providing an alternative format for consuming information, audio content can help to level the playing field and make information more accessible to everyone.

## Problem

- Normal text-to-speech does not optimize text
  - Reads whatever is given
  - The main focus being the generated audio, trying to make it sound as real as possible
- No unified interface for text to speech conversion
  - Different software needed for docs(pdf, docx) and websites
  - No cross-platform availability
  - Not easy to use
  - Don’t provide audio files separately

## Solution

This application aims to provide solutions to most of the problems listed
above:

- Introduces a text preprocessing step that optimizes the text for audio
- Ideally convert any file format(prototype only supports urls and pdfs) from a
  single application instead of installing different applications for different
  formats
- Generates and exports audio/mpeg files for portability

## Architecture

![Architecture diagrams](./assets/architecture.png)
