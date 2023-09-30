# TAED2-ML-Alphas
## Image classification for Alzheimer MRI Disease
A ML model to classify brain images of patients in four categories according to the presence of the Alzheimer disease.

## Dataset Card
This dataset consists on brain MRI images labeled into four categories:
- '0': Mild_Demented
- '1': Moderate_Demented
- '2': Non_Demented
- '3': Very_Mild_Demented

Train split:
- Number of bytes: 22,560,791.2
- Number of examples: 5,120

Test split:
- Number of bytes: 5,637,447.08
- Number of examples: 1,280

The whole information about the dataset can be found in *POSAR LINK*

#### Citation
Dataset was obtained from [Hugging Face](https://huggingface.co/datasets/Falah/Alzheimer_MRI).

## Model Card
The model consists of a ResNet architecture, a deep neural network architecture designed to overcome the vanishing gradient problem and improve the training of deep neural networks by using residual blocks.

### Model Details
#### Model Description

ResNet ("Residual Network") is a deep neural network architecture designed to overcome the vanishing gradient problem and improve the training of very deep neural networks.  It uses residual blocks, which introduce skip connections that allow the network to bypass one or more layers. These enable the flow of gradient information during training, making it easier to train deep networks without suffering from diminishing gradients. In each residual block, the input to the block is combined with the output of the block, allowing the network to learn the residual, or the difference between the desired output and the input. 

{{ model_description | default("", true) }}

- **Developed by:** {{ developers | default("[More Information Needed]", true)}}
- **Model type:** {{ model_type | default("[More Information Needed]", true)}}
- **Language(s) (NLP):** {{ language | default("[More Information Needed]", true)}}
- **License:** {{ license | default("[More Information Needed]", true)}}
- **Finetuned from model [optional]:** {{ finetuned_from | default("[More Information Needed]", true)}}


### Intended Uses
- **Primary intended uses:** Classify brain pictures of MRI scans according to the severity of the Alzheimer disease they present.
- **Primary intended users:** Researchers and health medicine applications.
- **Out-of-scope use cases:** Detection of other brain diseases different from Alzheimer.

### Bias, Risks, and Limitations

### Metrics



