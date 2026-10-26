# 🎧 Smart Audio Denoising System

**A Digital Signal Processing (DSP) project for reducing noise in audio signals using Python.**

![Python](https://img.shields.io/badge/Python-3.x-blue)
![DSP](https://img.shields.io/badge/Domain-Digital%20Signal%20Processing-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

The Smart Audio Denoising System demonstrates how digital signal processing techniques can reduce unwanted noise in audio signals.

The project loads an audio sample, adds artificial Gaussian noise, applies different digital filters, and compares their performance using numerical metrics and visualizations.

## 🎯 Project Objectives

* Load and analyze an audio signal.
* Add artificial noise to an audio signal.
* Apply multiple digital filtering techniques.
* Compare the performance of different filters.
* Evaluate results using MSE, RMSE, and SNR.
* Visualize audio waveforms, frequency spectra, and spectrograms.

## 📂 Dataset

The project uses an audio sample from the ESC-50 environmental sound dataset.

The sample is used to demonstrate audio processing and noise reduction techniques.

## ⚙️ Project Workflow

1. Load the original audio signal.
2. Convert stereo audio to mono when necessary.
3. Normalize the audio signal.
4. Visualize and analyze the original signal.
5. Add Gaussian noise.
6. Apply three different filtering techniques.
7. Evaluate the filtered signals.
8. Compare the results.
9. Save the selected denoised audio and evaluation results.

## 🔊 Filtering Techniques

### 1. Moving Average Filter

Uses a moving window to smooth variations in the audio signal.

### 2. Butterworth Low-Pass Filter

Reduces frequency components above a selected cutoff frequency.

### 3. Median Filter

Uses the median of neighboring samples to reduce certain types of noise.

## 📊 Evaluation Metrics

The project uses the following metrics:

* **MSE (Mean Squared Error):** Measures the average squared difference between two signals.
* **RMSE (Root Mean Squared Error):** Measures the square root of the mean squared error.
* **SNR (Signal-to-Noise Ratio):** Measures signal power relative to noise power.

MSE and RMSE are generally better when lower, while a higher SNR generally indicates a better signal-to-noise ratio.

## 📈 Visualizations

The notebook includes visual comparisons of:

* Original and noisy audio waveforms.
* Original and filtered signals.
* Frequency spectra using FFT.
* Audio spectrograms.
* Evaluation metrics for different filters.

## 🛠️ Technologies Used

* Python
* NumPy
* SciPy
* Pandas
* Matplotlib
* SoundFile
* IPython
* ipywidgets
* Jupyter Notebook

## 🚀 How to Run the Project

### 1. Clone the repository

Replace `YOUR_GITHUB_REPOSITORY_URL` with the actual URL of your repository.

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the project folder

```bash
cd Smart-Audio-Denoising-System
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

Open `smart_audio_denoising.ipynb` and run the cells in order.

## 📁 Project Structure

```text
Smart-Audio-Denoising-System/
│
├── smart_audio_denoising.ipynb
├── original_audio.wav
├── denoising_results.csv
├── requirements.txt
├── README.md
└── .gitignore
```

Some output files may be generated when the notebook is executed.

## 📌 Expected Outputs

* Original audio playback.
* Noisy audio playback.
* Filtered audio playback.
* Signal waveform plots.
* Frequency spectrum plots.
* Spectrogram comparisons.
* Evaluation metrics.
* A saved denoised audio file.

## ⚠️ Limitations

* The experiment uses artificial Gaussian noise.
* Filter performance depends on the audio signal and noise characteristics.
* A low-pass filter may remove useful high-frequency audio components.
* The best filter should be selected based on both numerical evaluation and listening tests.

## 🔮 Future Improvements

* Test the system on more audio samples.
* Compare additional filtering techniques.
* Add a graphical user interface.
* Allow users to upload their own audio files.
* Explore advanced speech enhancement methods.

## 👤 Author

Add Your Name

## 📄 License

This project is intended for educational purposes. Check the dataset's license and terms before redistributing its audio files.
