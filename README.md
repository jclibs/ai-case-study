# Meshy.AI Case Study
### By Jason Clibanoff
--------------------------
## Overview and Origin
Meshy is a small and relatively new company. It was created in San Jose, California in 2021 by co-founder and CEO Ethan Hu in 2021. It currently only employs between 11 and 50 people according to the [Meshy LinkedIn page](https://www.linkedin.com/company/meshyai/about/). In an article titled ["Meshy: Empowering 3D Content Generation,"](https://80.lv/articles/meshy-empowering-3d-content-generation/) written by the Meshy CEO on the 80.lv website, Ethan Hu describes his inspiration for creating Meshy, stating that he had always had an interest in computer graphics and that many of his CG artist friends had given him the impression that they needed a tool to quickly generate 3D models and bring ideas to life. He also expressed a desire to bring the ability to create 3D models to people who lack traditional 3D modeling skills.
The company earns its revenue through its tiered membership plans and its partnerships with other companies, most notably social media giant Snap. The Meshy site has a free tier and three additional paid tiers with more and more features, increasing price points ranging from as low as $20.00 per month to as high as $120.00 per month, and an option to cut prices by 20% with a yearly subscription.


[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/6tLVqm39dfg/0.jpg)](https://www.youtube.com/watch?v=6tLVqm39dfg)\
Meshy's main functions are creating 3D models from text promts and images, as seen in this demo video found at the top of [Meshy's documentation page](https://docs.meshy.ai/), or directly on their YouTube channel](https://www.youtube.com/@MeshyAI).

## Business Activities
The company aims to give everyone the ability to quickly generate high quality 3D models, regardless of their level of experience in 3D modeling. Meshy's customers are individuals, studios, teams, or companies of various sizes, like Snap, YAHAHA, D5 Render, and KIRI Engine-3D Scanner. Meshy is intended first and foremost to be used by 3D artists, game developers, and creative coders, but is made to empower everyone to get creative with 3D.
Meshy's bread and butter is being able to generate models from both text prompts as well as image prompts, as shown in the video above, but what really sets it apart from the competition is that it creates both an organic and a hard surface model for each prompt, it can create AI generated textures, and it even has a feature that can apply animations to generated models. The website also has a big community aspect to it. Users can upload their creations for the public to see and react to, and paid users can even download models from the community.\
 \
Meshy's goal is to maximize quality and minimize speed. In [this meshy blog post](https://www.meshy.ai/blog/meshy-1-generate-3d-models-with-ai-in-just-a-minute), they describe the technology being used behind the scenes. The blog post details the two major techniques for generating 3D models, 2D lifting and 3D diffusion:
>"2D Lifting: Elevating 2D generative models (such as Stable Diffusion) to 3D, utilizing iterative optimization techniques applied to structures like NeRFs. These methods use lots of 2D data and can make various good-quality 3D models, but it's slow and can take hours even on fast GPUs like the RTX 3080.\
3D Diffusion: This approach significantly trims the generation time to less than 1 minute per model. Because there's not much 3D training data available, models made this way often lack good quality."

The team at Meshy managed to create their tool with a combination of these two methods, resulting in fast, high quality results.

## Landscape
3D model generation with AI is still a very young branch of generative AI, without a single clearcut leader yet. There are many small companies currently striving to push this technology to the next level, Meshy among them. Sam Frish and Bohdan Khomych's article, ["Generative AI for 3D Models Revealed: Insights, Applications, and Tools,"](https://www.softserveinc.com/en-us/blog/generative-ai-for-3d-models-revealed) details the growing landscape and potential of this new technology. In the article, they suggest the revenue of the generative 3D market is set to rise to $1.3 billion by 2032. Frish and Khomych explain how 3D AI models are expected to be used for things like video game production, TV and movie production, avatars for AI assistants, e-commerce, real estate, and synthetic data. Essentially, everywhere traditional 3D artists are currently needed, there will be a place for generative AI 3D tools in the near future. The technology is rapidly advancing as developers strive for the Midjourney-esque jump in quality that came about in generative 2D art in the last few years. In an interview with [XR AI Spotlight,](https://xraispotlight.substack.com/p/are-3d-gen-ai-tools-ready-for-production?r=2umm8d&utm_campaign=post&utm_medium=web&triedRedirect=true) Meshy CEO Ethan Hu predicts that in the next two or three years, "we might see a 3D equivalent of Midjourney-level AI models, at least for niche uses like 3D printing." Some of Meshy's key competitors are 3DFY AI, Luma AI, Spline, Alpha 3D, and Masterpiece Studio.

## Results
In this newly emerging field of generative 3D, whichever companies produce the best results most efficiently and with the most versatility in both utility and output will be the ones to rise above the rest. Meshy AI is one of the leading and most highly regarded companies in this field. It is often highly ranked when comparing different 3D AI platforms, coming in at number one out of seven in UNITE.AI's ["7 Best AI 3D Object Generators (August 2024)"](https://www.unite.ai/best-ai-3d-object-generators/) by Alex McFarland, and at number two out of six in Sam Frish and Bohdan Khomych's rankings. Collaborations with big companies like Snap also suggest that Meshy is doing very well.

## Recommendations
One feature I think could benefit Meshy is showing a little more of what's going on behind the scenes. Competitor Masterpiece shows how it breaks down and interprets the user input before generating the 3D model. For example in Masterpiece I used the input "mecha shark," and this is how the AI broke it down. It shows how the AI decided to interpret the prompt for both the shape of the 3D model and the texture.

|Initial Prompt  |Shape | Paint Prompt |
| :------------------: | :----------------: | :--------------: |
|mecha shark  |Subject: mecha shark Characteristics: mechanical, shark-like shape |Mecha Shark Metallic surfaces, rivets, sharp edges, and hydraulic details to mimic shark anatomy with a robotic twist.|

This feature gives the user more insight into how exactly the program is turning their prompt into a fully textured 3D model. It is interesting, engaging, and likely not too difficult to implement. They would just need to create some new UI for it, and print some of the code running behind the scenes.

Another feature I have seen on some generative 2D platforms is the ability to build on, or *evolve* a creation you have made, using it as a base. This would allow users to tweak their generated models without having to generate a completely new one from scratch to see a change implemented. Meshy already has a refinement tool to upgrade the detail and resolution of a model; if they just add a place to input some new information using a similar method, that could be used to adjust the model without trying to reinvent the wheel. This gives the users more control over what they are creating.



## Sources
[The Meshy.ai Website](https://www.meshy.ai/discover)\
[Meshy Documentation](https://docs.meshy.ai/)\
[Meshy Blog](https://www.meshy.ai/blog/meshy-1-generate-3d-models-with-ai-in-just-a-minute)\
[Meshy LinkedIn Page](https://www.linkedin.com/company/meshyai/about/)\
["Meshy: Empowering 3D Content Generation" by Dr. Ethan Hu - 80.lv](https://80.lv/articles/meshy-empowering-3d-content-generation/)\
["7 Best AI 3D Object Generators (August 2024)" by Alex McFarland - UNITE.AI ](https://www.unite.ai/best-ai-3d-object-generators/)\
["Generative AI for 3D Models Revealed: Insights, Applications, and Tools" by Sam Frish and Bohdan Khomych - Softserve](https://www.softserveinc.com/en-us/blog/generative-ai-for-3d-models-revealed)\
["Interview with Ethan, CEO Meshy" by Gabriele Romagnoli - XR AI Spotlight](https://xraispotlight.substack.com/p/are-3d-gen-ai-tools-ready-for-production?r=2umm8d&utm_campaign=post&utm_medium=web&triedRedirect=true)\
[Masterpiece Studios website](https://app.masterpiecex.com/generate)
