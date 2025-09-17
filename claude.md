# Custom Meditation App - AI-Generated Meditation Sessions

## Project Overview
Building a meditation app that generates personalized, AI-driven meditation sessions. The core differentiator is dynamic content generation rather than a static library of pre-recorded sessions.

**Current Phase**: This Web app will Rails to test the meditation generation engine before mobile development.

## Code Style & Standards
- Use Rails conventions and follow the Rails style guide
- Write descriptive method and variable names
- Include basic error handling for API integrations (don't overthink it)
- Use strong parameters for all controller inputs
- Keep views simple - minimal logic, use helpers/partials
- **Focus on speed over perfection** - this is validation, not production code

## Core Technical Requirements
- We will be using Elevenlabs V3 API, the newest API
- The Elevenlabs V3 API are located here: https://elevenlabs.io/docs/models#eleven-v3-alpha and https://elevenlabs.io/docs/api-reference/introduction
- We will primarily be using the Create speech endpoint to create our audio files: https://elevenlabs.io/docs/api-reference/text-to-speech/convert

## Data Models
- Each time we make an API call to Elevenlabs to make an audio file, we need to save that request and audio file so that we can reference it later

## API Keys
- Elevenlabs: eba7ca7e2c79cede9f9c7e7f4bbd84526ef2324934eeb900021f815b28ea1173