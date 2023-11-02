# StableDiffusion

## colab book

https://colab.research.google.com/github/sagiodev/SDA-lora-training/blob/main/LoRA_trainer_kohya_ss_SDA.ipynb

## github reference

https://github.com/bmaltais/kohya_ss

## hugging face

```python
    from huggingface_hub import notebook_login
    notebook_login()

    from huggingface_hub import hf_hub_url

    myPath=  hf_hub_url(
        repo_id="stabilityai/stable-diffusion-xl-base-1.0", filename="sd_xl_base_1.0.safetensors"
    )
    !wget $myPath
       
```


## sdxl copy


    !wget https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/tree/main/sd_xl_base_1.0.safetensors

https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/tree/main


    !pip install gdown

## parameters 

https://www.youtube.com/watch?v=AY6DMBCIZ3A

## google colab

### access from google drive

```python
    from google.colab import drive
    drive.mount('/content/drive/)
    train_df = load_dataset('csv', data_files='/content/drive/xxx')
```


### basic operatins
    
    !cat /etc/os-release
    !wget --version
    ll -h


### multi-thread

is it possible to run multithread task in colab ?

### stackoverflow

https://stackoverflow.com/questions/77411193/when-copying-file-from-hugginface-to-googlecolab-with-wget-i-only-get-a-small-si