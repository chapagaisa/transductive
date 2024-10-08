
# Predictive Insights into LGBTQ+ Minority Stress: A Transductive Exploration of Social Media Discourse

![BERT_GCN_ARC](https://github.com/chapagaisa/transductive/assets/46834070/4b0b01f8-3962-4d4e-b71e-53eba6a80bab)

  Fig: BERT-GCN network architecture

  
### Dependencies
We used a Linux server equipped with an NVIDIA GPU, with following required packages: <br>
cudatoolkit=11.8.89 <br>
dgl-cuda10.1=0.6 <br>
ignite=0.4.2 <br>
nltk=3.8.1 <br>
python=3.8.10 <br>
pytorch==1.13.0 <br>
scikit-learn=0.22.2 <br>
transformers=4.1.1 <br>

### Code Reference
The coding refernce for this project are from TEXTGCN and BertGCN. 

https://github.com/codeKgu/Text-GCN        <br>
https://github.com/ZeroRin/BertGCN/tree/main


### Instructions
Step1: Dataset can be requested @ https://github.com/CJCascalheira/lgbtq_stress_dataset <br>
Step2: Install dependencies using terminal "pip install -r requirements.txt". If you wish to use .ipynb file in google colab, dependencies are included in the file. <br>
Step3: Run python build_graph.py [dataset] to build the text graph. <br>
Step4: Run python train_bert_gcn.py --dataset [dataset] 

