# pluto
Llama-3-8B chatbot hugging face

creating a chatbot using hugging face and langchain

huggingface official page:https://huggingface.co/
[create a hugging face account]
model link:https://huggingface.co/Orenguteng/Llama-3-8B-Lexi-Uncensored

system requirments:
if using 4bit quantization:
  GPU with Sufficient VRAM: At least 12 GB of VRAM
  RAM: At least 12.7 GBof system RAM
  STORAGE: atleast 15.0 GB
else:
    RAM: At least 30 GB of system RAM
    STORAGE: atleast 15.0 GB

recommended running on a cloud-based platforms with gpu like colab and kagle.
use a cache directory to save time during repeated use  

pipline parameters :
max_length: Limits the length of the generated text(max number of tokens to generate).
temperature: Controls creativity/randomness.
top_p: Ensures that the generation considers tokens that cover 90% of the probability mass.
top_k: Limits the token selection to the top 50 most probable ones.
num_return_sequences: Specifies how many outputs to generate.
truncation: Ensures input fits within the model's limits.

adjust these value to fine tune the model

