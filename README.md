# Team Attackers: Deep Learning CS 6953 / ECE 7123 2025 Spring

This is the project respository for team Attackers - Vaishnavi Mahanti, Nidhi Donuru, Rithvik Peeriga

### Install Libraries



### Final Model
It's at `jailbreaking_adversarial_attacks`

#### Evaluation Summary:

### Top-1 and Top-5 Accuracy

| Model              | Attack Type | Top-1 Accuracy | Top-5 Accuracy |
|-------------------|-------------|----------------|----------------|
| ResNet-34         | Original    | 0.7600         | 0.9420         |
| ResNet-34         | FGSM        | 0.3820         | 0.5960         |
| ResNet-34         | PGD         | 0.4320         | 0.5640         |
| ResNet-34         | Patch       | 0.3480         | 0.5360         |
| DenseNet-121      | Original    | 0.7480         | 0.9360         |
| DenseNet-121      | FGSM        | 0.4720         | 0.6940         |
| DenseNet-121      | PGD         | 0.5100         | 0.7020         |
| DenseNet-121      | Patch       | 0.4280         | 0.6540         |
