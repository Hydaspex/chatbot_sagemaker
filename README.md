# chatbot_sagemaker

This is an example on how to deploy an open-source LLM, like BLOOM to Amazon SageMaker for inference using the new Hugging Face LLM Inference Container. 
We will deploy the 12B Open Assistant Model, an open-source Chat LLM trained by the Open Assistant initative and build a quick gradio application to chat with it.
We are going to use the sagemaker python SDK to deploy Pythia 12B to Amazon SageMaker. We need to make sure to have an AWS account configured with the right Service Quota 
to run on ml.g5.12xlarge instance and the sagemaker python SDK installed.
