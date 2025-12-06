# Ashesi Deep Learning Submissions

This repository contains deep learning project submissions for the Deep Learning course at Ashesi University.

## 📚 Contents

### Prosit 2: Speech Recognition with Recurrent Neural Networks

A comprehensive implementation of speech recognition systems using various RNN architectures on the AfriSpeech-200 dataset.

**Key Features:**
- Multiple RNN architectures: Vanilla RNN, GRU, LSTM, and Attention-based models
- Complete pipeline from data preprocessing to model evaluation
- Interactive Plotly dashboards for metrics visualization and attention map analysis
- Support for streaming large datasets with configurable sampling
- Modular architecture with separate components for data, models, and training utilities

**Technologies:**
- PyTorch & TorchAudio
- Hugging Face Datasets
- Plotly for interactive visualizations
- CUDA/MPS support for accelerated training

**Dataset:**
- [AfriSpeech-200](https://huggingface.co/datasets/intronhealth/afrispeech-200) - A multilingual African speech corpus

## 🚀 Getting Started

### Prerequisites

```bash
# Install PyTorch with CUDA support (adjust based on your CUDA version)
pip install torch torchaudio --index-url https://download.pytorch.org/whl/cu121

# Install additional dependencies
pip install datasets==3.6.0 jiwer librosa accelerate rich plotly
```

### Running the Notebooks

Navigate to the respective Prosit directory and open the Jupyter notebook:

```bash
cd "Prosit 2"
jupyter notebook prosit_2b_combined_work_v2.ipynb
```

## 📊 Project Structure

```
Ahsesi---DL-Submissions/
├── Prosit 2/
│   └── prosit_2b_combined_work_v2.ipynb    # Unified pipeline for speech recognition
├── LICENSE                                  # MIT License
├── .gitignore                              # Git ignore rules
└── README.md                               # This file
```

## 🎯 Features

### Data Processing
- Configurable dataset sampling and streaming
- Audio preprocessing and feature extraction
- Text transformation and vocabulary building
- Efficient data loading with PyTorch DataLoader

### Model Zoo
- Vanilla RNN encoder-decoder
- GRU-based sequence-to-sequence models
- LSTM networks with attention mechanisms
- Modular architecture for easy experimentation

### Training & Evaluation
- Flexible training loops with progress tracking
- Word Error Rate (WER) evaluation using jiwer
- Model checkpointing and resumption
- Rich console output for monitoring

### Visualization
- Interactive training metrics dashboards
- Attention weight heatmaps
- Loss and WER progression plots

## 🔧 Configuration

The notebooks use dataclass-based configuration for easy experimentation:

- **DataConfig**: Dataset selection, sampling, and preprocessing parameters
- **ModelConfig**: Architecture choices, hidden dimensions, and layer counts
- **TrainingConfig**: Learning rate, batch size, epochs, and optimization settings

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**bcwin-i** (Isaac Bekoe)

## 🏫 Institution

Ashesi University - Deep Learning Course

---

*Last updated: December 2025*
