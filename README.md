# Project_lab2

## This is a University project in 2023/2024/1 semester using **Python**, **PyTorch** and **PyG**

## Useful links
- [Torch geometric](https://pytorch-geometric.readthedocs.io/en/latest/index.html)
- [Data Sets](https://pytorch-geometric.readthedocs.io/en/latest/modules/datasets.html#homogeneous-datasets) ,[the Planetoid dataset](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.datasets.Planetoid.html#torch_geometric.datasets.Planetoid)
- [Node2Vec documentation](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.nn.models.Node2Vec.html)
- [A basic example of usage N2V](https://github.com/pyg-team/pytorch_geometric/blob/master/examples/node2vec.py)

## Environments
- [Google Colab](https://colab.research.google.com/)
- [SageMaker](https://studiolab.sagemaker.aws/)
- [Wandb.ai project](https://wandb.ai/balintgerinm/project_lab2_node2vec)

## Instructions
1. Link prediction - for this you should look at the ROC or Lift curve, or the area under the ROC curve. Here we are looking at how well the graph can be reconstructed from the learned representation.
2. Classification - there are data sets where there are labels for the vertices, here if you have learned a representation you can build a classification model with any model (e.g. [Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)), to evaluate this you may want to look at Confusion Matrix, F1 score (micro/macro), Accuracy. Here we are looking at how useful the learned representation is in providing information to solve the problem.
3. regression - similar to the previous one
4. if you want to visualize the learned representation, you should first reduce it to 2d. For this you can use e.g. TSNE or PCA.
