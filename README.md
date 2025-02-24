# SparkBite

**Bite-sized wisdom for your daily boost**  
An AI agent delivering 60-second mentoring videos from any prompt—built for the ElevenLabs x a16z WW Hackathon.

## Overview
SparkBite turns questions like “How can I learn Python” into ~150-word, 60-second mentoring videos in ~2-3 minutes. Mistral crafts scripts and scene prompts, ElevenLabs narrates, fal.ai’s PixVerse v3.5 generates 5x 5-second video clips, and `ffmpeg-api/compose` merges them into a seamless MP4—all for ~$2-$3/run. From coding tips to personal boosts, SparkBite makes wisdom quick, actionable, and vibrant!

## Features
- **Input**: Any prompt (e.g., “How can I learn Python”).
- **Output**: 60-second video—~150-word script, narrated audio, 5x subject-focused scenes.
- **Tech**: Mistral, ElevenLabs, fal.ai, Supabase, React—built solo in ~24 hours.

## Prerequisites
- Node.js (~18.x or later)
- Supabase account ([supabase.com](https://supabase.com))
- API Keys:
  - Mistral API ([mistral.ai](https://mistral.ai))
  - ElevenLabs API ([elevenlabs.io](https://elevenlabs.io))
  - fal.ai API ([fal.ai](https://fal.ai))

## Try It Out
Video Demo: https://www.youtube.com/watch?v=zNEwuwVpARo
Live App: https://sparkbite.vercel.app/
