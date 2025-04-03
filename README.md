# Momenta Audio Deepfake Detection Assessment

This repository contains my solution for the Momenta audio deepfake detection assessment, implementing RawNet2 to detect AI-generated human speech using the ASVspoof 5 dataset.

## Repository Structure
- `RawNet2.ipynb`: Jupyter Notebook with Part 2 implementation (RawNet2 model, training, evaluation).
- `part1_research.md`: Part 1 - Research & Selection of RawNet2, AASIST, and LCNN.
- `part3_documentation.md`: Part 3 - Documentation & Analysis of the implementation.
- `requirements.txt`: Dependencies required to run the code.
- `models/`: (Optional) Saved model weights after training.
- `logs/`: (Optional) TensorBoard logs from training.

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone github.com/yourusername/momenta-audio-deepfake-detection
   cd momenta-audio-deepfake-detection
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt

3. **Obtain ASVspoof 5 Dataset**:
  Download from Zenodo (~14 GB).<br>
  Extract to a local directory (e.g., /path/to/ASVspoof5/).<br>
  Update paths in RawNet2.ipynb:<br>
  database_path = '/path/to/ASVspoof5/'<br>
  protocols_path = '/path/to/ASVspoof5/protocols/'<br>
