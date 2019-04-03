# Cleanup conda base environment

Source: https://stackoverflow.com/questions/52830307/conda-remove-all-installed-packages-from-base-root-environment

* Get base environment revision list
```
conda list -n base -r
```

* Revert base environment to initial revision
```
conda install --revision 0
```

# Export conda environment

```
conda env export -n <env_name> -f <env_name>-env.yml
```


# Uninstalling Anaconda completely

* https://docs.anaconda.com/anaconda/install/uninstall/

```
conda install anaconda-clean
anaconda-clean
```
