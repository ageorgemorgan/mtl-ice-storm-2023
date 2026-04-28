<h1 align="center">
  The April 2023 Ice Storm in Montréal
</h1>

<p align="center">
  <img width="750" height="561" alt="HERO_IMAGE" src="https://github.com/user-attachments/assets/fae70dbd-c158-4834-ad1c-e3564757e61e" />
</p>
<p align="center">
  <i>
    Pictured: contours of sea-level pressure and wind barbs during the storm, indicating a strongly ageostrophic flow.
  </i>
</p>

A little project on the April 2023 Ice Storm in Montréal, QC I completed for ESSE 4240 at York University in Fall 2025. 

<h2 align="left">
  How to use this code
</h2>

In the interest of making the code as easy to run as possible, this repo includes a YAML file (``esse4240_project_env.yml``) for creating a Conda virtual environment ``esse4240_project`` containing all dependencies. You will have to edit the last line of this YAML file manually to point to the directory on your machine where your Conda environments are stored. Once you’ve made this change make sure you have ``cd``'d into your local copy of this repo. Then run the terminal command

```
conda create env --file=<path-to-yaml>
```

Once the environment is created, type 

```
conda activate esse4240_project
```

and the environment will activate. 

To make sure you can use this environment as a Jupyter kernel so you can use the notebooks, type the following: 

```
python -m ipykernel install --user --name esse4240_project --display-name “Python (esse4240_project)”
```

This command uses the ipykernel package to turn our Conda environment into a Jupyter kernel! Now that this is done, start a Jupyter session. You should be able to select ``Python (esse4240_project)`` as a kernel, and you’re ready to go!

<b>WARNING</b>: The dependencies include Python support for ffmpeg, which I use to make movies. In other circumstances, however, I’ve found that getting ffmpeg to work is a bit of a pain, so I can’t guarantee that the code for producing movies will run properly without further work. 

<b>
  Please see the report and slides for complete details! Happy reading!
</b>
