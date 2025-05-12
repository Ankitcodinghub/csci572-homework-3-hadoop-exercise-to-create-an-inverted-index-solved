# csci572-homework-3-hadoop-exercise-to-create-an-inverted-index-solved
**TO GET THIS SOLUTION VISIT:** [CSCI572 Homework 3-Hadoop Exercise to Create an Inverted Index Solved](https://www.ankitcodinghub.com/product/csci572-homework-3-hadoop-exercise-to-create-an-inverted-index-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91236&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI572 Homework 3-Hadoop Exercise to Create an Inverted Index Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Hadoop Exercise to Create an Inverted Index

• Creating an Inverted Index of words occurring in a set of web pages

</div>
</div>
<div class="layoutArea">
<div class="column">
Objectives:

• Get hands-on experience in GCP App Engine

</div>
</div>
<div class="layoutArea">
<div class="column">
We’ll be using a subset of 74 files from a total of 408 files (text extracted from HTML tags) derived from the Stanford WebBase project that is available here. It was obtained from a web crawl done in February 2007. It is one of the largest collections totaling more than 100 million web pages from more than 50,000 websites. This version has been cleaned for the purpose of this assignment.

These files will be placed in a bucket on your Google cloud storage and the Hadoop job will be instructed to read the input from this bucket.

1. Uploading the input data into the bucket

a. Get the data files from either of the links below http://www-scf.usc.edu/~csci572/2020Spring/hw3/DATA.zip

https://drive.google.com/drive/u/1/folders/1Z4KyalIuddPGVkIm6dUjkpD_FiXyNIcq

You may use your USC account to get access to the data from the Google Drive link. Compressed full data is around 1.1GB. Uncompressed, it is 3.12 GB of data for the files for this project. So on balance you should download the zipped file, not the folder.

<ol start="2">
<li>Unzip the contents. You will find two folders inside named ‘development’ and ‘full data’. Each of the folders contains the actual data (txt files). We suggest you use the development data initially while you are testing your code. Using the full data will take up to few minutes for each run of the Map-Reduce job and you may risk spending all your cloud credits while testing the code.</li>
<li>Click on ‘Dataproc’ in the left navigation menu under . Next, locate the address of the default Google cloud storage staging bucket for your cluster in the Figure 1 below. If you’ve previously disabled billing, you need to re-enable it before you can upload the data. Refer to the “Enable and Disable Billing account” section to see how to do this.</li>
</ol>
d.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: The default Cloud Storage bucket.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
e. Go to the storage section in the left navigation bar and select your cluster’s default bucket from the list of buckets. At the top you should see menu items UPLOAD FILES, UPLOAD FOLDER, CREATE FOLDER, etc (Figure 2). Click on the UPLOAD FOLDER button and upload the dev_data folder and full_data folder individually. This will take a while, but there will be a progress bar (Figure 3). You may not see this progress bar as soon as you start the upload but, it will show up eventually.

Figure 2: Cloud Storage Bucket.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 3: Progress of uploading

Inverted Index Implementation using Map-Reduce

Now that you have the cluster and the files in place, you need to write the actual code for the job. As of now, Google Cloud allows us to submit jobs via the UI, only if they are packaged as a jar file. The following steps are focused on submitting a job written in Java via the Cloud console UI.

Refer to the examples below and write a Map-Reduce job in java that creates an Inverted Index given a collection of text files. You can very easily tweak a word-count example to create an inverted index instead (Hint: Change the mapper to output word docID instead of word count and in the reducer use a HashMap).

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Here are some helpful examples of Map-Reduce Jobs

1. https://developer.yahoo.com/hadoop/tutorial/module4.html#wordcount

2. https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-

core/MapReduceTutorial.html

The example in the following pages explains a Hadoop word count implementation in detail. It takes one text file as input and returns the word count for every word in the file. Refer to the comments in the code for explanation.

The Mapper Class:

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
The Reducer Class:

</div>
</div>
<div class="layoutArea">
<div class="column">
Main Class

The input data is cleaned, that is all the \n\r s is removed but one or more \t might still be present (which needs to be handled). There will be punctuation and you are required to handle this in your code. Replace all the occurrences of special charactersandnumeralsbyspacecharacter,convertallthewordstothelowercase. The‘\t’separatesthekey(Document ID) from the value(Document). The input files are in a key value format as below:

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
DocumentID document

</div>
</div>
<div class="layoutArea">
<div class="column">
Sample document:

The mapper’s output is expected to be as follows:

The above example indicates that the word aspect occurred 1 time in the document with docID 5722018411 and economics 2 times.

The reducer takes this as input, aggregates the word counts using a Hashmap and creates the Inverted index. The format of the index is as follows.

word docID:count docID:count docID:count…

The above sample shows a portion of the inverted index created by the reducer.

To write the Hadoop java code you can use the VI or nano editors that come pre-installed on the master node. You can test your code on the cluster itself. Be sure to use the development data while testing the code. You are expected to write a simple Hadoop job. You can just tweak this example if you’d like, but make sure you understand it first.

Creating a jar for your code

Now that your code for the job is ready we’ll need to run it. The Google Cloud console requires us to upload a Map-Reduce job as a jar file. In the following example the Mapper and Reducer are in the same file called InvertedIndexJob.java.To create a jar for the Java class implemented please follow the instructions below. The following instructions were executed on the cluster’s master node on the Google Cloud.

1. Say your Java Job file is called InvertedIndex.java. Create a JAR as follows: ○ hadoopcom.sun.tools.javac.MainInvertedIndexJob.java

</div>
</div>
<div class="layoutArea">
<div class="column">
If you get the following Notes you can ignore them

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>          Note: InvertedIndexJob.java uses or overrides a deprecated API.
</pre>
Note: Recompile with -Xlint:deprecation for details. ○ jarcfinvertedindex.jarInvertedIndex*.class

Now you have a jar file for your job. You need to place this jar file in the default cloud bucket of your cluster. Just create a folder called JAR on your bucket and upload it to that folder. If you created your jar file on the cluster’s master node itself use the following commands to copy it to the JAR folder.

○ hadoopfs-copyFromLocal./invertedindex.jar

○ hadoopfs-cp./invertedindex.jargs://dataproc-69070…/JAR

The highlighted part is the default bucket of your cluster. It needs to be prepended by the gs:// to tell the Hadoop environment that it is a bucket and not a regular location on the filesystem.

Note: This is not the only way to package your code into a jar file. You can follow any method that will create a single jar file that can be uploaded to the Google cloud.

Submitting the Hadoop job to your cluster

As mentioned before, a job can be submitted in two ways.

<ol>
<li>From the console’s UI.</li>
<li>From the command line on the master node.
If you’d like to submit the job via the command line follow the instructions here https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-
</li>
</ol>
core/MapReduceTutorial.html

Follow the instructions below to submit a job to the cluster via the console’s UI.

1. Go to the “Jobs” section in the left navigation bar of the Dataproc page and click on “Submit job”.

Figure 4: Dataproc jobs section

2. Fill the job parameters as follows (see Figure 13 for reference): ○ Cluster: Select the cluster you created

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="layoutArea">
<div class="column">
<ul>
<li>○ &nbsp;Job Type: Hadoop</li>
<li>○ &nbsp;Jar File: Full path to the jar file you uploaded earlier to the Google storage bucket. Don’t forget
the gs://
</li>
<li>○ &nbsp;Main Class or jar: The name of the java class you wrote the mapper and reducer in.</li>
<li>○ &nbsp;Arguments: This takes two arguments
<ol>
<li>Input: Path to the input data you uploaded</li>
<li>Output: Path to the storage bucket followed by a new folder name. The folder is created
during execution. You will get an error if you give the name of an existing folder.
</li>
</ol>
</li>
<li>○ &nbsp;Leave the rest at their default settings
○
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 5: Job submission details

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
3. Submit Job. It will take quite a while. Please be patient. You can see the progress on the job’s status section.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 6: Job ID generated. Click it to view the status of the job.

NOTE: If you encounter a Java.lang.Interrupted exception you can safely ignore it.

Your submission will still execute.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 7: Job progress

<ol start="4">
<li>Once the job executes copy all the log entries that were generated to a text file called log.txt. You need to submit this log along with the java code. You need to do this only for the job you run on the full data. No need to submit the logs for the dev_data.</li>
<li>The output files will be stored in the output folder on the bucket. If you open this folder you’ll notice that the inverted index is in several segments.(Delete the _SUCCESS file in the folder before merging all the output files)</li>
</ol>
To merge the output files, run the following command in the master nodes command line(SSH) ○ hadoopfs-getmergegs://dataproc-69070458-bbe2-…/output

./output.txt

○ hadoopfs-copyFromLocal./output.txt

</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="section">
<div class="layoutArea">
<div class="column">
○ hadoopfs-cp./output.txtgs://dataproc-69070458-bbe2-…/output.txt The output.txt file in the bucket contains the full Inverted Index for all the files.

<ol>
<li>Sort your output.txt file using the command
<pre>           sort -o output_sorted.txt output.txt
</pre>
</li>
<li>Use grep to search for the words mentioned in the submissions section. Using grep is the</li>
</ol>
fastest way to get the entries associated with the words. For example to search for “string” use

grep -w ‘^string ’ output_sorted.txt

Note:-&gt; In the above grep command, the word to be searched should be followed by a tab character.

Part II: Inverted Index of Bigrams using Map-Reduce

Now that you are familiar with setting up and running Hadoop jobs on GCP, you will now modify your InvertedIndexJob.java script to generate an inverted index of bigrams (instead of unigrams).

Your existing Mapper class emits (word, docID) pairs which are then aggregated in the Reducer class. You will have to modify your Mapper class to emit (“word1 word2”, docID) pairs instead. The reducer remains unchanged.

Once you modify your class(es), create the jar invertedindex__bigrams.jar and dispatch a Hadoop job on the devdata/ in the same manner as before.

The output will look something like this:

To get credit for this task, create another text file index_bigrams.txt with the index entries for the following bigram phrases (generated from devdata/):

<ol>
<li>computer science</li>
<li>information retrieval</li>
<li>power politics</li>
<li>los angeles</li>
<li>bruce willis</li>
</ol>
You can apply grep on the output file in the same way you did for the previous exercises.

Submission Instructions:

Part I

<ol>
<li>Include all the code that you have written(java) and the log file created for the full data job submission.</li>
<li>Also include the inverted index file for the document “5722018484.txt</li>
<li>Create a text file named index.txt and include the index entries for the following words</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
a. architecture

</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="section">
<div class="layoutArea">
<div class="column">
b. technology c. temperature d. academics e. concurrent f. experiment g. catalogue h. hierarchy

Add the full line from the index including the word itself

<ol start="4">
<li>Also submit a screenshot of the output folder for the full data run in GCP.</li>
<li>Also submit Log file generated from running the job on the full data.</li>
<li>Do NOT submit your full index.</li>
<li>Compress your code and the text file into a single zip archive and name it index.zip. Use a
standard zip format and not zipx, rar, ace, etc.
</li>
</ol>
Part II

Submit this file index_bigrams.txt along with your modified java code (rename it as InvertedIndexBigrams.java) as part of the index.zip archive.

FAQ:

Q) Can’t seem to select a cluster for submitting a job? A) Changing the region will do the trick

