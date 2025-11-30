---
title: "The ML collaboration platform"
author: aguzman
---

Now you need the tools that will help you carry out your Artificial Intelligence project, whether it’s generative AI or another type. You need technology and an architectural plan.

First, you must be very clear about the central piece of the whole project: the software collaboration platform. Some of the most relevant ones are GitLab and GitHub.

This will allow you to maintain automated control over the software lifecycle. AI engineers, data scientists, and even data engineers will work on it, collaborating in their areas of expertise that I mentioned in the previous article.

You will need a tool to provide infrastructure for your project, such as a storage bucket to host versions of your models, their outputs and a cloud execution environment.

Maintaining all the versions of your model and tracking which data was used is crucial. You can use MLFlow to achieve that goal.

The pipeline that trains your AI model can use different orchestrators: Prefect, Airflow, Kubeflow...

Nowadays most software runs as an isolated component of the operating system where it executes. This minimizes version incompatibility errors and lets you run different models, each with its own dependencies. You should move to building your containers with Docker.

Now you want to present your AI project to your client and thereby validate your idea. You can achieve this with a RESTful API framework. There are several on the market: KServe, FastAPI, Django.

Once you have all, you’ve not finished yet; you must keep your model’s quality as high as possible. To that end, include monitoring software for data drift and model drift in your code. Evidently can help you with that!

Are you already deploying your models using best practices or still missing out?
Activar para ver una imagen más gran