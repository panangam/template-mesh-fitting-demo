# Template Mesh Fitting Demo

Contains a demo of template mesh fitting. 

## Viewing instruction

The easiest way to view the demo is the clone or download the repo and simply open the static html file `template_mesh_fitting_demo_snapshot_20210802.html` in your browser. The 3D plots are embedded inside the html file and should load up in a few seconds (tested in Chrome.)

## Developing instruction

I use conda to manage the environment

1. Use conda to create a new environment, and install dependencies from `environment.yml`.
2. Install the `STAR` python package locally using `pip install -e ./STAR`. The `STAR` folder is a modified version of the STAR shape space from https://github.com/ahmedosman/STAR, simply included locally for simplicity. 
3. Run `jupyter notebook` and choose `template_mesh_fitting_demo.ipynb`.
