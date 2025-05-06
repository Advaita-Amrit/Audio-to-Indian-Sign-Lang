# Audio-to-ISL
For Symbiot. Comment if changes required.


# Automatic Indian Sign Language Translator (ISL)

![Project Banner](signlang.png)

A real-time speech-to-sign-language translator developed by Team Advaita that converts spoken English into Indian Sign Language representations using animated GIFs and static images.

## 🏆 Team Members
- **Advaita Amrit** 
- **Harsh Raj**
- **S D Purvi Raj** 
- **Nuha Fathima**

## 🚀 Features
- 🎤 Live speech recognition
- ✨ 100+ animated ISL GIFs for common phrases
- 🔤 Letter-by-letter spelling with visual guides
- 🖥️ Intuitive graphical interface
- 🆓 Open source with MIT License

## 📦 Installation
```bash
git clone https://github.com/AdvaitaAmrit/Indian-Sign-Language-Translator.git
cd Indian-Sign-Language-Translator
pip install -r requirements.txt
```

## 🏗️ Project Structure
```
.
├── ISL_Gifs/          # 150+ sign language animations
├── letters/           # A-Z sign images
├── main.py            # Core application
├── requirements.txt   # Dependencies
└── LICENSE            # MIT License
```

##Install all required Libraries


**For Windows users**:
```bash
pip install speechrecognition Pillow numpy matplotlib opencv-python easygui pyaudio && python -c "import speech_recognition as sr; print('\033[92m✓ Ready - Microphones detected:\033[0m', sr.Microphone.list_microphone_names())"
```


**For Linux users**:
```bash
sudo apt-get install -y python3-pip portaudio19-dev && pip install speechrecognition Pillow numpy matplotlib opencv-python easygui pyaudio
```

**For macOS**:
```bash
brew install portaudio && pip install speechrecognition Pillow numpy matplotlib opencv-python easygui pyaudio
```

## 📜 License
MIT © 2023 **Advaita Amrit, Harsh Raj, S D Purvi Raj, Nuha Fathima**

```text
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software... [full license text in LICENSE file]
```

## 🤝 How to Contribute
1. Fork this repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push (`git push origin feature/AmazingFeature`)
5. Open a Pull Request