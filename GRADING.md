The final project should either be submitted as a zipped folder (file upload), or a link to a public github repository (text entry).  The directory structure should make sense, for example,

/README.md - describes the project at a high level, what each code file does, where I can find the project notebooks, and how to get the data, also add the group member names to the README

/code/ - directory with all python files, and other scripts that are not notebooks

/data/ - directory with data, do not add datasets over 100MB to the directory, we will transfer that data ourselves

/notebooks/ - directory with all the jupyter notebook writeups

 

GRADING

I will grade based on several criteria that are related to the lessons in the class...

1. Project organization, writeup readability, and overall conclusions (see lessons 1 and 2)

Does your directory structure make sense, are the scripts separated by function, is the writeup(s) readable, can I figure out where to look from your README.md?  Are your conclusions backed up by the facts/visualizations presented?

2. Code quality, readability, and efficiency (see lessons 3 and 4)

Is it easy to read the code, are the scripts modularized, are there docstrings, could I modify your code easily?

3. Scientific programming, custom algorithms, and numpy use (see lesson 5)

If you write custom data processing scripts are they efficient?  Do they use numpy to its full effect/vectorize when possible?  Do you use numpy to extract custom features/create network data/etc?

4. Data munging (see lesson 6, 7)

Do you use the munging tools in pandas well, such as filtering, joining, grouping, transforming?  How do you handle missingness and timestamps?  Do you use indices appropriately?  Do you extract custom features with pandas?

5. Data visualization (see lessons 9 and 10)

Do you make sensible visualizations?  Do they follow the principles of data integrity?  Do you explain the visualizations and give appropriate context?  Are your visualizations rich with aesthetic mappings?

6. Data extraction (see lessons 11 and 12)

Do you use a web API and parse the JSON?  Do you scrape and parse HTML?  Are there other structured formats that you work with such as text data?  Do you have to crawl a website with requests?

7. Data storage (see lesson 8)

Do you store your data in a relational database and interact through SQL queries?  Do you interact with your data in chunks and not read it all into memory first?

8. Interactive visualization

Do you use D3 or some other interactive data visualization tool to enable the exploration of the data.  Do you enable multiple views and filters of the data.

Grading method: Each category will be graded on a 1-10 scale.  I will drop the lowest 2 scores so that you can excel in some areas and get a good grade.

For example, you could scrape a website, which involves substantial data munging through pandas and the use of requests/beautifulsoup; you produce lots of data visualization and make an interactive visualization.  Your grades in (3 - numpy) and (7 - sql) could be dropped.
