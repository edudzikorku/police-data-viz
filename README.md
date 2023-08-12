# Geospatial Analysis of Crime and Policing 👮

Link to Github Issue: [https://github.com/DSML-Research-Group/public-projects/issues/2](https://github.com/DSML-Research-Group/public-projects/issues/5)

# The Big Idea 💡
"Big Idea": We want to use a comprehensive dataset from the Chicago Police Department that identifies the spatial characteristics of crime and police force used over different neighborhoods and different locations throughout the city.  We'd like to turn this into a compelling visualization deployed over the web, as well as perform geo-spatial clustering analysis to identify novel spatial trends in crime and policing.

# Helpful Links 🔗
 - Link to All of the Data Files: (https://drive.google.com/drive/folders/1UpXFHClKiDL_S6lEkulFx7tGXVgLpqUs?usp=sharing)

# Roadmap 🗺️
The current roadmap is this:
 - [x] Collect initial datasets to use for the project
 - [ ] Begin with some initial visualizations and charts to better understand the data
 - [ ] Develop a list of experimental techniques to apply to the data
 - [ ] Incorporate results from previous step into visualizations
 - [ ] Write up results, and publish through different mediums

# Current Questions ❔
Current issues that are being discussed are:

 - What are the basic spatial patterns in crime throughout Chicago?
 - How is crime correlated temporally?
 - How consistently does increased crime result in increased policing and vice-versa?

# Installation 🖥️
To install the project on your computer locally, please follow these steps:

1).  Fork the repo to your own account

2).  Copy the URL of the git file (this is not the public url of the repo)

3).  From your command line or in Github Desktop run the command `git clone git_repo_location`

To install the dependencies, you can then run the commands:

### Regular Python 🐍
`cd police-data-viz`

`pip install -r requirements.txt`

### With Anaconda 🐍
If you'd like to create a development environment with anaconda, you can install everything you need with the `environment.yaml` file by following these steps:

First navigate into the root directory of the repo with this line:

`cd police-data-viz`

`conda env create -f environment.yaml`

If you then want to activate that environment you can do so with the command:

`conda activate police_data_viz`
