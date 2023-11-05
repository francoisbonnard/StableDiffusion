
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

### git

```sh
git pull && git submodule update

```
### multi-thread

is it possible to run multithread task in colab ?

```python
import multiprocessing

cores = multiprocessing.cpu_count() # Count the number of cores in a computer
cores
```