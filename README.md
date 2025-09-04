# chatbot-with-llama-lp-author
Repository for liveProject: Chatbot with Llama

## Milestone 1

I am just going to upload the PNG files - not the gguf file because of the size. I'm on a cable modem & the upload speed is terrible. I will keep this branch around in case I need those PNG files again for some reason.

## Milestone 2

I executed llama-simple.wasm via wasmedge as shown below. I did not include logging but did set the number of tokens to predict at 128.

`    wasmedge --dir .:.
       --nn-preload default:GGML:AUTO:Meta-Llama-3.1-8B-Instruct-Q5_K_M.gguf llama-simple.wasm --n-predict 128
       --prompt "What is the answer to the ultimate question of life, the universe, and everything?"`

The answer is a screen capture in the file **milestone-2-answer-42.png**. I did not upload the llama-simple.wasm file.