Q) How many files were there in full_data while uploading? A) You need to upload .txt files only !!

Number of .txt files is 74.

Q) Chrome suffers, in uploading 74 files?

A) Consider opening the storage in another tab and checking the number of files. This way you will be able to know when the upload is complete.

Q) Do we have to use Java as the programming language?

A) Please go ahead and use any language binding of your choice.

Note : You may be on your own with language other than Java. TA’s may not be able to help with other languages.

Q) How to Import and Export Java Projects as JAR Files in Eclipse?

A) http://www.albany.edu/faculty/jmower/geog/gog692/ImportExportJARFiles.htm

Q) Is it fine to submit only one .Java file, which has the all the (Mapper and Reducer Classes) inside it ? A) One .java file containing your entire program should be good enough.

Q) Approximately how long does it take for a submitted job to finish in GCloud Dataproc? A) It takes approximately 10 minutes

Q) Should the postings list be in the sorted order of docIDs? A) No need to sort the listings.

</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="section">
<div class="layoutArea">
<div class="column">
Q) Google cloud is not allowing to ssh? A) You need to start VMs manually.

Q) Where can I find log files?

A) Cloud Dataproc -&gt; Under Jobs

Click on one of the jobs you ran.

Q) Should identical words in different case be treated as same or different words?

A) Different words, you need not pre-process or case fold.

