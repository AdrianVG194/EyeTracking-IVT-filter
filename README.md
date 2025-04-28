# IVT Eye-Tracking Analysis – Full Demo

This repository provides a functional pipeline for analyzing eye-tracking gaze data into fixations and saccades using a minimal IVT (Velocity Threshold Identification) filter combined with PCHIP interpolation for handling missing data.

## Key Features
- Handling of missing velocity samples via shape-preserving interpolation
- Smoothing and segmentation of gaze velocity data
- Chunk-wise analysis for detailed temporal insights
- Automatic computation of:
  - Fixation count
  - Saccade count
  - Average fixation durations
  - Average saccade durations
  - Average fixation velocities
  - Average saccade velocities
- Designed for clarity, extensibility, and easy integration into larger eye-tracking systems

## Applications
Ideal for researchers and industry practitioners involved in:
- Eye-tracking usability studies
- Human-computer interaction analysis
- Virtual and augmented reality systems
- Cognitive and neurological research

## Files
- `IVT_MVP.ipynb` — Minimal example demonstrating the IVT filter
- `IVT_Full_Demo.ipynb` — Full data pipeline including preprocessing, segmentation, and metrics
- `data_example.npy` — Sample velocity data for testing the notebooks

## Quick Start
1. Open `IVT_Full_Demo.ipynb` in Google Colab or Jupyter Notebook.
2. Ensure `data_example.npy` is in the working directory.
3. Run all cells to:
   - Interpolate missing data
   - Smooth velocity signals
   - Segment gaze events (fixations and saccades)
   - Compute chunk-wise statistics and summary metrics
   - Visualize results

## Prerequisites
- Python 3.x
- NumPy
- SciPy
- Matplotlib

Alternatively, run on Google Colab where dependencies are pre-installed.

---

This implementation is a clear, minimal baseline designed for ease of understanding and extension. Contributions and adaptations are welcome.

---
