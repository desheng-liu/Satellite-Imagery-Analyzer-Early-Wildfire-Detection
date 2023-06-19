# AI / ML Project At Lockheed Martin

The AI/ML training model for wildfire and object detection is designed to analyze satellite imagery and detect instances of wildfires and objects within the images. It leverages cutting-edge technologies such as geoJSON, numpy, torch, kubernetes.client.models, and kfp_tekton to achieve accurate and efficient results. The model employs advanced convolutional neural networks (CNNs) to extract high-level features from the satellite imagery, enabling effective detection of wildfires and objects. The CNNs are trained using a combination of labeled datasets and techniques such as transfer learning to enhance their accuracy and generalization. The model manages the deployment and scaling of training jobs across a distributed cluster of machines using Kubernetes. Kubeflow Pipelines allows for the seamless execution and coordination of various steps in the AI/ML training pipeline, including data preprocessing, model training, evaluation, and deployment.

TL:DR
* The model analyzes satellite imagery in geoJSON format for wildfire and object detection.
* It uses numpy for data processing, including feature extraction, image normalization, and resizing.
* Torch, a powerful deep learning framework, employs convolutional neural networks (CNNs) for accurate detection.
* The model leverages labeled datasets and transfer learning for enhanced accuracy.
* Kubernetes, along with kubernetes.client.models, manages distributed training jobs for scalability and resource optimization.
* kfp_tekton facilitates pipeline orchestration, integrating with Tekton for seamless execution of preprocessing, training, evaluation, and deployment.
* The model enables efficient monitoring and response to wildfires, as well as precise identification and tracking of objects in satellite imagery.
