# UiPath-Challenge for TKS

This project use UIPath for to acess gmail provider and create a XLS file .

## Installation

It is necessary to have the UiPath Studio. If you do not have, use this link (https://www.uipath.com/).

This project has three activities : AnswerMail.xaml, PDFtoCSV.xaml, ReadMailGetAttachment.xaml. In the next chapter, i will explain each one

### 1. ReadMailGetAttachment

This activity is responsible to enter a gmail account, to search specific mail, and to download the attachment.
Before to run this activity is necessary to configure our variables:

```javascript 
email_google //variable for the gmail account 
password_google //variable for the password of the above gmail account
subject_email //variable for search for the  email
```

### 2. PDFtoCSV.xaml

This activity is responsible to create the CSV file according to PDF in the first activity

```javascript 
path_file_pdf //variable for path that contains pdf file 
output_path //variable for path that will generate csv file
```

### 3. PDFtoCSV.xaml

This activity is responsible to create the CSV file according to PDF in the first activity

```javascript 
email_google //variable for the gmail account 
password_google //variable for the password of the above gmail account
subject_email //variable for search for the  email
path_attachment // variable for the path of CSV file
name_attachment // variable for the name of CSV file
body_mail // variable for the body of mail that will send
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
