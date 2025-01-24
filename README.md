# Voice-Enabled Geospatial Map Application

**Team Name:** Shazam  
**Institution:** Anurag University  

---

## Project Overview

This project revolutionizes geospatial web applications by integrating **voice recognition technology** with dynamic map interfaces. Using advanced tools like the **Whisper model** for speech-to-text and **TensorFlow-based NLP** for text classification, it provides an **intuitive, hands-free solution** for navigating and interacting with maps.

---

## Key Features

- **Voice Command Control**: Navigate maps and perform actions like zooming, adding markers, and switching views.
- **Multilingual Voice Recognition**: Accurate recognition across multiple languages with the Whisper model.
- **Dynamic Geospatial Interaction**: Real-time updates with smooth map rendering.
- **Personalized Voice Shortcuts**: Commands like "How is the day outside?" provide contextual weather and traffic updates.
- **Advanced Marker Operations**: Measure distances, identify common points, and more.
- **Seamless User Experience**: Hardware-optimized performance and integrated voice feedback.

---

## Technology Stack

- **Programming Languages**: Python, JavaScript  
- **Speech-to-Text**: Whisper Model  
- **Natural Language Processing (NLP)**: TensorFlow with Named Entity Recognition (NER)  
- **Geospatial Tools**: OpenLayers GIS library  
- **Rendering Engine**: WebGL for high-performance graphics  

---

## Unique Selling Points (USP)

Existing solutions like Google Maps and Qwhery fall short when it comes to handling complex voice commands or offering an integrated interface for voice-controlled map interaction. This project fills that gap by:

- Fine-tuning **Whisper** for specific geospatial commands.
- Utilizing **TensorFlow** for action and location classification.
- Ensuring seamless execution through a **user-friendly, voice-enabled interface**.

**Example:** A command like "zoom to Hyderabad" directly zooms in on Hyderabad, unlike other tools that may misinterpret or fail to execute such requests.

---

## System Architecture

1. **Voice Input**: Captures commands through the Whisper model.
2. **NLP Processing**: Converts speech to text and interprets it using TensorFlow.
3. **Command Execution**: Processes actions and locations with OpenLayers and WebGL.
4. **Error Handling**: Implements confidence thresholds, fallback mechanisms, and clarification prompts.
5. **User Feedback**: Enhances usability by learning from interactions.

---

## Features in Detail

- **Voice Command Control**: Easy voice-based navigation and actions.
- **Real-Time Geospatial Interaction**: Update and interact with maps in real-time.
- **Custom Shortcuts**: Personalized voice commands for contextual data.
- **Marker-Based Calculations**: Measure distances and find common points.
- **High-Performance Rendering**: Optimized map visuals via WebGL.
- **Integrated Voice Responses**: Verbal confirmation of executed actions.
- **Minimal API Dependence**: Runs on local hardware with minimal reliance on external APIs.

---

## Installation

### Prerequisites
- Python 3.8+
- Node.js 16+
- Required Python and npm dependencies

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/voice-geospatial-map.git
   cd voice-geospatial-map
