# Exploratory data analysis of ultrasound scans
For my capstone I am building computer vision algorithms to identify objects in ultrasound images. Because we want to be able to scan multiple areas I decided to see if I could make a statistical model to identify different scan locations so we could apply the correct machine learning algorithm autonomously. 
# Results 
Using naieve bayes I was able to find a statistically significant difference in the pixel values between ultrasound images of different ultrasound scan locations.
# Warings
This will download about 3.5 gigabytes of sample data onto your computer when run. If you want to get rid of this information after you have run the notebook I reccomend running 
```
git clean -xdf
```
to remove any and all unwanted files from the repository

The notebook depends on some unix command line functions such as `tar`, `rm`, and `tree` to run. I reccomend using windows subsystem for linux or linux itself to run this!
# Use
All exploration, data and results are documented in the `notebook.ipynb` file. 
## Package management
As long as your chosen python enviroment has *pip, ipython, and ipykernel*
then you can run the notebook. It will automatically install all other needed packages using pip by reading from the `requirements.txt` file
## Data Management
All data will be stored locally under a directory called `data/` and will be downloaded if not present automatically by the notebook
# Credits
All files are sources from a contribution by the [butterfly network](https://www.butterflynetwork.com/) for [MIT Grand Hack 2018](https://grandhack.mit.edu/nyc-2018/) and cannot be used in any capacity outside a personal project. They were very kind to provide the data and should have their rights respected!
