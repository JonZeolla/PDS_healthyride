# Analysis of the Healthy Ride Pittsburgh data
As a part of the 2017-09-06 ["Hands on Python"](https://www.meetup.com/PGH-Data-Science/events/242535873/) Pittsburgh Data Science event, attendees took a look at the [Healthy Ride Pittsburgh](https://healthyridepgh.com/data/) dataset and broke out into groups to do further analysis.  This is my playground for analyzing the data using Python 3 and Jupyter notebooks.

## Getting Started
### Working locally
Close the repository, install the Python 3 dependencies, and then open the appropriate Jupyter notebooks.  This assumes you already have [Python 3](https://www.python.org/downloads/) and [Jupyter notebooks](http://jupyter.org/install.html) already installed (If you are having issues, look at installing [Anaconda](https://www.anaconda.com/download/)).
```
git clone --recursive https://github.com/JonZeolla/PDS_healthyride
cd PDS_healthyride && pip3 install -r requirements.txt
jupyter notebook analysis/example.ipynb
```

### Navigating this repository
| Folder            | Description                                                           |
| ----------------- | --------------------------------------------------------------------- |
| `analysis`        | Jupyter notebooks that perform analysis.                              |
| `clean`           | A storage area for any processed Healthy Ride Pittsburgh data.        |
| `enriched`        | Ancillary datasets, which can be used to provide additional context.  |
| `original-event`  | All of the information from the original event.                       |
| `raw`             | An archive of the raw Healthy Ride Pittsburgh data.                   |

### Contributing
1. [Fork the repository](https://github.com/jonzeolla/PDS_healthyride/fork)  
1. Create a contrib branch via `git checkout -b contrib/description`  
1. Make your changes  
1. Commit your changes via `git commit -am 'Summarize the changes here'`  
1. Create a new pull request ([how-to](https://help.github.com/articles/creating-a-pull-request/))  

