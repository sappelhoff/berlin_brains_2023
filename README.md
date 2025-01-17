# Berlin Brainwaves: Advanced EEG Analysis with MNE Python @ Campus of Cognition

This is the repository for a 2-day workshop on advanced topics in M/EEG analyis using [MNE-Python](https://github.com/mne-tools/mne-python).
The workshop is taking place October 12th-13th, 2023 in [Berlin](https://maps.app.goo.gl/nuLLdxN6jgG276e28).

## How to get there

Please see the folder `how_to_get_there` for further instructions on how to find the workshop location.

## Materials

Authors of the material:

- [Stefan Appelhoff](https://stefanappelhoff.com/), Max Planck Institute for Human Development, Berlin
- Nikolai Kapralov, Max Planck Institute for Human Cognitive and Brain Sciences, Leipzig
- [Marijn van Vliet](https://cmhc.fi), Aalto University, Finland
- Carina Forster, Max Planck Institute for Human Cognitive and Brain Sciences, Leipzig
- Britta Westner, Radboud University Nijmegen, Donders Institute

## Before you arrive

Please make sure you do the following steps before the first hands-on session:

1. You will need to download this directory of scripts.
1. You will need to [download the data](https://drive.google.com/file/d/1etefiAIRG6CMBeU91Fu2CTqM5KT9Ng_Z/view?usp=sharing).
1. You will need to have an up-to-date version of MNE-Python installed on your machine (you need a *full install* with all dependencies, **not** "MNE-Python with core functionalities only"). See instructions at: https://mne.tools/stable/install/index.html
1. You will need to have the very latest version of MNE-RSA (v0.9) installed either through PIP (`pip install mne-rsa`) or through conda using the conda-forge channel (`conda install -c conda-forge mne-rsa`).
1. You will need Panel and Streamlit frameworks as well as several other packages (fooof, PyQt5, mne_bids) for the tutorials on creating interactive apps. They can be installed using PIP (`pip install --upgrade fooof mne_bids panel PyQt5 streamlit`).
1. To check your installation, please look at the (very short!) notebook [Check your installation](Installation_check.ipynb). See below if you need a reminder how to start it.
1. Additionally, to test whether Streamlit is working properly, run `streamlit hello` or `python -m streamlit hello`. A new tab (or window) should open in your browser with demo examples of other apps based on Streamlit.
1. Please read the section on the MNE homepage on how to [contribute to MNE](https://mne.tools/stable/install/contributing.html) and follow the instructions until the part where we create a virtual environment. If you feel up for it you can of course also complete the whole setup.
1. If you are not familiar with Python, we invite you to take the time to work on these tutorials:
[Intro to Python](intro_to_python/0a-Intro_Python.ipynb), [Intro to Numpy](intro_to_python/0b-Intro_Numpy.ipynb).

### Start a Jupyter notebook

To start a Jupyter notebook, open your terminal and navigate to the directory where you saved this directory of scripts.
Then type the command `jupyter notebook` and Jupyter should open in your internet browser.
Click on the notebook you want to run!

## Program

See also the schedule: https://docs.google.com/document/d/11x1XO39NtUT6g0h45SEwk2834KM2GQ6pdLJSPC6i3VU/edit?usp=sharing

### Day 1 (Thursday October 12, 2023)

Morning session: 09:30 am to 1:00 pm

- 09:30 to 11:00 am: Carina: How to contribute to MNE/github pull requests
- 11:30 am to 1:00 pm: Nikolai: Turning MNE-based analysis into an interactive app

Afternoon session: 2:00 pm to 5:30 pm

- Marijn: Representational similarity analysis with MNE-RSA, including performing statistical analysis using cluster-based permutation testing

### Day 2 (Friday October 13, 2023)

Morning sesssion: 09:30 am to 1:00 pm

- Britta: Source localization in M/EEG and beamforming

Afternoon session: 2:00 pm to 5:30 pm

- Stefan: [MNE-BIDS](https://github.com/mne-tools/mne-bids)

## References and credit

The code from this tutorial is heavily inspired from this article:

	Mainak Jas, Eric Larson, Denis Engemann, Jaakko Leppakangas, Samu Taulu, Matti Hamalainen,
	and Alexandre Gramfort. 2018. A Reproducible MEG/EEG Group Study With the MNE Software:
	Recommendations, Quality Assessments, and Good Practices.
	Frontiers in Neuroscience. 12, doi: 10.3389/fnins.2018.00530

The MNE software when used in publications should be acknowledged using citations.

To cite MNE-C or the inverse imaging implementations provided by the MNE software, please use:

	A. Gramfort, M. Luessi, E. Larson, D. Engemann, D. Strohmeier, C. Brodbeck, L. Parkkonen,
	M. Hämäläinen, MNE software for processing MEG and EEG data, NeuroImage, Volume 86,
	1 February 2014, Pages 446-460, ISSN 1053-8119.

To cite the MNE-Python package, please use:

	A. Gramfort, M. Luessi, E. Larson, D. Engemann, D. Strohmeier, C. Brodbeck, R. Goj, M. Jas,
	T. Brooks, L. Parkkonen, M. Hämäläinen, MEG and EEG data analysis with MNE-Python,
	Frontiers in Neuroscience, Volume 7, 2013, ISSN 1662-453X.

To cite the MNE-BIDS package, please use:

	Appelhoff, S., Sanderson, M., Brooks, T., Vliet, M., Quentin, R., Holdgraf, C., Chaumon, M.,
	Mikulan, E., Tavabi, K., Höchenberger, R., Welke, D., Brunner, C., Rockhill, A., Larson, E.,
	Gramfort, A., & Jas, M. (2019):
	MNE-BIDS: Organizing electrophysiological data into the BIDS format and facilitating their analysis.
	Journal of Open Source Software, 4:1896. DOI: 10.21105/joss.01896
