---
layout: post
title: "Download the Data"
description: "This tutorial covers the data and set up the data directory you 
will need for the Institute."
date: 2016-05-17
dateCreated: 2016-06-09
lastModified: 2016-06-09
estimatedTime: 
packagesLibraries:
authors: Megan A. Jones
contributors:
categories: [tutorial-series]
tutorialSeries: [pre-institute0]
mainTag: pre-institute0
code1: 
image:
 feature: data-institute-2016.png
 credit:
 creditlink:
permalink: /tutorial-series/download-data
comments: true
---


{% include _toc.html %}

## NEON Teaching Datasets
Many NEON tutorials, available through the 
[NEON Data Skills portal](http://www.NEONdataskills.org) and the 
[NEON Data Institute 2016 portal](http://neonscience.github.io/neon-data-institute-2016/),
utilize teaching data subsets which are hosted on the NEON Data Skills 
<a href="https://figshare.com/authors/NEON_Data_Skills_Teaching_Data_Subsets/834136" target="_blank">fig**share** repository</a>. 

We recommend downloading the complete Data Institute teaching data subsets from the 
button in the instructions below. 
The required dataset(s) will also be available to download at the start of each 
tutorial series in the **Download Data** section. 

## Download & Uncompress the Data

#### 1) Download
First, we will download the data to a location on the computer. To download the 
data for this tutorial, click the blue button **Download NEON Teaching Data 
Subset: Data Institute 2016**. 


<div id="objectives" markdown="1">


### Download Data


{% include/dataSubsets/_data_Data-Institute-16-TEAK.html %}
{% include/dataSubsets/_data_Data-Institute-16-SJER.html %}
{% include/dataSubsets/_data_Data-Institute-16-SOAP.html %}


</div>

After clicking on the **Download Data** button, the data will automatically 
download to the computer. This is a large file so it might take a while to 
download. 

#### 2) Locate .zip file
Second, we need to find the downloaded .zip file. Many browsers default to 
downloading to the **Downloads** directory on your computer. 
Note: You may have previously specified a specific directory (folder) for files
downloaded from the internet, if so, the .zip file will download there. 

<figure>
	 <a href="{{ site.baseurl }}/images/pre-institute-content/pre-institute0-setup/DI16-Download_AllSets.png">
	 <img src="{{ site.baseurl }}/images/pre-institute-content/pre-institute0-setup/DI16-Download_AllSets.png"></a>
	 <figcaption> Screenshot of the computer's Downloads folder containing the
	 newly downloaded file. Source: National Ecological
	 Observatory Network (NEON) 
	 </figcaption>
</figure> 

#### 3) Move to **NEONDI-2016** directory
Third, we must move the data files to the location we want to work with them. 
We recommend moving the .zip to a dedicated **NEONDI-2016** subdirectory within a 
**data** directory in the
**Documents** directory on your computer (**~/Documents/data/NEONDI-2016**). This 
**NEONDI-2016** directory can then be a repository for all data subsets you use 
for the NEON Data Institute tutorials. 

Note: If you chose to store your data in 
a different directory (e.g., not in **~/Documents/data/NEONDI-2016**), modify 
the directions below with the appropriate file path to your **NEONDI-2016** 
directory. 


<i class="fa fa-star"></i> **Data Tip:** All NEON Data Skills tutorials are
written assuming the working directory is the parent directory to the 
uncompressed .zip file of downloaded data -- **NEONDI-2016**. This allows for multiple data 
subsets to be accessed in the tutorial without resetting the working directory. 
If you choose to put your data elsewhere, you must remember to modify the working 
directory and/or file paths when going through the tutorials. 
{: .notice}

#### 4) Unzip/uncompress
Fourth, we need to unzip/uncompress the file so that the data files can be 
accessed. Use your favorite tool that can unpackage/open .zip files (e.g.,
winzip, Archive Utility, etc). Depending on the tool you use to uncompress the files,
you may need to individually uncompress the individual files (SOAP, SJER, and TEAK)
within the main file. 


#### 5) Combine the Subsets
Fifth, we need to put all three data subsets within a single directory structure. 
The directory should be the same as in this screenshot (below). We want the TEAK,
SJER, and SOAP data subsets within the **NEONdata** subdirectory. 

<figure>
	 <a href="{{ site.baseurl }}/images/pre-institute-content/pre-institute0-setup/AllSets_FileStructureScreenShot.png">
	 <img src="{{ site.baseurl }}/images/pre-institute-content/pre-institute0-setup/AllSets_FileStructureScreenShot.png"></a>
	 <figcaption> Screenshot of the <b></b> directory structure: nested 
	 <b>Documents</b>, <b>data</b>, <b>NEONDI-2016</b>, and other 
	 directories. Source: National Ecological Observatory Network
	 (NEON) 
	 </figcaption>
</figure> 

Due to difference in the tools used to uncompress the zipped files, the name of 
the directory you initially see once unzipping is complete may differ. The most straight 
forward way to set up this structure, is to open the newly 
unzipped TEAK directory, within it you will find a **NEONdata** and an **outputs** 
directories. Now open the unzipped SJER and SOAP directories until you get to 
subdirectories named **SOAP** or **SJER**. Transfer only these two subdirectories 
to the **NEONdata** directory originally from the unzipped TEAK directory. 
If necessary, move this **NEONdata** directory so that it is within **NEONDI-2016** 
directory. 


You will now have all the teaching data subsets that will be used in the NEON
Data Institute 2016. 
