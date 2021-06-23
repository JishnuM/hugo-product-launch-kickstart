---
header_brand: 📏 MetricRule
header_tagline_paragraph: Open source granular monitoring for ML services
header_button_cta:
  url: "#contact-form"
  title: Get in touch
header_button_more:
  url: "https://github.com/MetricRule/metricrule-agent-go"
  title: Code
teaser_image: 'images/dynamic-input-outputs.gif'

---

## Monitor models in production

Building a great ML service is difficult. Managing it in production is doubly so.

If your team is in the trenches using ML in production, take this
[quiz](https://mltestscore.metricrule.com), to measure how you are doing and get ideas for improvements.

MetricRule works with your model serving stack to automatically create metrics for your services' inputs and outputs, so you can track and get alerted on bad model deployments, feature drifts, or unexpected data.

## Demo

Interact with a live demo of a dashboard powered by MetricRule metrics [here](http://bit.ly/petfinder-dash).

This demo runs MetricRule against an [example model](https://www.tensorflow.org/tutorials/structured_data/preprocessing_layers) to predict whether a pet will be adopted or not, trained on the [PetFinder dataset](https://www.kaggle.com/c/petfinder-adoption-prediction), with simulated production traffic.

### Features

- Agents to create feature metrics on your deployed ML models. Get real-time data on what production features and predictions look like.
  - Works with [Tensorflow Serving](https://github.com/tensorflow/serving), [KFServing](https://github.com/kubeflow/kfserving), [FastAPI](https://fastapi.tiangolo.com/), [Flask](https://flask.palletsprojects.com/en/2.0.x/) and more.

- Pluggable into standard software observability tools (e.g Prometheus, Grafana).

- Open source. Hosted version coming soon.

***

Interested to know more? Have feedback or feature requests? Get in touch with us here:

{{< contact_form id="contact-form" placeholder_name="Name" placeholder_email="Email Address" placeholder_message="Message" button_label="Send ✉️">}}

***

## Why granular monitoring of features?

- Poor quality model outputs are not diagnosed as system errors but have user experience and [revenue impact](https://www.washingtonpost.com/technology/2019/07/18/uber-glitch-charges-passengers-times-normal-price-resulting-crosstown-fares-thousands-dollars/)

- Poor model performance can be restricted to specific [slices](https://www.snorkel.org/blog/slicing) of inputs and outputs which are not apparent on global views

- Shifts in user behavior in response to [external](https://www.technologyreview.com/2020/05/11/1001563/covid-pandemic-broken-ai-machine-learning-amazon-retail-fraud-humans-in-the-loop/) [events](https://fortune.com/2020/06/09/instacart-coronavirus-artificial-intelligence/) or internal product [changes](https://www.wired.com/2015/10/can-learn-epic-failure-google-flu-trends/) can affect model outcomes

***

## Interested in email updates?

Sign up here to get very occasional updates from us. Don't worry, we hate spam too.

{{< newsletter_sign_up id="newsletter-sign-up-form" placeholder_email="Your Email" button_label="Sign up">}}
