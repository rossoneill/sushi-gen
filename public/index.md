# Sushi Card Generator

## Populating Content
Go to the command line in the **sushi-gen** folder and run *npm run fetch-content*.

## Creating Sushi Cards
1. Follow the steps outlined under **Populating Content** above.
2. Navigate to *public/sushi/* and follow the appropriate instructions:

### Creating a new series under an existing subject
1. Navigate into the folder for that subject and create a new folder named appropriately for your series. Good examples might be *intermediate* for mid-level content around that language in general or the name of a framework or tool if your work is specific to that tool. For example, I might create *sushi/python/flask* to write about the Flask framework for Python. Please use lowercase letters and separate words with **-** characters.
2. Inside the new folder, add a sub-folder for the language you will be writing in, using the appropriate ISO 369-1 two letter abbreviation chosen from [this list](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes).
3. Copy all the files from *sushi/example* and paste them into your series directory. Edit the *_data.json* file and update the **language** value in all entries to match the language your series is about.
4. Open one of the Markdown files in the folder and start editing!


### Translating an existing series to a new language

**TODO**

### Adding a new subject

**TODO**
