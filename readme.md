# CSE 576 Topics in Natural Language Processing

Phase 2: Automated Data Creation

**Goal**

Creates a visual referring expression dataset by converting existing QA data (v7w pointing) to expressions using Stanford NLP parser.

**Process Used**

This code uses Stanford NLP parser (Stanza) to parse the questions in the v7w pointing dataset and get POS (part of speech) tagging. Using the tags, we try to convert the questions into referring expressions by removing some tags in the parsed text.

**How to Run the Code**

To run the code follow the below steps:

1. Download the data folder from this dropbox link:

    [https://www.dropbox.com/sh/6o971duivp7zjqg/AABQ7rN5wjaNZcLMnC-RvCnWa?dl=0](https://www.dropbox.com/sh/6o971duivp7zjqg/AABQ7rN5wjaNZcLMnC-RvCnWa?dl=0)

This contains the JSON file (dataset\_v7w\_pointing.json) and the images.

2. Run the code on the google collab (link below):

    [https://colab.research.google.com/drive/1OiqlnmpDRiP2KS6o3D0SyecFox34ykOp?usp=sharing](https://colab.research.google.com/drive/1OiqlnmpDRiP2KS6o3D0SyecFox34ykOp?usp=sharing)

3. No explicit installation is required. All the libraries are downloaded on the go. Due to this, the code might take some time to start the processing.
4. Also, I&#39;m using google collab&#39;s files.upload() to upload the required JSON. When this cell is run, you need to upload the JSON file (dataset\_v7w\_pointing.json) that was downloaded in step 1.

**Output**

The output of this exercise is a new JSON file with a list of bounding boxes and referring expression pairs.
