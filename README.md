# Language Learner
This app is great if you are learning a language, allowing you to quick and simply write down words in the langauge you are learning along with the translation.
You can apply colours and filters to your words to easily keep them organised. If you are looking for a specific word you can simply search for it.
Having multiple windows open at a time alows you to modify different files and group words based on context.

I have developed this application to help me with my leanguage learning journey. I required some where to write down words I had searched up while learning german.
This app has substantially improved my understanding of OOP and tkinter. I have learnet how to manipulate json file structures within python and the kind of 
features needed to have a positive user experience (UX).

## Table of Contents
- [Downloading / Installing](#download-and-run)
- [First time running](#opening-for-the-first-time)
- [Using the app:](#navigating-the-main-window)
  - [Add words](#adding-new-words)
  - [Remove words](#deleting-a-word)
  - [Change highlight colour](#changing-highlight-colour)
- [Filters](#filters)
- [File management](#creating-and-opening-files)
- [Settings](#changing-settings)



## Download and run
Simply download the application file under the lastet release. Please note, support currently is MacOS only.

I have not published the source code at this time.

# Functionallity and features
Many features of this app are still in working progress and may have bugs.

## Opening for the first time
When launching the application for the first time it will automatically create a folder within you user directory. This is where you last opend file path will be stored.
The program will then prompt you to select where you would like to save a file and what you would like to call it. This json file will store all your words and app settings.

<img width="912" height="588" alt="Screenshot 2026-06-09 at 11 33 51 am" src="https://github.com/user-attachments/assets/3aea5501-1d1f-4313-9ea1-079064d3d0c9" />

Press save once you have fond a location and given your file a name.

The window will now load and should look something like this:

<img width="775" height="631" alt="Screenshot 2026-06-09 at 11 34 42 am" src="https://github.com/user-attachments/assets/89f4cc5c-29dd-4f33-bdc2-ad3bdb34e63c" />

## Navigating the main window
The main window is where all your saved words are displayed. You can have as many of these open as you want by pressing Command + Shift + N or by going: File --> Open In New Window.

The currently open file is shown along the top of the application within its title.

#### Here you can:
- Add new words
- Modify saved words
- Apply highlighting effects
- Apply filters
- Search for words saved
- Delete words

### Adding new words
At the bottom of the screen you can see 2 entry fileds and a button labled "Create". To add a new word to the file, simply type in one box the word and the
other, type the translated version.

When you are ready either press create or hit return to add the word to your list.

<img width="775" height="631" alt="Screenshot 2026-06-09 at 11 48 05 am" src="https://github.com/user-attachments/assets/15663ee4-8f0a-472b-812c-a24c9bdef22a" />


### Deleting a word
When creating a new file, example widgets are automatically put in. To delete them you can simply select using the left mouse button and then press the delete key.

When selecting a word, you will notes all highlighting is removed and all items you have selected are coloured red.

<img width="775" height="631" alt="Screenshot 2026-06-09 at 11 43 39 am" src="https://github.com/user-attachments/assets/f229ac2b-d05d-4285-84e0-760647442f10" />


### Changing highlight colour
To change the highlishted colour of a word or words, simply select with the left mouse button which words you would like to modify. Then either press one of the shortcut keys or go to the menu bar along the top of your screen and select a colour under highlight.

#### Short cut keys:
- Command + R (Red)
- Command + G (Green)
- Command + B (Blue)
- Command + Y (Yellow)
- Command + Shift + R (Remove highlight)

<img width="775" height="631" alt="Screenshot 2026-06-09 at 11 55 32 am" src="https://github.com/user-attachments/assets/bf8b21f8-178e-479b-a95a-783bf4083f1d" />

### Copy / Paste / Undo
To copy / paste simply select the word or words you would like to copy, then either press Command + v or right click on a word and press paste.
The selected words will now be pasted at the bottom of the list.

To undo an action, E.g. Undo highlighting, uncopy or undelete, simply press Command + z or go: Edit --> Undo.

## Filters
To remove a filter of any kind simply go: Filter --> Reset.

This option will change to inform you wether or not you have any filters applyed.

If you want to save your applayed filters to a new file, simply press Command + S or go to: File --> Save As...

### Start / End letter filters
You can filter words by start letter or end letter. Simply go: Filters --> Starts With... / Ends With...

A dialog should apear where you enter the starting / ending letter you would like to look for.
The main window will update displaying only the words stored that match your filter.

### Organise alphabetically
The program can automatically organise your saved words alphabetically. This can either be by the first word or the second word.
The options automatically change to show the label you have given each word. 

### Search
To search for a word, simply go: Filters --> Search.

A dialog box will apear where you can enter a word and then press "Ok" to search. Now all words which do not contain your entered search will be hidden from the main window.

### Grouping
To group items simply select the items you want to group and then go: Filters --> Group

All items you did not select will now be hidden from view.

## Creating and opening files
Under the file menu within the top menu bar, you can find options to do with file managment.

### Some of the options include:
- Opening a file
- Creating a new file
- Saving the current file as
- Deleting the current file + opening a different one

## Changing settings
To open settings press ether Command + , or go to: languageLearner --> Settings...

Within this window you can change how the app functions. After making a change, you will pe prompted to restart the app to allow the changes to take effect.
You can press cancel and the changes will not be applyed untill you menually restart the app.

### General Tab
Currently auto text scalling is not finished and so it is grayed out.

#### Here you can customise:
- Word entry box lables
- Wether window postion is remembered or not on restart
- Auto scalling of text as the window size changes

<img width="479" height="274" alt="Screenshot 2026-06-09 at 1 25 55 pm" src="https://github.com/user-attachments/assets/5b65644d-7ea0-4464-8a69-57ae396f576a" />
<img width="775" height="631" alt="Screenshot 2026-06-09 at 1 37 13 pm" src="https://github.com/user-attachments/assets/ecdb65a9-e513-4fef-a116-ec92b487434d" />

### Style Tab
Here you can customise the text size and theme of the application.

The recomended text size is between 15 and 20. However, if using in full screen you might what it larger.

Currently themes is not supported. 

<img width="375" height="314" alt="Screenshot 2026-06-09 at 1 35 40 pm" src="https://github.com/user-attachments/assets/2fc91a7e-7fdd-4460-8c98-997427c831cd" />



