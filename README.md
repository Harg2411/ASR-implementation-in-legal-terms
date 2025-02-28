# Enhancing Legal Transcription Using ASR, TTS, and NLP  

## Overview  

This project integrates **Automatic Speech Recognition (ASR)**, **Natural Language Processing (NLP)**, and **Text-to-Speech (TTS)** technologies to improve legal transcription. By leveraging transformer-based models like **BERT**, the system enhances transcription accuracy, extracts legal terms, and maps them to **Indian Penal Code (IPC) sections**. The addition of TTS functionality provides auditory feedback, making legal information more accessible and interactive.  

## Features  

- **ASR for Legal Transcription:** Converts spoken legal proceedings into text with high accuracy.  
- **NLP-Based Legal Term Extraction:** Identifies and maps legal terms to IPC sections.  
- **TTS for Audio Output:** Converts text-based legal transcriptions into speech.  
- **Multilingual Support:** Handles legal content in **English** and **Telugu**.  
- **Noise Reduction & Preprocessing:** Enhances transcription accuracy in challenging audio environments.  

## Methodology  

1. **Data Collection**:  
   - Legal audio recordings from court hearings, testimonies, and depositions.  
   - A structured dataset mapping **legal terms to IPC sections**.  

2. **ASR & TTS Setup**:  
   - **ASR:** Uses SpeechRecognition, pydub, and Google’s Speech-to-Text API.  
   - **TTS:** Utilizes pyttsx3 for text-to-speech synthesis.  

3. **Data Processing**:  
   - Noise reduction via **spectral subtraction & adaptive filtering**.  
   - Audio segmentation for improved transcription efficiency.  

4. **Algorithm Implementation**:  
   - **Speech-to-Text Conversion**: ASR extracts spoken content into text.  
   - **Legal Term Extraction**: BERT-based NLP models identify key legal terms.  
   - **Text-to-Speech Synthesis**: Generates auditory feedback for accessibility.  

5. **Evaluation Metrics**:  
   - **Transcription Accuracy**: 92.3%  
   - **Legal Term Extraction Precision**: 89%  
   - **Recall**: 87%  
   - **TTS Naturalness Rating**: 4.6/5  

## Results  

- **Improved transcription accuracy** in noisy legal environments.  
- **Accurate IPC mapping** of legal terms for documentation.  
- **Enhanced accessibility** through TTS-based auditory feedback.  

## Contributors  

- **Hari Sai Ganesh Sanjammagari**  
- **Shivmani Gangarapu**  
- **Surya Teja Kadali**  
- **Dr. Nagamani M**  
- **K.E. Srinivasa Desikan**  
