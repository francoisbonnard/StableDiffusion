# StableDiffusion


## github reference

https://github.com/bmaltais/kohya_ss

### hugging face

```python
    from huggingface_hub import notebook_login
    notebook_login()
```

## sdxl copy

https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/tree/main

    !wget https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/blob/main/sd_xl_base_1.0.safetensors


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