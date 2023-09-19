# IEEE-TKET-TUTORIAL

Join our public slack channel!

[![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)](https://tketusers.slack.com/join/shared_invite/zt-18qmsamj9-UqQFVdkRzxnXCcKtcarLRA#/shared-invite/email)

There are two main folders one for each tutorial section. Find the slides and notebooks for each section in the corresponding folder.

Note that you will not be able to run all of the cells in the repetition code (Tutorial 2) notebook unless you have a quantinuum account.

## Installing the required packages

For dependency management, we recommend that you set up a virtual environment. The required pytket packages are also installed in the qbraid platform. Alternatively you can use conda or whatever you're used to.

Note that in order to use the latest version of pytket you will need to use python 3.9, 3.10 or 3.11.

First, clone the repository.

```shell
git clone git@github.com:CalMacCQ/IEEE-TKET-TUTORIAL.git
```

Next we recommend that you install the required packages in a virtual enviornment inside the `IEEE-TKET-TUTORIAL` directory.


### MacOS and Linux installation

If you're a linux or Mac user you can set up a virtual environment as follows.

```shell
cd IEEE-TKET-TUTORIAL
python -m venv ".venv"
```
This enviornment can be activated as follows

```shell
source .venv/bin/activate
```
Now we can install packages into this virtual envionment using pip. Install the required packages from the `requirements.txt` file.

```
pip install -r requirements.txt
```

These package versions will be isolated from other packages on your machine. This is helpful for avoiding dependency conflicts.

The jupyterlab package will be installed as a requirement. To start the jupyter notebook server run the following

```shell
jupyter-lab
```

### Windows installation

Create a venv on windows as follows...

```shell
cd IEEE-TKET-TUTORIAL
python -m venv ".venv"
```

Now activate with

```shell
.venv\Scripts\activate.bat
```

Now install packages

```shell
pip install -r requirements.txt
```


