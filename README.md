# Subtitle Creator for Adobe Premiere Pro

## Overview

A CEP extension for Adobe Premiere Pro that automatically creates subtitle tracks from text files with intelligent timing calculation. Each line in your text file becomes a subtitle, with duration automatically calculated based on the detected video length.

## Features

- **Automatic Video Duration Detection** - Intelligently detects video length from the active sequence
- **Dynamic Subtitle Timing** - Calculates optimal subtitle duration based on video length and subtitle word count
- **Simple File Upload** - Select a .txt file directly in the panel
- **Word Spacing Control** - Adjust spacing between words (0-15 points) in the panel
- **Real-time Feedback** - Status and errors are shown in Premiere Pro's Events panel
- **Minimal User Prompts** - Only the video duration is alerted to the user; all other feedback is non-intrusive

## How It Works

1. Open the extension panel in Premiere Pro
2. Select your subtitle text file (.txt) using the file input
3. Adjust word spacing if needed using the slider or number input
4. Click "Create Subtitles"
5. The only alert you will see is the detected video duration; all other status and errors are shown in the Events panel

## Author

rahul

