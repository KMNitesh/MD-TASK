# MD-TASK

A suite of Python scripts that have been developed to analyze molecular dynamics trajectories. Detailed documentation on how to install and use MD-TASK can be found on our [ReadTheDocs](http://md-task.readthedocs.io/en/latest/index.html) site.

### Project Status
| Branch | Build Status                                                                                                              | Code Style                                                                                                                                                                                                                                                    | Coverage | 
|--------|---------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------| 
| Master (1.0.x) | [![Build Status](https://travis-ci.org/RUBi-ZA/MD-TASK.svg?branch=master)](https://travis-ci.org/RUBi-ZA/MD-TASK) | [![Codacy Badge](https://api.codacy.com/project/badge/Grade/f81d8d8016094467a836dd3ef1c42908)](https://www.codacy.com/app/davidbrownza/MD-TASK?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=RUBi-ZA/MD-TASK&amp;utm_campaign=Badge_Grade) | n/a      | 
| 1.1.x | [![Build Status](https://travis-ci.org/RUBi-ZA/MD-TASK.svg?branch=1.1.x)](https://travis-ci.org/RUBi-ZA/MD-TASK) | [![Codacy Badge](https://api.codacy.com/project/badge/Grade/f81d8d8016094467a836dd3ef1c42908?branch=1.1.x)](https://www.codacy.com/app/davidbrownza/MD-TASK?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=RUBi-ZA/MD-TASK&amp;utm_campaign=Badge_Grade) | n/a      |
| 1.0.x | [![Build Status](https://travis-ci.org/RUBi-ZA/MD-TASK.svg?branch=1.0.x)](https://travis-ci.org/RUBi-ZA/MD-TASK) | [![Codacy Badge](https://api.codacy.com/project/badge/Grade/f81d8d8016094467a836dd3ef1c42908?branch=1.0.x)](https://www.codacy.com/app/davidbrownza/MD-TASK?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=RUBi-ZA/MD-TASK&amp;utm_campaign=Badge_Grade) | n/a      |

MD-TASK consists of a suite of Python scripts that have been developed to analyze molecular dynamics trajectories. Detailed documentation can be found on our [ReadTheDocs](http://md-task.readthedocs.io/en/latest/index.html) site.

## Installation

*Download the project:*
```bash
git clone https://github.com/RUBi-ZA/MD-TASK.git
cd MD-TASK
```
*Install dependencies and set up Python virtual environment:*
```bash
sudo apt-get install virtualenvwrapper python-dev libblas-dev liblapack-dev libatlas-base-dev gfortran libpng-dev libfreetype6-dev python-tk r-base
sh install.sh
```
*Install igraph package for R:*
```bash
R
> install.packages("igraph")
```

## Usage

The scripts are located in the root directory of the project. To run the scripts, ensure that the virtual environment is activated. For more info, find detailed documentation [here](http://md-task.readthedocs.io/en/latest/index.html). 

