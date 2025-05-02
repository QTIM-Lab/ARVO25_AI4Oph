# ARVO25 Artificial Intelligence in Ophthalmic Research course
Repo for the ARVO 2025 Artificial Intelligence in Ophthalmic research course

## Exercise 1: Using ChatGPT to extract data from a screenshot

For this exercise, we will upload a screenshot taken from a csv file for the GRAPE dataset (available [here](https://springernature.figshare.com/collections/GRAPE_A_multi-modal_glaucoma_dataset_of_follow-up_visual_field_and_fundus_images_for_glaucoma_management/6406319)).

The GRAPE dataset includes information about patient's gender, age, and eye-specific Intra-Ocular Pressure (IOP).

To run this exercise, you'll need to:
- go to [ChatGPT](https://chatgpt.com/)
- upload the file `files/GRAPE_screenshot.png` and type the prompt "can you extract the data in the provided screenshot and return it in csv format?”

At this point, ChatGPT will provide a link to download the generated csv file.

It may also ask follow up questions on performing additional processing or data analysis on the extracted data.

## Exercise 2: Simple data analysis like regression, plotting

The goal of this exercise is to show how simple data analysis, plotting, and machine learning can be carried out by ChatGPT.

> NB: the free ChatGPT subscription will limit the number of requests for data analysis, for thorough analysis a PLUS subscription may be required

We provide a notebook that can be run locally in the [exercise_2](/exercise_2/ex_2_plotting.ipynb) folder. Running this notebook will require python and Jupyter Notebook to be installed as well as installation of the necessary python libraries.

To avoid local installation, we also provide a Colab notebook that can be run in the cloud [here](https://colab.research.google.com/drive/1B-mMiSrklHBGptPGs1_PQ-lE8yg778fS?usp=sharing)

We will use the (full) GRAPE dataset provided at `files/grape_img_info_w_file` to plot age distributions, change the appearance of plots, perform statistical analysis on the data, and train a simple linear regression model to predict IOP from age and gender (not clinically relevant but useful to illustrate our purposes).

## Exercise 3: Using NotebookLM

The goal of this exercise is to illustrate the abilities of NotebookLM to distill information from pdf file(s).

For this exercise, you'll need to:
- go to [NotebookLM](https://notebooklm.google.com/)
- upload the files provided in the folder `files/papers` (or any collection of papers you are interested in analyzing)

Examples of questions that can be asked are:
- can you provide a paragraph summarizing the uploaded papers?
- can you go into more details on the role of the fellow eye status as a potential biomarker for the progression rate of GA?
- can you identify one common limitation of these studies that could be leveraged for future research?

In addition, similarly to ChatGPT, NoteBookLM also allows you to reformat information stored in a pdf. For instance, answers to medical intake forms provided by patients by circling out options can be automatically extracted and re-arranged in a csv file automatically. 