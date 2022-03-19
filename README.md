# bmi706-2022

Repository for BMI 706 materials.


## Getting started

The problem sets for this course will be shared throughout the semester in
this repository. Follow the instructions below to configure your environment
so that you are able to:

- Work independently on the current problem set.
- Pull down the latest problem sets as they are released.

### Setting up your environment

#### Fork `hms-dbmi/bmi706-2022`

<img width="1209" alt="image" src="https://user-images.githubusercontent.com/19774198/159098237-d03f193a-f50a-499d-b3ee-4c336c52bab3.png">

For more details on forking, see the [GitHub documentation](https://docs.github.com/en/get-started/quickstart/fork-a-repo).

#### Clone the fork (`<YOUR-GITHUB-USERNAME>/bmi706-2022`) to your machine

Clone the fork to your local machine.

```bash
git clone git+https://github.com/<YOUR-GITHUB-USERNAME>/bmi706-2022.git
```

#### Configure `hms-dbmi/bmi706-2022` as the `upstream` remote for your fork

In order to pull down the latest assignments as they are released,
you will need to point your local clone to both your fork _and_ the original
`hms-dbmi/bmi706-2022` repository. The is accompished using git "remotes".

Make sure you `cd` into your local repository, then

```bash
git remote add upstream https://github.com/hms-dbmi/bmi706-2022.git
```

> You should only need to run this step once after cloning the repository

### Working on assignments

Each problem set for the course will be added to a folder in this repository
with the names `ps1`, `ps2`, and `ps3` respectively. Each folder will contain
additional instructions of how to get started. 

Although we will ask for files to be submitted on Canvas, please commit your
changes as you work. This will be important to sharing visualizations for Problem
Set 3 and the Final Project.

### Getting the latest assignments

As assignments are released, you will need to pull down the latest changes
to your fork. Running,

```
git pull upstream main
```

will pull the latest changes (newest problem sets) from `hms-dbmi/bmi706-2022`
as they are added.

### Useful Resources
- [Altair Documentation :link:](https://altair-viz.github.io/gallery/index.html)  
  You will use Altair, a Python visualization library, to create interactive visualizations in this course.
- [Pandas Documentation :link:](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html)
  You will use Pandas to read and process datasets for the visualization.
- [Google Colaboratory Documentation :link:](https://colab.research.google.com/)
  You will create visualizations and submit them using Google Colab notebook. 
