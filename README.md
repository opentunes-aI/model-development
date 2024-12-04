# 🎵 Opentunes AI Model Development

This repository contains development workflows for training, validating, testing, and deploying Opentunes AI models to Hugging Face.

## 📁 Repository Structure
```
model-development/
└── model_name/
    └── version/
        ├── training/      # Training phase
        ├── validation/    # Validation phase
        ├── testing/       # Testing phase
        └── deployment/    # Deployment phase
```

## 🤖 Models
- MelodyMaster V1 (`melodymaster/v1/`)
  - Text-to-music generation model
  - Based on Facebook's MusicGen
  - Fine-tuned on MusicCaps dataset

## ⚙️ Prerequisites
- Hugging Face account and API token
- Access to:
  - Base models (e.g., facebook/musicgen-melody)
  - Training datasets (e.g., google/musiccaps)
  - Your model repository on HF (e.g., opentunes-ai/melodymaster-v1)

## 🚀 Setup
1. Clone this repository:
```bash
git clone https://github.com/opentunes-ai/model-development.git
cd model-development
```

2. Configure Hugging Face access:
```bash
# Set your HF token
export HUGGING_FACE_TOKEN=your_token_here
```

3. Install requirements:
```bash
pip install -r requirements.txt
```

## 🔄 Development Workflow
1. **🏋️ Training Phase**
   - Configure training parameters
   - Run training notebooks/scripts
   - Monitor training progress

2. **✅ Validation Phase**
   - Validate during training
   - Check model performance
   - Adjust hyperparameters

3. **🧪 Testing Phase**
   - Evaluate model performance
   - Run quality checks
   - Generate test reports

4. **🚀 Deployment Phase**
   - Push to Hugging Face
   - Update model cards
   - Version management

## 🤝 Dataset Resources
1. [Meta Sound ](https://www.facebook.com/sound)
2. [Pond5 Music Collection ](https://www.pond5.com/)
3. [MTG-Jamendo Dataset]( https://github.com/MTG/mtg-jamendo-dataset)
   - Contains over 55,000 full audio tracks with 195 tags
4. [ComMU Dataset](https://pozalabs.github.io/ComMU/)
   - 11,144 MIDI samples with 12 metadata categories
5. [MusicCaps](https://huggingface.co/datasets/google/MusicCaps)
   - 5,521 music clips (10 seconds each) with text captions
6. [AudioSet](https://research.google.com/audioset/)
   - Over 2 million audio files, including music clips
   - Available through Google's research resources
7. The Bach Doodle Dataset:
   - 21.6 million harmonizations with metadata
   - Available through Google's research platforms
8. MusicBench:
   - 52,768 training and 400 test audio-text pair samples
   - Available alongside the Mustango text-to-music model
     
## 🤝 Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📄 License

Apache License 2.0

## 📫 Contact

- Organization: [Opentunes AI on Hugging Face](https://huggingface.co/opentunes-ai)
- GitHub: [Opentunes AI](https://github.com/opentunes-ai)
