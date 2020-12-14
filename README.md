# Jupyter Notebooks on Rocket Guidance

This is a repository for Jupyter notebooks on rocket guidance.

To edit the notebooks using the Docker Jupyter notebook image, run:

``` sh
docker run --rm -p 8888:8888 -v $(pwd):/home/jovyan/work jupyter/scipy-notebook:399cbb986c6b
```
