# TransferLearning

### Abstract

* Transfer learning reuses a model developed for one task as the starting point for a model on a second task.
* Models often forget previous learnings when retrained on new classes. We aim to minimize this forgetting and enhance knowledge retention. 
* There are various existing approaches which inorder to increase the transferability mainly relay on either replicating the models or using additional memeory space for the parameters or data augmentations. However, these approaches can add complexity to the model and increase computational costs.
* We implemented an Auxiliary Prototypical Network (Protonet) model to tackle catastrophic forgetting and compared it with the standard Protonet model. Our model exploits another dataset(e.g: cipher 100) to create auxilary prototype.
* The auxiliary Protonet significantly reduces forgetting, showing better retention across multiple training sessions. This approach improves continual learning in dynamic environments.

### Project Motivation
* The motivation behind this project is to explore the potential of transfer learning in improving the accuracy and efficiency of models, particularly when dealing with limited datasets. By using pre-trained models, we aim to build robust models with reduced training time and computational resources.

## Auxiliary ProtoNet
  * The Auxiliary ProtoNet Model is an improved version of the Prototypical Network (ProtoNet) used for few-shot learning, where the goal is to train a model to recognize new classes with only a few examples

  * Outcome: The auxiliary protonet approach yielded significant improvements in model accuracy and robustness.

## Conclusion
  ### Achievements: 
      Utilized a pre-trained model to efficiently adapt to our specific dataset.
      Fine-tuned the model for improved accuracy and performance.

  ### Auxiliary ProtoNet Model:
      Implemented prototype distance calculations to measure feature similarities.
      Used an attention mechanism to focus on important features.
      Combined these methods to achieve more accurate predictions.

  ### Efficiency: 
     Transfer learning allowed for quick and effective model development.
