# Image Colorization

## Project of Vision And Cognitive Services

#### [Saverio Monaco](https://github.com/SaverioMonaco/)
#### [Filippo Zillotto](https://github.com/ZiliottoFilippoDev)

### Development cycle using Google Colab

#### Creating a branch
First you need to update your local _master_ branch with the one present on GitHub:

```git checkout master``` (to switch to master branch in case you are not)

```git pull origin master```

```git checkout -b NEWBRANCHNAME``` (to create a copy of master named NEWBRANCHNAME)

To make GitHub know of your new branch, just make a slight change in a file a make a dummy push:

```git commit . -m "dummy push"```

```git push origin NEWBRANCHNAME``` 

#### Working on the file
On GitHub, switch to your branch, then open Project.ipynb and click on _Open on Colab_.

...

To save the changes done on Colab to your branch click (on Colab)

```File -> Save a Copy in GitHub```
 
and make a commit to your own branch.

#### Updating the master branch with your changes
Just make a Pull Request from your branch to _master_


### References:
* https://richzhang.github.io/colorization/
* https://arxiv.org/abs/1603.08511
* https://arxiv.org/abs/1908.01311
