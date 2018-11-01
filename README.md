# conda_note

## Check conda version

```
conda -V
```

## Check `conda` subcommand

```

```

## 
```
conda create -n ViewBS
```

## activate

```
source activate ViewBS
```

## deactivate

```
source deactivate
```

## Check `conda` version and python version

```
conda info
```

## Check environmenta list 
```
conda env list
```


## 

```
module load anaconda/5.1.0-py36
conda create -n ipykernel_py3 python=3 ipykernel
source activate ipykernel_py3    # On Windows, remove the word 'source'
python -m ipykernel install --user
```
