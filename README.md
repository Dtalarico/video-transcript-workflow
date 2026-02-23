# Video Transcript Extraction Workflow

This project documents a real-world workflow for extracting text transcripts
from lecture videos that do not provide captions or downloadable transcripts.

## Problem

Some lecture platforms stream video without providing caption files or transcript downloads.
This makes studying difficult, especially for people who learn better by reading
or need searchable text.

## Solution

A multi-step workflow was developed to extract usable text:

1. Play lecture video
2. Screen record video playback
3. Extract audio from recording
4. Use speech-to-text (Whisper via Subtitle Edit)
5. Export transcript to text file
6. Review and clean transcript for accuracy

## Tools Used

- Screen recording software
- Subtitle Edit
- Whisper speech recognition
- Text editor

## Skills Demonstrated

- Media capture workflow design
- Audio processing
- Speech-to-text transcription
- Accessibility problem solving
- Toolchain integration
- Practical troubleshooting

## Why This Matters

This demonstrates real-world problem solving when systems do not provide
direct data access. The workflow converts locked video content into usable,
searchable study material.

## Future Improvements

- Automate audio extraction
- Batch processing pipeline
- Scripted transcription workflow
- Integration with cloud storage
