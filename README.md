
![](https://academichub.blob.core.windows.net/images/mit-active-learning-10-28.png)


Click the button below to launch [Binder](https://mybinder.org/):<br>
[![Binder](https://img.shields.io/static/v1.svg?logo=Jupyter&label=launch&message=Binder%0A%2B%0AAVEVA_DataHub&color=3d1152)](https://mybinder.org/v2/gh/academic-hub/notebooks-env/main?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Facademic-hub%252Fmit-bioreactor%26urlpath%3Dtree%252Fmit-bioreactor%252F%26branch%3Dmain)

The notebook can also be ran on [Google Colab](https://colab.research.google.com/) with its handy access to Google Drive:<br>
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/academic-hub/mit-bioreactor)

[Deepnote](https://deepnote.com/) is a nice service for cooperation, give it a try:<br>
[<img src="https://deepnote.com/buttons/launch-in-deepnote-small.svg">](https://deepnote.com/launch?url=https%3A%2F%2Fgithub.com%2Facademic-hub%2Fmit-bioreactor)

---
---

## Instructions for TAs

### Overview

This repository (https://github.com/academic-hub/mit-bioreactor) is a class notebook template to seed other repositories you can then modify at will. 

In summary it contains:

* one quick start notebook using the MIT bioreactor dataset
* save and restore notebook instructions within Binder

Below are the steps and details how to publish your own repository

### Class publication steps

Prerequisites:
* a Github account 
* an Academic Hub account for data accesses (register at https://academic.osisoft.com/register)

We recommend [Github desktop](https://desktop.github.com/) for dealing with Github repository. **The steps below assumes it is already installed on your laptop.**

2. Fill in the information as indicated below to create a new repository:<br>![](https://academichub.blob.core.windows.net/hub/binder/hub-ta-binder-step2.png)<br><br>
3. Clone the repository on your laptop with the simple step shown below:<br>![](https://academichub.blob.core.windows.net/hub/binder/hub-ta-binder-step3.png)<br><br>
4. Modify the content for the class as needed. Note that an installation of [Anaconda](https://repo.anaconda.com/archive/Anaconda3-5.3.1-Windows-x86_64.exe) is required to modify and run the notebook 
5. Once the repository on Github is ready for publication, go to https://github.com/academic-hub/notebooks-env#link-generator-for-binder-based-classes and follow the steps to build a link to the class repo:<br>![](https://academichub.blob.core.windows.net/hub/binder/hub-ta-binder-link-gen.png)<br><br>
5. Add the following markdown to the README.md of the class repo, replace `<step-4-link>` by the generated URL from Step 4:

```
    [![Binder](https://img.shields.io/static/v1.svg?logo=Jupyter&label=launch&message=Binder%0A%2B%0AAVEVA_DataHub&color=3d1152)](<step-4-link)
```

Your Github class repository is now ready to be shared with students, just distribute its URL. 

No Github account is necessary to run notebooks. **But data accesses do require an AVEVA Academic Hub account for each student. Please go to https://academic.osisoft.com/new-class for details.**


