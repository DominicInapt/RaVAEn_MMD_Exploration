Summary of RaVAEn findings in relation to https://github.com/spaceml-org/RaVAEn

After executing the inference_demo_.ipynb I made some changes to my clone of the RaVAEn repository.

The most prominent change is hardcoding configuration for the evaluate_model.py script.
Once you have the environment setup by following the instructions in the inference demo, you can
simply call something like python3 evaluate_model.py in your command line after changing the file
addresses in cfg_copy.txt

To speed up inference further, I have attached a .zip containing all of the generating data, reconstructions,
embedded images, and changes from running evaluate_model.py.
This should help you run the inference faster and make it more repeatable on modification.

The PT-MMD demo file uses some of the saved data above and does some quick experiments with it.
The MMD metric seems to work fairly well on the raw images but had trouble on some of the embeddings that I gave it.

The necessary git repository for PT-MMD is https://github.com/GreatA1exander/pt-mmd-demo/tree/master.
