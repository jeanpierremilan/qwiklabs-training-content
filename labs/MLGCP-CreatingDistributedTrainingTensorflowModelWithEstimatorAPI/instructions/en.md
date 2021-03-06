# Creating a distributed training TensorFlow model with Estimator API


## Overview

*Duration is 1 min*


This lab is part of a lab series, where you go from exploring a taxicab dataset to training and deploying a distributed model with Cloud ML Engine. In the next course of this specialization, we will work on improving the accuracy of this model using feature engineering.

### __What you learn__

In this lab, you will :

* Learn the importance of watching your validation metrics while training is in progress
* Use the estimator.train\_and\_evaluate function
* Monitor training using TensorBoard


## Setup


![[/fragments/start-qwiklab]]


## Launch Cloud Datalab


![[/fragments/setup-datalab]]


## Clone course repo within your Datalab instance


![[/fragments/clone-repo-in-datalab]]



## Refactor for Distributed training and monitoring

*Duration is 15 min*


__Step 1__

In Cloud Datalab, click on the __Home__ icon, and then navigate to __datalab \> notebooks \> training-data-analyst \> courses \> machine\_learning \> deepdive \> 03\_tensorflow \> labs__ and open __d\_traineval.ipynb__.

<aside class="warning"><p>Note: If the cloud shell used for running the datalab command is closed or interrupted, the connection to your Cloud Datalab VM will terminate. If that happens, you may be able to reconnect using the command ‘<strong>datalab connect mydatalabvm</strong>&#39; in your new Cloud Shell. Once connected, try the above step again.</p>
</aside>

__Step 2__

In Datalab, click on __Clear | Clear all Cells__ (click on Clear, then in the drop-down menu, select Clear all Cells).

Now read the narrative and execute each cell in turn.

__Step 3__

Compare to solution

In the parent level 03\_tensorflow folder (above labs/) there is the solution notebook with the same title for comparison.

![[/fragments/endqwiklab]]

Last Tested Date: 12-04-2018

Last Updated Date: 12-18-2018

![[/fragments/copyright]]
