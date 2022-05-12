# Demo Stories for LineaPy

Here are collections of LineaPy demo stories for different persona.

Each story collected here should be a good introduction resource for user who doesn't have any prior knowledge of LineaPy.
We should also assume our users might coming from different background, so we should prefer plain language than technical synonym.

Each story here may contain more than one LineaPy feature. 
For instance, if using both `code slicing` and `artifact store` can help the story more complete, we should go ahead to do it.
For feature specific topic should be in some where else.

Each demo story should start from describing some pain points that we've observed based on user studies and personal experiences.
Then we present the idea about how LineaPy is trying to solve these pain points and give a outline about the demo structure.
Finally, a live demo.

Currently, all the demo a designed to do in Google Colab, so there will be some Colab specific code exist in the notebook.
Other than these code, the demo should be able to run in a native Jupyter environment.

If you think pre-populating the artifact store can make your story more concise, we can pre-populate the artifact store by inserting following command to clone this repo and copy the `.linea` folder to the home directory and just point out the tutorial about how to save the LineaPy artifact.

```bash
%%sh
git clone https://github.com/linealabs/demos
cp -r demos/story/create_simple_pipeline/.linea/ ~
```
