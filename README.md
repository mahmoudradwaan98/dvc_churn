## Git

``` bash

git init

git add .

git commit -m "msg"

git branch -M main

git remote add origin < ssh link or http link >

git push

git status


```

## DVC

``` bash

dvc init

dvc add ./data/ ./models/

dvc remote add --default myremote  gdrive://1wTYm3V6Wa1-BHwBHqKrMM_o5vR1Ay2Zp

dvc push

dvc status

```

## `Churn Detection with use of CML & DVC Tools `
    * Using different approaches for solving imbalancing dataset.
    * Using different Algorithms also.
-------------------
### Note
> `cml-churn.yaml` file is attached to this directory. You can put it in `.github/workflows/cml-churn.yaml` as usual.
------------------------