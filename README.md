# IDA Tor Network Data set

## Introduction

The datasets were collected in the IDA lab. and preprocessed for website fingerprinting.

## Directory structure

* TorDataset
  * HIDDEN
    * 191006: The name of the folder indicates the time when the collection ended. *Only Tor broswer used.*
      * HIDDEN_191006.spa
      * class_label.txt: Class labeling related to the dataset.
  * TBB
    * 191004: The name of the folder indicates the time when the collection ended. Data was collected using the Tor browser bundle.
      * TBB_191004.spa
      * class_label.txt: Class labeling related to the dataset.
  * WGET
    * 190829: The name of the folder indicates the time when the collection ended. Data was collected using WGET + torify.
      * WGET_190829.spa
      * class_label.txt: Class labeling related to the dataset.

## Feacture vector

|       Feature group        | No. of features |
| :------------------------: | :-------------: |
|    General information     |       44        |
|    Cell sequence length    |        4        |
| Cell interval arrival time |       27        |
|           Burst            |       24        |
|       Cell ordering        |       18        |
|       Concentration        |        8        |
|           Total            |       125       |

