In this project, let's build a Feedback App by applying the concepts we have learned till now.

Refer to the image below:

![image](https://github.com/bukka5sandhya/Feedback-App-React-js/assets/133884532/05533408-40cf-48b4-a7f9-78c66b42c967)

https://assets.ccbp.in/frontend/content/react-js/feedback-app-output-v2.gif

Design Files

Click to view

Extra Small (Size < 576px) and Small (Size >= 576px)

Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Feedback Question

Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Thank You Screen

Set Up Instructions

Click to view

Download dependencies by running npm install

Start up the app using npm start

Completion Instructions

Functionality to be added

The app must have the following functionalities

When an emoji is clicked, then the thank you screen should be displayed

The Feedback component receives the resources as a prop. It consists of the following properties

Key	Data Type

emojis	Array <object>

loveEmojiUrl	String

emojis consists of list of emoji objects with the following properties in each emoji object

Key	Data Type

id	Number

name	String

imageUrl	String

Implementation Files

Use these files to complete the implementation:

src/components/Feedback/index.js

src/components/Feedback/index.css

Important Note

Click to view

The following instructions are required for the tests to pass

The love emoji should have the alt as love emoji

The emojis should have the alt equal to name value in each emoji object
Colors

Hex: #ffeeee

Hex: #ffc0bb

Hex: #ffebeb

Hex: #ffffff

Hex: #0f172a

Hex: #1e293b

Font-families

Roboto

Things to Keep in Mind

All components you implement should go in the src/components directory.

Don't change the component folder names as those are the files being imported into the tests.

Do not remove the pre-filled code

Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets
