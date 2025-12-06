# Implementation Code

We've included the notebook used to run the Dreamer v3 implementation on the MiniWorld environments. The uploaded notebook is based on the Hallway environment; to run other MiniWorld environments, one would simply have to change the task under "MiniWorld" in the config.yaml file of dreamerv3-torch-DRL. We did not include the notebooks for the other environments because their training runs were stopped at much later timesteps, and they are therefore too large. However, you can find the raw outputs in zipped format in the raw_logs repo in the parent directory. We have provided a notebook to visualize these results in Tensorboard as well.

Please find our Dreamer v3 code here: https://github.com/PV5667/dreamerv3-torch-DRL. Please note that we have adapted this repository to work with the MiniWorld environments using the gymnasium library. There may be errors with other environment suites due to library version errors.

