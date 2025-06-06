# Google-Colab-Time-Out-Preventer

This repository contains a code snippet that prevents Google Colab from timeout. Google Colab is a cloud-based platform that allows you to write and execute Python code in your browser, with free access to GPUs and TPUs. However, Google Colab may disconnect your session due to inactivity or network issues, which can cause you to lose your work or progress. This code snippet uses IPython and google.colab modules to click the connect button every 60 seconds automatically, which keeps your session alive and prevents timeout.

## How to use this repository

To use this repository, you need to have a Google account and access to Google Colab. You can go to [Google Colab](https://colab.research.google.com/) and create a new notebook or open an existing one. Then, you can copy and paste the code snippet from the README file of this repository into a code cell and run it. This will start a loop that will click the connect button every 60 seconds. You can also clone this repository to your Google Drive or GitHub account and open the notebook file from there.

## Features

- Prevents Google Colab from timeout due to inactivity or network issues
- Uses IPython and google.colab modules to interact with the browser
- Runs in the background without interrupting your work
- Easy to use and modify

## More

- To learn more about Google Colab, you can check out this [link](https://colab.research.google.com/notebooks/intro.ipynb).
- To learn more about IPython, you can check out this [link](https://ipython.org/).
- To learn more about google.colab, you can check out this [link](https://colab.research.google.com/notebooks/snippets/importing_libraries.ipynb).
  
  
## Credits

- The code snippet is adapted from this [Stack Overflow answer](https://stackoverflow.com/a/57113206/13673747) by user [Kuldeep Singh](https://stackoverflow.com/users/11530618/kuldeep-singh).