Q) How to check number of files in full_data on storage bucket?

A) Go to your bucket, select the full_data folder and click on delete. It’ll list out the total files present. DO NOT PRESS DELETE in the dialog box that appears. Or run the following command from the hadoop cluster terminal:

Hadoop fs -find gs://…//full_data/*.txt | wc -l

You can perform certain sanity checks.

1) Check if your code run properly for the dev_data?

2) Check if you used correct space / tab specifications as mentioned in the assignment description, sometimes it might be the problem with the storage space related to that.

3) You can debug with a single custom file to see, if everything is properly indexed or not.

Q) Different index order. Should we take the same index order (sorted) or can it be different (unsorted)?

A) Order does not matter. The accuracy of results is important.

Q) Code runs fine on development but strange file size with full data.

A) Check if the results produced by running on dev_data produces huge file sizes as well. If so, that means you have to check your code. If not, check if your full_data is uploaded correctly.

Q) I’m getting this error repeatedly, but I’ve already created the output directory and have set the argument path to that directory. Can someone help me with it?

A) You need to delete the output folder because the driver will attempt to create the output folder based on the argument provided.

Q) Am able to run the dev_data and it is generating results. But if I ran the same code on the full data I am getting an error. The job is running for till map 25% and then it throws an error?

A) Please check that you have all the files uploaded just fine, and you should have 74 files in full_data.

