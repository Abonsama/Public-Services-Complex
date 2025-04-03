# public services complex
this is a solution to the unorganized and chaotic public services in sudan.
here i made it on the web.
you can make all you need with this web portal with ease.
## overview
this project can reflect how to solve a serious problem in life only with going online using available tech solution.
the idea is to make the data gathering of people easy for both goverment and individuals(who are authorized) and that solves many problems in counting, predicting or even planning skiping a lot of steps of checking the reliablitiy of the data

## building plan
- first step is the user research(which is skipped here because this is a demo)
- wireframing and prototyping
- making the block diagram to know what are the functionality needed
- implemeting the functionality using typeScript on nextJs for front end and python on Django for backEnd(if needed)
- styling using tailwind css
- refactoring
### pages or services involved
- id related services page
- drivers license page
- car registration page

### id page
#### id rules
this page has the new registration and the updatess based on the following;
- if its for a newBorn baby the id color will be slightly green and has all the details recorded on a QR code except the main data like the full name, mother name, date of birth and the id code.
- for the education age individuals the color will be slightly red and has all the details recorded on a QR code except the main data like the full name, grade and education level, age and id code.
- for post educaton levels the color will be white and has all the details recorded on a QR code except the main data like full name, age, type of employment or business, and id code.
- for the retired individuals the color will be slightly gray and has all the details recorded on a QR code except the main data like full name, age, address, specific needs or health issues(if exist) and id code.
**note that when id is issued, it may never get changed under normal circumstances
all the id cards has a photo on them with the owner's name
each card has a small serial number on them which is unique for every card and never get used on another card for identification of cards
when a card gets lost or damaged, it get replaced with a new one and the old one will be stopped

#### id page contents
four buttons for each type of of ids
some banars and paragraphs for more informations or updates