# explainable toxicity identification and detoxification of text

## project info 

Toxic language in online spheres is affecting individuals and communities in society. There has been an increasing demand to mitigate toxic content. In Ethical Artificial Intelligence (EAI) perspective, numerous research have been undertaken in detecting and alleviating the toxic content. In this paper, we aimed to combine several approaches together to implement a single pipeline for explainable toxicity identification and detoxification of text. 

We trained a transformer based language model for identification, adopted a local surrogate model for interpretability and leveraged the power of GPT3.5 model with zero-shot prompting for detoxification of text. Results showed that dataset size, annotator bias, bias in Large Language Models and evaluating content preservation are critical for this task. We concluded the paper presenting two possible future directions, reinforcement learning with human feedback for enhancing the quality of style transferring and re-ranking as a post-hoc debiasing method.

## user interface 

<p align="center">
    <img src="https://github.com/hasanselimyagci/eai-project-toxicity/blob/main/img/eai-ui.png">
  </p>


## notebooks

You can find individual experiments inside the notebooks folder, whereas 'project_pipeline' demonstrates the whole pipeline with instructions for each major parts and setup of final Gradio interface.

