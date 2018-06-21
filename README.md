# scraping-justdial.com

I have done coding in python3 so all issues which were there in the code of python2 are not here,
Just enter the url and it'll extract business info from it .

Enter the url from which you want to extract information and save it in the 'url' variable ex:
url="http://www.justdial.com/Bangalore/Car-Repair-Services/ct-23150/page-%s" % (page_number)

change the name of the csv file to be generated to be an appropriate one ex:
out_file = open('car_services_bangalore.csv','w')

Run the file : python ./scraping-justdial.py

You will see the results in CSV as well as on the terminal.
Thanks !!!
