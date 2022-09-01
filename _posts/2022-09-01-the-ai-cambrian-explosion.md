---
layout: post
title:  The AI Cambrian Explosion
tags:
- AI
- LLMs
- Stable Diffusion
- product
- startups
---

The utility and versatility of AI is accelerating and has reached a tipping point where we will see an explosion of AI-first products. Most people outside of the AI community don’t appreciate this, but thanks to DALL-E and Stable Diffusion, awareness is starting to increase as people are able to *see and experience* these capabilities for themselves. 

In this post, I’ll lay out the trail of breadcrumbs that leads me to this conclusion and some of my predictions for the future.

# Why researchers are so excited

One of the reasons the AI community is so excited is because they are steeped in the research and seeing how quickly the state-of-the-art is advancing. Researchers benchmark AI capabilities on datasets and challenges these models need to solve. For years, progress towards benchmarks was slow and incremental. 

In 2012 [AlexNet](https://en.wikipedia.org/wiki/AlexNet), one of the first “deep” neural networks for object recognition made a huge leap forward in performance that caught the machine learning community’s attention. That was a shot across the bow that began an enormous shift of focus to deep learning and ignited new interest in neural networks. 

[https://twitter.com/jackclarkSF/status/1542723429580689408](https://twitter.com/jackclarkSF/status/1542723429580689408)

In 2017, the Transformer architecture was introduced and changed the game for natural language processing. To me, that paper is the inflection point where progress accelerated. Since then we’ve seen variations of the transformer for vision, audio, tabular and multi-modal data and massive increases in model sizes. This innovations have pushed the state-of-the-art so quickly that the community is for the first time struggling to come up with benchmark challenges fast enough!

# Ecosystems emerging and products are going viral

We’re now seeing AI research translated into real world value and ecosystems emerging to support these models. DALL-E rocked the world with stunning AI generated images guided by human prompting. [Stability.AI](http://Stability.AI)’s open source stable diffusion made DALL-E obsolete nearly overnight by providing an improved model that is open source and can run on commodity hardware.

What’s remarkable beyond the explosion of interest and generated images on Twitter, Reddit, Discord, etc. is the ecosystem that is rapidly emerging to support these capabilities.

Lexica is a search engine for (prompt, image) pairs that overnight reached 55,000 searches.

[https://twitter.com/sharifshameem/status/1562872737495785472](https://twitter.com/sharifshameem/status/1562872737495785472)

Other tools like [Photoshop plugins](https://twitter.com/wbuchw/status/1563162131024920576), [Figma plugins](https://twitter.com/RemitNotPaucity/status/1562319004563173376), [Web GUIs](https://twitter.com/altryne/status/1563452692399214594), and more have launched within days of the release of the open source Stable Diffusion model. We’re witnessing the genesis of an entirely new market for art.

# Emergent capabilities from LLMs as they get bigger

While image generation models are deservedly getting a tremendous amount of attention, large language models that generate text and quietly making strides. I believe there is an enormous amount of value to tap from these language models which have shown signs of reasoning, logic and inference. The challenge with these models is that they often make stuff up that ranges from superficially plausible to obviously wrong. But researchers are working to quickly solve for these deficiencies.

I see two broad areas of effort. The first is increasing the size of the models. The remarkable empirical observation is that as you increase the size of the model, new capabilities *emerge!* Although recently new results in this area seem to have slowed and there is [evidence of hitting a wall](https://twitter.com/davisblalock/status/1563455844670246912) with parameter count in recommender systems which needs to be made up for with more data.

[https://twitter.com/_jasonwei/status/1537230731599962112](https://twitter.com/_jasonwei/status/1537230731599962112)

The other area of progress is in sequentially interacting with one or multiple language models to carry out a more robust reasoning process. While this is bearing fruit, it’s not yet a solve problem. Still, given the pace of progress, it seems reasonable that in 12-24 months these models will be capable and robust *enough* to deliver real world value.

[https://twitter.com/mpshanahan/status/1565329081251827713](https://twitter.com/mpshanahan/status/1565329081251827713)

# AI Tailwinds

Progress in AI capabilities is accelerating thanks to a growing body of researchers and practitioners, improved [infrastructure](https://wandb.ai/site) for training and serving AI models, acquiring and [labeling data](https://snorkel.ai/), decreasing costs of [training](https://www.mosaicml.com/) and [serving](https://www.banana.dev/) [models](https://arxiv.org/abs/2208.07339), [open sourcing](https://stability.ai/) of state-of-the-art models, web-scale data sets to train on, and Moore’s law giving us more compute power.

I see a number of tailwinds for launching successful AI products:

- Model capabilities are compounding at a high rate, e.g. Language Models, Image Generation, etc. —> What’s technically infeasible today can be extrapolated to be feasible in 18-36 months. For example, generating incredible images is possible today and we are seeing the earliest [AI generated motion pictures](https://twitter.com/fabianstelzer/status/1565085199322456069). It seems like a reasonable bet that in 18-36 months we will have personalized and entertaining, AI generated movies and shows. Now is the time to start building that [product](https://runwayml.com/), because if you wait until it’s possible, you’re already too late.
- Infrastructure innovation is making it possible for small orgs to independently build, train and run very capable state-of-the-art models. Stable Diffusion can be run on consumer hardware and [MosaicML](https://www.notion.so/Emergent-Abilities-of-Large-Language-Models-Papers-With-Code-d0fb901cbc444bff994965e508d9ffce) is rapidly making progress in training and serving large language models.
- Model training and inference costs will halve every (6-18?) months. Progress here is rapid due to improving model architectures (e.g. stable diffusion), lower cost inference with [serverless GPU infrastructure](http://Banana.dev), decreasing memory footprint for serving models by using techniques to [convert trained model parameters](https://arxiv.org/abs/2208.07339) to lower precision data types. Uneconomical today will become economical in the future. Again, now is the time to start building.

# The right mental model

I think it’s important to have the right mental model for predicting the future capabilities and therefore value-creation opportunities for AI. The key insight is that because progress is compounding at a high rate, we have to extrapolate *exponentially,* not linearly.

I’m particularly excited about progress in improving large language models, multi-modal models and [multi-modal/multi-task models](https://www.deepmind.com/publications/a-generalist-agent) trained with reinforcement learning.

# Conclusion

AI today feels like the internet circa 1995 where the adoption and impact is ready to explode — the vast majority of successful products and startups have yet to be launched. As the folks at [AI Grant](https://aigrant.org/) say, “it’s a new world; there is no map.”