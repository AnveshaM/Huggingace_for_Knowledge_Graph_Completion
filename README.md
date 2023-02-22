# Huggingace_for_Knowledge_Graph_Completion
Designed pipeline for completing the enterprise Knowledge Graph at R2 Factory to reduce number of incorrect triples and predict missing relations and entities;

Knowledge Graph Completion involves the following tasks:
Entity/Link Prediction: This refers to the task of predicting the entities or the nodes of the Knowledge Graph.
Relation Prediction: This refers to the task of predicting the missing links or the edges of the Knowledge Graph.
Triple Classification: This refers to verifying if the triple created by the pretrained language model from the input text is correct.

This project has been run on Google Colab. Experiments have been conducted through August, September, and October. On average around 250 compute units (Cloud Virtual Machines) have been used per month. All VMs ran on High RAM runtime configuration where a maximum of 37.8 Gb of memory was available. The notebook used a premium A100-SXM4-40GB GPU runtime for an advanced GPU setting. All three tasks for both the language models (DeBERTa and XLNet) have been carried out on a single GPU Training environment. To enable use of GPU in Google Colab, ensure that the Pytorch CUDA toolkit is installed correctly.

