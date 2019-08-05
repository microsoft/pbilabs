<img style="float: right;" src="https://github.com/Microsoft/sqlworkshops/blob/master/graphics/solutions-microsoft-logo-small.png">

# Power BI CAT Labs
## (https://aka.ms/powerbi_labs)

This site is a map of learning content produced by and curated by the Power BI Customer Advisory Team (PBICAT) team in Microsoft Engineering. These materials are meant to be instructor-led, but you can work through the materials on a test system on your own if desired. Labs are shorter and Workshops are more comprehensive. You can view all materials directly in this interface, or you can [view the raw github site for this content here](https://github.com/plebla372/labs). 

*See the license information at the bottom of this README.md file*

Find a problem? Spot a bug? [Post an issue here](https://github.com/Microsoft/sqlworkshops/issues) and we'll try and fix it.

## Power BI Data Modeling
- [Lab: Data Modeling Best Practices]
- [Lab: Preparing the Power BI Environment]
- [Lab: Incremental Refresh](https://github.com/microsoft/pbilabs/tree/master/Incremental%20Refresh)
- [Lab: Aggregations]
- [Lab: Managing and Monitoring Premium Capacity]

## Other Power BI Labs
- [Using Artificial Intelligence and Power BI to Detect Picture Emotion](https://github.com/plebla372/labs/tree/master/Using%20Artificial%20Intelligence%20and%20Power%20BI%20to%20Detect%20Picture%20Emotion)
## Learning how to self-learn

Many of these topics are quite deep, and take time to fully absorb. There are several phases of learning:

 - Awareness (You learn a technology exists and what it is used for)
 - Understanding (You learn the components, processes and steps of a technology)
 - Practice (You can perform the steps with the technology by following a process to complete a task)
 - Mastery (You are able to explain the technology to others)


These courses are designed for you to repeat many times to move through these phases. Before you embark on any of these, you may want to complete a "Learning how to Learn" course. <a href="https://www.nytimes.com/2017/08/04/education/edlife/learning-how-to-learn-barbara-oakley.html" target="_blank">You can find more information on that here</a>. 

*Disclaimer*

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

### Download all Labs as a zip file

The entire repository can be [downloaded as a single ZIP file here](https://github.com/plebla372/labs/archive/master.zip). 


### Clone all Labs using git

You can [clone the entire respository using `git` here](https://github.com/plebla372/labs.git). 

### Get only one Lab
You can follow the steps below to clone individual files from a git repo using a git client. 

Example:

<pre>
git clone -n https://github.com/plebla372/labs
cd labs
git config core.sparsecheckout true
echo workshopname/*| out-file -append -encoding ascii .git/info/sparse-checkout
git checkout
</pre>

For more information about `sparse checkout please` visit [this](https://stackoverflow.com/questions/23289006/on-windows-git-error-sparse-checkout-leaves-no-entry-on-the-working-directory) stackoverflow thread.

### Code of Conduct
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

### License
These samples and templates are all licensed under the MIT license. See the LICENSE file in the root.

### Questions
Email questions to: sqlserversamples@microsoft.com.
