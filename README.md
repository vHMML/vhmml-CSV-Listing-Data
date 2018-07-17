# vHMML Data Portal and JSON

[vHMML Data Portal](https://www.vhmml.org/dataPortal) makes it possible for you to create a custom dataset for personal research or for digital humanities projects. Choose your own search criteria and then focus your search results using the same tools as in [vHMML Reading Room](https://www.vhmml.org/readingRoom/).

vHMML Data Portal also provides users with the option of exporting curated datasets or the complete vHMML Reading Room dataset. Datasets are downloadable in JSON format, which provides the widest range of options for repurposing vHMML metadata for your projects.

We have placed a [full metadata schema](https://www.vhmml.org/dataPortal/schema) for the data in vHMML Reading Room on the main landing pager of the Data Portal, or you can [download the data schema via a Google sheet](https://bit.ly/vHMMLSchema). 

HMML has uploaded sample digital humanities projects using metadata from vHMML Reading Room on its digital humanities resource site [vHMML DH](https://www.vhmmldh.org/).

# Downloading Metadata From vHMML Data Portal

One of the tools you can utilize to work with your vHMML JSON datasets, is this Python script to convert your downloaded JSON Listing data into a CSV file.

Don’t know Python? Don’t worry, you don’t have to! The nice thing about Python is that it is already installed on a Mac. But, if you don’t have a Mac, you can use a service like [Pythonanywhere](https://www.pythonanywhere.com) to run the program instead. 

To start, perform your search in the Data Portal.

<<image>>
  
Click the Export Results Table button to download your data.

<<image>>
  
Say yes to download.

<<image>>

# Using Python on a MAC

Download the Python script you’ll need (https://github.com/vHMML/vhmml-CSV-Listing-Data)

Open a terminal (via Launchpad, Other folder) and navigate to the directory with both files.

This is typically a “cd” command to “change directory”.

Once in the directory that contains both files, type “python” (to run python), then the python script file name, then the json file name. Then hit enter. For example:

Then you can open your CSV

Note that you should read the open in CSV to EXCEL guide to understand unicode and Excel.

# Using Python on a PC: PythonAnywhere

If you don’t have a Mac, or want to run your Python script in the cloud, you can use PythonAnywhere.

First create an account at pythonanywhere.

![alt text](https://github.com/vHMML/vhmml-CSV-Listing-Data/blob/master/img/pa_create_account.PNG "Create account")

Then Login. From the Dashboard click FILES in the upper right and create a “vhmml” directory (yellow input box).

![alt text](https://github.com/vHMML/vhmml-CSV-Listing-Data/blob/master/img/pa_files_new_dir.PNG "New Directory")

Change to the new vhmml directory and click the yellow “Upload a file” button to upload the Python script.

![alt text](https://github.com/vHMML/vhmml-CSV-Listing-Data/blob/master/img/pa_upload_file.PNG "Upload file")

From here you can upload the Python script you downloaded from Github (https://github.com/vHMML/vhmml-CSV-Listing-Data)

Or, you can instead clone the Python script. From the bash command line run: git clone https://github.com/vHMML/vhmml-CSV-Listing-Data.git 

![alt text](https://github.com/vHMML/vhmml-CSV-Listing-Data/blob/master/img/pa_git_clone.PNG "Git Clone")

This will close the GitHub repository from vHMML onto your PythonAnywhere account.

Then click the yellow “Upload a file” button to upload your vHMML downloaded dataset.

![alt text](https://github.com/vHMML/vhmml-CSV-Listing-Data/blob/master/img/pa_upload_python_file.PNG "Upload")

This should be what your PythonAnywhere will look like. The Dataset JSON and Python program in the same folder.

![alt text](https://github.com/vHMML/vhmml-CSV-Listing-Data/blob/master/img/pa_files_uploaded_open_bash.PNG "Files uploaded")

From here, click the “Open Bash console here” link. This will open something that looks and acts like terminal.

![alt text](https://github.com/vHMML/vhmml-CSV-Listing-Data/blob/master/img/pa_bash_run_program.PNG "Bash Command line")

You can run “ls” to “list” your files. Or run the program with “python vhmmlCSVfromListingData.py XXXXX.json”

After the file has been converted, click the hamburger menu and choose Files.

![alt text](https://github.com/vHMML/vhmml-CSV-Listing-Data/blob/master/img/pa_view_files.PNG "Files menu")
![alt text](https://github.com/vHMML/vhmml-CSV-Listing-Data/blob/master/img/pa_files_nav_dir.PNG "Navigate files")

Navigate to your files, and download your new CSV file using the download icon.

![alt text](https://github.com/vHMML/vhmml-CSV-Listing-Data/blob/master/img/pa_files_download_csv.PNG "Download CSV")

# Open in Excel.

Note that you should read the open in CSV to EXCEL guide to understand unicode and Excel.

![alt text](https://github.com/vHMML/vhmml-CSV-Listing-Data/blob/master/img/pa_view_excel.PNG "View Excel")
