---
title: Documenting as You Go
teaching: 0
exercises: 0
questions:
- "Key question"
objectives:
- "Understand how to effectively document **during the process**"
- "Uploading files"
- "Version control on the OSF"
- "Understanding the importance of certain lifecycle points"
- "Creating Registrations"
- "GUIDs/DOIs"
keypoints:
- "First key point."
---


## Files and Version Control
Now we want to start actually working on our project.

We had previously uploaded our materials when we set up the storage, but now we need to make sure we upload our data.

You always want to **keep a copy of our complete, raw data file.** Even if we end up doing a lot of data cleaning, or only using a subset of the datafile for our analyses, we want to keep a raw, untouched version of the data file to make sure we can always create our analyses from start to finish.

---

>## Upload raw data file and data dictionary
>
>* Name the data file accordingly and upload it to the appropriate section of you project.
>  * If you need a data file, download and use this file <gapminder.csv>
>* We also want to upload the data dictionary so we’ll always know what our variable names actually mean.
{: .challenge}

So now we have the static version of all these different files, but in real research, things often change over time. We need a way to easily track those changes. This tracking of different versions of a file is usually called **version control**. Often times people have their own ad-hoc version control procedures which can be confusing.

Poor version control can make finding files and recreating experiments/analyses very difficult, because in a few months it may take days for you to figure out, if you can at all, exactly what protocol was used, or exactly which analysis file was used to produce the results in the paper you submitted.

We want to make sure this doesn’t happen to us.

There are some programming languages out there that are specifically built for version control, many of you may have heard of **Git and Github**, and those are great, but they can prove to be a barrier to adoption of good version control methods for people who either don’t have the time or motivation to learn how to use them.

The OSF has **built in version control** in an accessible way to help lower that barrier.

Version control on the OSF works in a few different ways.

* **For text files:** You can edit directly on the site and save the new versions. This is a possible with the wiki, and for anything that will render as a plain text file. So, if I go to the R script I uploaded, you’ll notice an ‘edit’ button in the top right corner. I can click on that, and edit this script directly on the OSF, and the edits will be saved as a new version, the same thing with the wiki.

* **For non-text files:** the procedure is a little different. You’ll open the file on your personal computer, and make any changes that you want. Then **save the file with the exact same name on your computer.** So, on your computer, you’ve just **over-written** the older version of the file. Now, go to the OSF and upload the file with the **same name to the same component**, once the file is uploaded you can click on that file and see that there are now 2 versions of the file, and you can toggle between them.

Now that I’ve shown the ways version control works on the system, I want you to edit your projects.

> ## Update wiki to reflect analyses done & clearly comment analysis scripts
>
> 1. Go into the wiki and update it so that it reflects that analyses you actually performed.
> 2. One of you who didn’t run the analyses, please look at the analysis script that was uploaded, and edit it to make sure that it is clearly commented.
> 3. How you do this will depend on the exact way in which the file was uploaded.
> 4. If you don’t know how to comment in the particular language the analysis was done, ask the person who did the analyses.
{: .challenge}

> ## Update wiki to include navigational README for the project
> The final thing we want to do is make sure that we give our future selves and, potentially, other people information about how to navigate our project.
> What are our files, where can we find things, if information is missing or private, why?
> Basically, we want to create a **README** for the project.
> We’ve already done a bit of this by putting information about the research question for the project in the wiki. But, we also want to add information there, and/or in the wikis of our subcomponents about what files are there and how to navigate through the project.
{: .challenge}
