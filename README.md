## Managing Packages

$ conda install [package_name]
$ conda remove [package_name]
$ conda update [package_name]
$ conda update --all
$ conda list
$ conda search *search_term*

i.e.
$ conda install numpy=1.10 scipy pandas
$ conda search '*beautifulsoup*'

## Managing Environments

$ conda create -n [env_name] [list of packages]
$ source activate [env_name]
$ source deactivate


i.e.
$ conda create -n my_env numpy python=3
