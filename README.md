# Moroccan Ads Generation Using NLP

## Introduction

In this project, we are trying to solve an NLP task, which is generating Moroccan ads.  
In order to achieve this goal, we decided it would be better to use a pretrained model, build a dataset that is suitable to our task, and then fine-tune the model on this dataset. The pretrained model we decided to work on is the [araGPT 2](https://huggingface.co/aubmindlab/aragpt2-base) model, which is used for Arabic text generation.  
The dataset was built using web scraping techniques.

## How to Use

Suppose you are an entrepreneur, who just came up with a brand new product, and you want to advertize it in Morocco. You want to generate an ad for your product, but you don't know how to write it, that's where our model comes in handy.  
You can basically start the prompt by typing a very few words about your product, and the model will try to generate a well written script, that is as relevant as possible to your target customers.

## Demo

Starting prompt:

```text
اتاي
```

Generated ad:

```text
! اتااااااااي
```

## Limitations

The main limitations we faced during the development of this project are:

- The very limited resources concerning Moroccan ads, which made it hard to build a dataset that is big enough to train our model on.

- Training the model from scratch would have taken us a lot of time to do, our only choice was to use a pretrained model, and the one we found that is suitable to our task, due to it being trained on Arabic and dialects, is very slow to generate text, and the generated text has no relevenace to the prompt, nor the Moroccan cultyure

## How to overcome these limitations

- We can overcome the first limitation by using more advanced web scraping techniques, and by using more than one website to build our dataset, which reauires more time and resources.

- We can overcome the second limitation by using a more powerful machine, or by using a more powerful model, which requires more resources.

## Business Value

Once the limitations cited above are overcome, this project would be powerful enough to make ads that are very mmuc tailored to the Moroccan culture, without any need to hire a copywriter, which would save a lot of time and money. Also, if used in combination with a recommender system, it would be able to generate ads that are tailored to each customer, which would increase the chances of the customer buying the product. It could also be used with a diffusion model, to generate ads that could be displayed on social media, or shorts, or promote small business.

## Installation

To install the required packages, run the following command:

```bash
pip install -r requirements.txt
```

## Packages Used

- Python (notebooks)
- BeautifulSoup
- Selenium
- Pandas
...

## Aknowledgements

The authors that have contributed to this project are:

- [Yasir Ech-Chammakhy](https://github.com/yasirech-chammakhy)
- [Mohamed NIJADI](https://github.com/gurennnn)

This is the project that my team and I participated in, during the Hackathon organized by 1337 School, and sponsored by the [1337 School](https://www.um6p.ma/en/ecole-1337), huge thanks to them for this opportunity.

In addition to the mentors that have helped us tailor our solution and make it more doable.
