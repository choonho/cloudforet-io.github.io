---
title: "Collector History"
linkTitle: "Collector History"
weight: 1
date: 2021-07-31
description: >
    Look up and manage the monthly change history of the collector.
---

# Collector History

## Overview

On the Collector History page, you can check the monthly changes of the various resources collected
through the Collector Plugin on SpaceONE.

## Collector History

You can check the monthly job status collected by the Collector. Job is the result of performing according to the schedule that you set up the actions for the Collector.

![](/docs/using_spaceone_console/admin_guide/management/collector-history_img/collector-history_image_01.png)

Main Graph shows the status of the number of jobs collected. The number of successful and unsuccessful jobs is shown on graph. When you click a point, job list details are shown in the form of the table below.

You can move the month through `< >` at the top right of the graph.

#### Collector History Detail

![](/docs/using_spaceone_console/admin_guide/management/collector-history_img/collector-history_image_02.png)

 You can check list of successful and unsuccessful jobs respectively in 3 status. 

Using the search bar, You can search Job ID, Status, Start Time for Job collected through Collector History.

![](/docs/using_spaceone_console/admin_guide/management/collector-history_img/collector-history_image_03.png)

The information of the job can be viewed on the Collector history page is as follows.

| Title | Description |
| :--- | :--- |
| Job ID | Id of Job |
| Collector Name | Name of the Collector which performed the job |
| Status | Status showing the job performance results of the Collector  |
| Task \(completed / total\) | Number of the tasks completed among the whole tasks |
| Start Time | Job start time |
| Duration | Job running time |



## Job Detail

![](/docs/using_spaceone_console/admin_guide/management/collector-history_img/collector-history_image_04.png)

When you click an individual job in the job list on the Collector history page, you can check the details on the Job Management page.

At the top of the page, you will see the collector and cloud provider that collected the job.


#### Task Search

You can search service account, project, status for job's task collected by Collector History.

![](/docs/using_spaceone_console/admin_guide/management/collector-history_img/collector-history_image_05.png)

#### 

#### Task List Search

At the bottom of the page, a list of tasks is shown according to Job status. The information of Task that you can see on this page is as follows.

| item | Description |
| :--- | :--- |
| No | task order |
| Service account | Service Account assingned to task |
| Project | project that task belongs |
| Status | performance status of task |
| Created | number of resource created |
| Updated | number of resource updated |
| Error | cause of task failure |
| Start time | task start time  |
| Duration | task running time |

When the status of job is failure, you can see the cause of task failure in the Error list at the bottom.

![](/docs/using_spaceone_console/admin_guide/management/collector-history_img/collector-history_image_06.png)


