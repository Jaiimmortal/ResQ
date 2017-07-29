# ResQ

Analysis and cleaning of the June-2017 month's sale of [ResQ](http://resqtechnologies.in/) products data set used for notifying clients for renewal of their product after a year of purchase,  automated using Python.

***Data set hasn't been uploaded, becuase of security and privacy concerns***, but can view the dataset partially in the [IPython Notebook.](https://github.com/Jaiimmortal/resq/blob/master/resq.ipynb)

### Goals

1. To fetch the customer's Date of Purchase, Customer's name and their contact number and save them as a CSV file.
2. To check the saved CSV file (which will be merged with other month's csv) and if the Date of Purchase turns out to be year old, have to notify the admin via email, that these people have to renew their prodcuts today.

### Libraries used

  * [pandas]() - To extract the Date, Customer_name, Contact_number after cleaning and filtering the data set.
  * [smtp]() - To send email to the admin 
  * [datetime]() - for fetching today's date which is used to compare with the csv file, for posting renewal updates.
