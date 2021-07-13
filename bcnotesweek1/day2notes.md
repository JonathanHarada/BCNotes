# Day 2 Notes

## Algorithm Loops and conditionals

A process that you do. Every piece of software isa  set of instructions.
### Algorithm steps
- Start
- Declare variables 1, 2, and sum
- step 3 Read values num1 and num2
- Add 1 and 2 and assign the result to sum. sum<nu1+num2
- Display sum
- Stop

### Algorithm examples
Step 1: Start
Step 2: Declare variables a,b and c.
Step 3: Read variables a,b and c.
Step 4: If a > b
If a > c
Display a is the largest number.
Else
Display c is the largest number.
Else
If b > c
Display b is the largest number.
Else
Display c is the greatest number.  
Step 5: Stop

### Conditionals 

- || mean (or)
- if blocks evaluate boolean expressions (true or falce)
- x > 0
- x >= 0
- answer === 42 (3 equal signs)
- string.contains("fuzzy") looking for the words fuzzy
- someArray.length > 4 true/false
- x > 10 && (means and) x v 20 - checks if x is between 10 and 20
- person.inClass() || person.isInstructor() - if this person is in class or an inst.

Console.log prints () in the console

## Price of admission for ABQ Zoo (How to plan in Pseudocode)
Need to get some info:
- Get customers age
- get membership status
- get nm residency status

   
    if membershipStatus or age <= 3 
      -price = 0
    else if age > 65
      -price = 4
    else if age > 13 
      -price = 3
    else if residencyStatus
      -price = 5

else
-price = 6
display price

## Variables
- at first use of a variable you must declare it with const, let, or var
- use const when possible and when the value will not need to be changed. 

const name = 'Bob'

- use let when you need to change a value

let age = 27

age = age +1

- use var when you want your code to not work

var planet = earth


## Loops
- blocks of code that are (possibly) executed multiple times
- while: keep doing this at least once, then keep doing this as long as true
- do...while: do this at least once, then keep going as long as true (avoid)
- for: special kind of while loop that uses special syntax to save lines of code (trying to do something n Number of times)
- foreach: do this once for each element in array or object

for(let i = 0; i < 16; i++) number/counter/how it's going to add

### Write an algorithm that runs from 1 to 20 when the number is even, out 'fizz'. When the number is divisible by 5, output 'buzz'. If it is neither even nor divisible by five, output 'foo'. 

- modulas gives the remainder of division

    
for (let i=1; i<=20; i=i+1)

    if i % 2 === 0 
      output 'fizz'
    if i % 5 === 0
      output 'buzz'
    else if i % 2 !== 0
      output 'foo'
    

### Given two number, write an algorithm that outputs the sum of all odd numbers between those numbers, inclusive. 

    get firstNumber
    get secondNumber
    
    if firstNumber > secondNumber
      largerNumber = firstNumber
      smallerNumber = secondNumber
      else
      largerNumber = secondNumber
      smallerNumer = firstNumber

    sum = 0

    for (i = smallerNumber; i > largerNumber; i++)

    if i % 2 !== 0 
      sum = sum + i

    output sum

# By next Tuesday: How are we going to introduce ourselves (elevator pitch) Write down. Specific to someone who hires web developers.

# UI/UX
- UI: the graphical and interactive parts of an application that a user interacts with directly
- UX: all aspects of an end-user's interactions with an application. 
- Example: Bootcamp

ddc-web-student is the User Interface

admission, lectures, projects, and graduation are all included in User Experience

most examples for apps will be more narrow

### focus on end user design (User-centered design)
- Pareto principle (80/20 rule) - 80% of the value of the site comes from 20% of it's functionality
- focus on what users want to do most
- this is called user-driven design

### Personas
user persona - an idealized user of the site
- the best persona to build first is the ideal user for the site
- all application have at least one key persona, most have several
- give them a personality, including: Name/technology/attitudes & needs/
- attitudes and needs: why are they using this site/what does this persona have that your application aims to fill/why choose your site over other options?


## Idealized Twitter User Persona
- Name: Mark Erikson
- Technology:

Devices 
* Iphone 12 running the latest version of IOS
* Macbook Pro running Apple Silicon with the latest Operating System

Proficiency: medium proficiency, is able to complete most tasks on a computer. 

Passion For Technology: Neutral

Attitudes and Needs:
* is an avid political junky who wants to keep up to date with the latest news and opinions related to national and local politics. 
* Mark is a huge John Roberts fan and wants to be able to follow him for immediate updates to the users tweets.
* Mark wants to be able to comment on tweets so that he can engage in "spirited debates" around policy. 

Frustrations:
* Being suspended for unknown reasons
* Bad faith arguments by people who oppose his beliefs. 
* Not being informed about major political events. 
* Fake news and bought followers. 
* Content not related to politics. 
* Slow loading times or un-interactive sites. 
* Lack of dark mode. 
* Auto-loading of new Tweets and being unable to find an old Tweet. 
* Auto-playing ads that are hard to stop or mute. 

Role: normal user. 

User Story: as a normal user I want to be able to follow my favorite politician. 

End user did something, the system responded!

Content creators: 
- Name: Fred Savage
Technology: Creates video game tutorials
  Devices:
  * PC
    * Windows
    * Cameras: Plugins
    
Proficiency: Highly proficient. Uses on a daily basis
Passion for Technology: Love hate. Likes really robust easy to use software for video editing

Attitudes and Needs:
* Archival and searching purpose
* Draw people in
* Quick uploads fast connection speeds
* Lots of subscribers 
* Make money

Frustrations: 
* You-tube search algorithm
* Censorship
* Pay algorithm
* Slow uploads
* Throttle speeds based on how popular you are
* Storage
* Bad comments/trolls
* Irrelevant videos suggestions
* Competing content creator invading comments
* Server goes down
* Dislike buttons

Role: Avid user/main source of income

Story: As an avid user I want to be able to make money 

* User interaction flow
* Content creator wants to go live during his demo
    * User clicks on log in content creator profile
    * User click button that says "go live"
    * User is given option to use camera, screen, or both
    * Chooses which option and is now live















