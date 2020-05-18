## Assignment 14 - FINAL PROJECT Info
In the second iteration of this project, I'm trying to allow users to add new deals to the database.
To do this, I created a new sheet located at `@app.route("/add")
I got the form set up, and it's 90% operational, except I cannot for the life of me figure out how to
append the data I get from the web app to my .xlsx file. I've tried reading all of the pandas documentation,
multiple different websites, etc. It's a dumb problem, and I'm most of the way there, and after spending six
hours on this problem alone, I've decided to call it quits. I know that the smarter thing to do is to switch
to using a .json or .csv file instead of .xlsx. I'm pretty much there, the data is just being added to a new sheet
instead of the existing database. So for the time being I'm going to call this a "feature", where all of the new
entries are added to a new sheet so the administrator can review the entries before they're posted for all the 
world to see. This way, nobody can prank the website by adding fake deals in.  
So basically, I've finished the product, the functionality is just slightly different than what I intended,
but I think it works just as well.

## Assignment 13c Info

### I moved repos
I moved this project from my fork of MU-Software Engineering to this repo.

### Changed Goal
I've changed the goal of my app, because my last goal (display data from login) proved to be really
simple and boring. Displaying the data that SSO tracks would be trivial, and is basically already
done by the example app.  

### New Goal
Instead, I have a new goal. To display local food and drink prices (okay,
mainly just beer). What this means, is the app now displays drink deals, and by next week, will
allow users to add deals to the list. This took me quite a while to figure out, since I've never
done anything like this before, but it's looking pretty interesting so far!

## Running the App
Same as before,  
GOOGLE_CLIENT_ID=734280250142-hrm6r40r4002l4oc6augb6gg3hj4fcdg.apps.googleusercontent.com  
GOOGLE_CLIENT_SECRET=5mSP9__DRZL_LXVHheJsGgEZ  
`python app.py`
and it's up and running.

The "deals" section is located at "localhost:5000/deals"
The "add" section is located at "localhost:5000/add"

## Sources
https://sarahleejane.github.io/learning/python/2015/08/09/simple-tables-in-webapps-using-flask-and-pandas-with-python.html  
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_excel.html  
https://www.c-sharpcorner.com/article/create-python-flask-web-application-and-display-sql-records-in-browser/  
https://code.tutsplus.com/tutorials/creating-a-web-app-from-scratch-using-python-flask-and-mysql--cms-22972  
https://pythonspot.com/flask-web-app-with-python/  
https://www.freecodecamp.org/news/how-to-build-a-web-application-using-flask-and-deploy-it-to-the-cloud-3551c985e492/  
  
https://pythonspot.com/flask-web-forms/  
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.ExcelWriter.html#pandas.ExcelWriter  
https://stackoverflow.com/questions/47737220/append-dataframe-to-excel-with-pandas  
https://stackoverflow.com/questions/38074678/append-existing-excel-sheet-with-new-dataframe-using-python-pandas  
https://www.geeksforgeeks.org/different-ways-to-create-pandas-dataframe/  
https://stackoverflow.com/questions/38074678/append-existing-excel-sheet-with-new-dataframe-using-python-pandas  
http://www.datasciencemadesimple.com/get-maximum-value-column-python-pandas/  
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.ExcelWriter.html#pandas.ExcelWriter  
https://stackoverflow.com/questions/20219254/how-to-write-to-an-existing-excel-file-without-overwriting-data-using-pandas  
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.to_csv.html  
https://www.tutorialspoint.com/python_pandas/python_pandas_dataframe.htm  


