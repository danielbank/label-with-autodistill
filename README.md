# Training Supervised CV Models from Foundational Models with Autodistill

In this talk, we examine the process of labeling a six-sided dice image dataset for training a supervised computer vision model. Supervision models are nice because they are small and fast. They can run on your phone privately and get accurately detect objects of a small number of classes.

From the [autodistill](https://github.com/autodistill/autodistill) docs:

> Human labeling is one of the biggest barriers to broad adoption of computer vision. It can take thousands of hours to craft a dataset suitable for training a production model. The process of distillation for training supervised models is not new, in fact, traditional human labeling is just another form of distillation from an extremely capable Base Model (the human brain 🧠).

> Foundation models know a lot about a lot, but for production we need models that know a lot about a little.

> As foundation models get better and better they will increasingly be able to augment or replace humans in the labeling process. We need tools for steering, utilizing, and comparing these models. Additionally, these foundation models are big, expensive, and often gated behind private APIs. For many production use-cases, we need models that can run cheaply and in realtime at the edge.

This project was created as the demo for an accompanying talk: **Training Supervised CV Models from Foundational Models with Autodistill** that was presented at the [Phoenix AI Devs](https://www.meetup.com/phx-ai-devs/) meetup. The [slide deck](slides/autodistill.pdf) is included in this repo in the `/slides` folder.

The [notebook](autodistill.ipynb) is meant to be run in [Google Colab](https://colab.research.google.com/). You will need to use a GPU runtime. The T4 GPU is free but availability is not reliable.
