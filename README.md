<h1>Part-of-speech Dataset annotator</h1>


<h2>Description</h2>
A mobile for annotating Part-of-speech (POS) datasets. The application uses a web API to fetch the sentences from a database hosted in the cloud. A logged-in annotator is presented with a drop-down list of tag options for a selected word. The tag and word pair are stored in the database alongside their sentence ID. Using the application, Chichewa experts do the annotation process(more than one annotator annotates each sentence); this means that each word has multiple tags; we apply the Boyer-Moore majority voting method to determine the final tag of the word. The voting process replaces the process of verification and validation, which requires a lot of resources. We used this application we annotated 65,787 words into 17 classes.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Dart</b> 
- <b>Flutter</b>
-<b>PHP</b>
-<b>Mysql</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Home screen for annotators: <br/>
<img src="https://github.com/ndebvu/Part-of-speech-dataset-collector/blob/main/Interface_landing%20(1).png" height="50%" width="40%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select word to tag:  <br/>
<img src="https://github.com/ndebvu/Part-of-speech-dataset-collector/blob/main/Interface_selected.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
