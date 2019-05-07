# Early Adoptors Notebooks


The aim of this repository is to collect and manage notebooks of the ESDL Early Adoptors Call. 

## How To

The following steps describe the upload process:

```bash

cd ~/work/workspace
git clone https://github.com/esa-esdl/early_adoptors.git

cd early_adoptors

mkdir MyName
cd MyName
cp []/my_notebook.ipynb .

git commit -a -m "Added my notebook"
git push origin master
```

Any supplementary info can be added to your directory using the ```git add ``` strategy.

## When notebook is changed

```
cd early_adoptors/MyName

git commit -a -m "Added my notebook"
git push origin master

```

## Don't want to have it in the Public Space yet

In that case, you can use the same strategy as above. However, you should fork the repo into xour ew space. Once you are happy, you 
can start a so-called Pull Request from teh GitHub Website. The admin user will then merge your notebook into teh master repository.

