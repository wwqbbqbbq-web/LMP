# LMP
Learning Multi-Modal Prototypes for Cross-Domain Few-Shot Object Detection
## Setup

We conduct our model testing using the following versions: Python 3.9.23, torch 2.6.0+cu124, and CUDA 12.4.

1. Clone this repository.

```bash
git clone https://github.com/your_name/your_repo.git
cd your_repo/
```

2. Install the required dependencies.

```bash
conda activate cdfsod
pip install -r requirements.txt
```

3. Download the pre-trained model and weights, then modify the corresponding paths in the train/test script.
   Download the [GroundingDINO_weights](https://github.com/IDEA-Research/GroundingDINO/releases) and [BERT weights]
