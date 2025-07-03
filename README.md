# I'm Somewhat of a Painter Myself  
CycleGAN for Monet Style Transfer

This project implements a CycleGAN to perform unpaired image translation between real-world photos and Monet-style paintings. It is developed as part of the Kaggle competition "I'm somewhat of a painter myself" using TensorFlow.

---

## Overview

CycleGAN enables image-to-image translation without paired data by leveraging adversarial training combined with cycle-consistency and identity losses.

---

## Data Source

The dataset used in this project is sourced from the [Kaggle "I'm somewhat of a painter myself" competition](https://www.kaggle.com/competitions/i-m-somewhat-of-a-painter-myself/data), which includes real landscape photos and Monet paintings.

---

## Contents

- **Data Exploration:** Dataset overview, image inspection, and visualization of sample photos and Monet paintings.
- **Image Analysis:** Computation and visualization of average images and color distributions for both domains.
- **Model Architecture:** Construction of generators and discriminators, along with loss functions and optimizers.
- **Training:** Custom training loop using four Adam optimizers, trained for 20 epochs.
- **Results:** Loss curves tracking generator and discriminator performance over time.

---

## Usage

1. Clone the repository.  
2. Install TensorFlow and required dependencies.  
3. Download the dataset from Kaggle and prepare the data paths.  
4. Run the notebook to train the CycleGAN and visualize results.

---

## License

This project is open source and available under the MIT License.