Q) Starting VM instance failed

When I try to start the VM instances, for some of them it shows the message: Error: Quota “CPUS” exceeded: Limit 8.0?

A) If you get an error saying that you’ve exceeded your quota, reduce the number of worker nodes or choose a Machine Type(for master and worker) with fewer vCPUs.

</div>
</div>
<div class="layoutArea">
<div class="column">
11

</div>
</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="section">
<div class="layoutArea">
<div class="column">
Q) Did anyone run into a situation where if you go under Dataproc &gt; Clusters &gt; (name of cluster instance) &gt; VM instances &gt; SSH, the only available option is to use another SSH client?

A) You probably didn’t start the VM instances. Every time you disable billing and enable billing, you need to start VMs manually.

Q) Error enabling DataProc API

A) shut down project and create new one

Q) No space between DocID:count pairs in the output file after merge?

A) Happens due to copy-pasting the grep output from console to a text file. Pipe the grep output into a file and then download that file from gcloud

Q) “message” : “982699654446-compute@developer.gserviceaccount.com does not have storage.objects.get access to dataproc-60450493-bff5-4160-8156-fcb96702ebf0- us/full_data_new/32229287.txt.”,

“reason” : “forbidden”

A) If you’re using a custom service account, you still have to give reader access to the Default service account &lt;your-project-number&gt;-compute@developer.gserviceaccount.com

Important Points:

#P1) Output folder Number of parts generated – can be any number

#P2) Manually inspect output.txt and copy lines for the words from it and create a new txt file named index.txt. – for the 8 words

#P3) start worker nodes before submitting job to cluster

#P4) No Sysout – write in logs from reduce function

#P5) jar tvf jar_file_name – to list class files archived for a jar

#P6) space in your folder name which is treated as illegal character – throws error

#P7) Every time you disable billing and enable billing, you need to start VMs manually.

#P8) If you are not able to upload full data then add the data in parts. The main aim is to get all the files there.

#P9) Size of output folder for full data can vary.

#P10) When using “grep” command to search for keywords, look for exact match.

#P11) You just disable the billing account (when you’re not using it) as per mentioned in the HW description. There’s no need to disable the cluster, they’ll not charge you. Also, when you’ll disable the billing account; your master and worker threads will be disabled automatically.

#P12) You have to write a program that outputs the entire inverted index file and then using the grep command filter out the indices of the eight words given

</div>
</div>
<div class="layoutArea">
<div class="column">
12

</div>
</div>
</div>
</div>
