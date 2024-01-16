# Using Falcon40B Instruct...and any other Open Source LLMs on GPU via HuggingFace  
we're going to be checking out some of the biggest baddest LLMs...but running them on a GPU!

## See it in action 📺
<img src="https://github.com/NitinRwt/Falcon40B/assets/110294741/4b1474a0-c83c-472c-a2b7-effdceeb7ae5">


# Startup 🚀
1. Create a virtual environment `python -m venv gpullm`
2. Activate it: 
   - Windows:`.\gpullm\Scripts\activate`
   - Mac: `source gpullm/bin/activate`
3. Install PyTorch with CUDA Support 
N.B. I've included the lib in the requirements.txt file but this is latest installer as of creating this readme. 
`pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu117`
Download and install CUDA (i've used 11.7 for this tutorial): https://developer.nvidia.com/cuda-11-7-0-download-archive
Download and install the matching cuDNN version ( v8.9.1): https://developer.nvidia.com/rdp/cudnn-archive 
5. Clone this repo `git clone https://github.com/NitinRwt/Falcon40B`
6. Go into the directory `cd Falcon40B`
7. Startup jupyter by running `jupyter lab` in a terminal or command prompt
8. Hit `Ctrl + Enter` to run through the notebook! 
10. Go back to my YouTube channel and like and subscribe 😉...no seriously...please! lol 

# Other References 🔗
<p>-<a href="https://pytorch.org/get-started/locally/">PyTorch Installation</a>:main guide leveraged to handle GPU support.</p>
<p>-<a href="https://python.langchain.com/en/latest/modules/models/llms/integrations/huggingface_pipelines.html">Langchain HF Pipelines</a>:the HF Pipelines class is used in order to pass the local LLM to a chain.</p>
<p>-<a href="https://huggingface.co/tiiuae/falcon-40b-instruct">Falcon 40B Instruct Model Card</a>:check out the model details.</p>



