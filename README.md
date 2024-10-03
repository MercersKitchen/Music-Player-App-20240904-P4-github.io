# Music-Player-App-20240904-P4-github.io
2024-2025 Development

Progressions
- [x] Practice creating and deleting repositories ( REMEMVER: github.io for hosting )
- [ ] Case Study: what does a music player interface look like with most of the buttons present
    - Demo: What would my buttons look like
    - Demo: where does my information go
    - Review video: https://www.youtube.com/watch?v=JMjozqJS44M
    - List of Buttons & Information (See DIVs), leads to prototyping buttons as a void (variable inputs comes from DIVs), purpose is working with size()-CANVAS
    - Image of Text, Images, and buttons: 100% activity, leads to paper folding activity ("Draw my pointillism"), purpose is developing mini-CANVAS's
    - List of Data: music MP4's, associated images, purpose is now where these images go
        - Review how to find information, know what is available
        - NOTE: Computers can see NULL and give information to user as a Try-Catch (CS30)
    - Final Case Studies "Booklet", purpose is sequence of images for website promotion answering who I am as a developer
        - "Where do I put the buttons", name separate images, upload to GitHub for reference and Website Hosting
        - Splash Screen & Welcome with App Name, Music Playlist as Enter and AutoPlay Button, Preferences (in CS20 to be saved as Write-Read File, DIVs as preference buttons to change formats),
         Uses APIs in 20
        - AutoPlay Screen, one playList starts playing with minimalist interface (user defines minimalist and purpose of whitespace), 2 click to anything rule
            - NOTE: lower half of "One Screen" as a teaching tool, activate lines to see symmetry (1/2, 1/4, etc if necessary)
            - 10 Seconds: Stop - Previous - Loop ONCE - Next
            - Middle of Song: Stop - Reverse (Previous is double click) - Pause - Forward - Loop ONCE - Next
            - Last 20%: Stop - Previous - Reverse - Replay - Loop ONCE - Next
            - Always on, MUTE & QUIT ( how to read a display, actually reading anything, then ID where important stuff is in "T", 
              like a seating plan in a classroom)
            - "Upper Half of "One Screen: my teaching screen, using images (easier not as valuable in learning)
        - Play List Screen, Buttons to interact with playlist like Loop-Play-List (this button can be included on previous), drag and drop, refresh
        - Single Song Screen, Buttons for single song, metadata information
    - Final Case vs. Remedial: students must demonstrate design of use, are buttons always on, how is screen spaces active or not
    - Remedial Splash Screen: single Boolean of entire screen, active the WINDOW in WINDOWS for Key Pressing (not mouse-pressing), OS Level hack
    - Due Dates: the day I teach it is the day it is due and must be done for HW (will be checked online or in person), must send email if missed

- [ ] Buliding Basic Prototype for functionality
    - Add minim library
    - Introduce Arrays for Music Songs Only, Array List Out of Bounds, Try-Catch, Index
    - Loading Music
    - size() only
    - keyboard for music buttons only
    - [ ] Paper Folding Ratios
        - two pieces of paper
        - Estimate a dot in the center
        - Paperfold the center: two 1/2 folds perpendicular (like two perpendicular diameters)
        - did you make it
        - Repeat the same paperfold and backfold
        - Rip a 1/4 area, notice the width and height are 1/4 (A=lw)
        - Put dots on both pieces of paper ... this is where the computer starts counting
        - The "display" center is where the rect(X,Y) is
        - How would this change if both squares looked like they were both centered on the paper
        - What would I have to minus
        - Note:
            - In code appWidth and appHeight might be used for the general musicButtonWidth and musicButtonHeight
            - musicButtonX&Y should use the smaller of the two dimensions for a square (subset of rectangles) optically in the center
            - CAUTION: rectMode does allow for this introduces formulaic exercises
            - Notice: the music button doesn't know how big it is, it has no numbers. It knows how big the display is
            - Foreshawdowing: the computer will calculate how many buttons it needs and then calcualte the width-height

- Features of Basic Prototyping Build
    - [ ] Repository Folder Strucuture and Pathway - Directory Organization
    - [ ] Music Load | Drag and Drop Feature (Advanced, CS20)
    - [ ] Introduce Key-variables for size() | width&height becoming INTs for appWidth & appHeight (key variables should not be used in manipulation)
    - [ ] First DIV for basic muusic button, using debugger to ID strongly coded float variable (or double)
    - [ ] Introduce Algorithm for Display Geometry being repeated in DIV
    - [ ] Introduce Algorithm for Drawing Square in Rectangular DIV
    - IF-Then between landsape-square | portrait (hardcoded)
        - Smaller side
        - Repeat for other side
        - X&Y Variables from from DIV
        - Width & Height come from smaller dimension
        - Verify by visually checking

- [ ] STOP Button: outline, fill, gray scale, colour (day, dark, & night mode), new Variable Boolean (small memeory between VOIDs)
    - Code sections to Music App
    - Introduce COLOR Algorithms using Global Variable Boolean
    - Key Bind all COLOR Boolean Variables as 3 keys, then only one key with counter variable
    - Introduce Truth Tables to explore Boolean Controls
    - Introduce Mouse Press Algothrithm (listener and any time in draw(), finish draw, then continue draw)

- [ ] Buttons in Prototyping, exploring 2D Shapes and Features of 2D Shapes
    - Stop: creates the symmetry of all buttons
    - Play | AutoPlay
    - Pause
    - Fast Forward | includes Pause ? | Note: set time skip as seconds or percentage of song
    - Fast Reverse 
    - Next 
    - Previous
    - Loop, single song: once (1), infinite (sideways 8), set number of times (other number)
    - Loop PlayList
    - Shuffle (Cross with triangle ends)
    - Mute (speakers only)
    - Quit Button | Shape and Text | Sound Effect | "Are you Sure" Menu Reminder
 - [ ] See images for reference, based on 1/4 folds, very effective for students, all buttons within space for STOP, some buttons are student designed
    - teach rect() for rectangle & square, ellipse() for inscribed circle, line() for diagonal lines
    - teach 2D Shape Fill and Modifiers like stroke(), caps on lines, noStroke(), etc.
    - teach hoverover: gray scale, colour ( day, dark, night modes )
- [ ] Prototype will play song, button and key board short cut will add simple interaction
    - CAUTION: not autoplay
    - Only simple one song play at execution, then simple stop because file is at the end
 - [ ] Separate Buttons to build (Uses varaibles of DIVs)

- [ ] Case Study: algorithms of music button features

- [ ] Case Study: music player app, one screen or mulitple screens

- [ ] Music App
    - Display appWidth&Height
    - Display full screen (displayWidth, displayHeight)
    - Music Load
    - DIVs of one-screen | multile screens (include all DIVs, visually verifiy, then use only varaibles)
    - 



...

- [ ] Case Study: what do music buttons look like? Different Styles? Different Functions?
    - Introduce DIVs as lines to view symmetry (1/2, 1/4, etc if necessary)
    - Hover-over changes outline and shape colour
    - Booleans change Day, Dark, and Night Modes ( advanced: preferences CANVAS, otherwise CONSOLE accessed)
    - Math formulae about geometry (screen and shapes)
    - Remedial: Download one "square" play button image for tint() hover-over, who struggles with formulae and variable-cascading, leads to passing parameters

- [ ] Prototype: individual buttons on CANVAS and through CONSOLE, one sound effect and one song

- [ ] Buttons
- [ ] CANVAS vs. CONSOLE

---

### Reviewing Minim Documentation
- Prototyping on KeyPressed, CANVAS, CONSOLE

DIVs: paper folding on different sized papers with ratios, draw after me in pointillism
- Introduce Primitive Variables: int v long, float v double, string v char
- CAUTION: one song only
- CAUTION: Single DIV only


- [ ] Information
   - Display Song File, Name, Progess, Total Time, Other strings inside MetaData
   - Song Number in Play List
- [ ] Image

Prototyping Buttons: CANVAS, no mousePressed yet

Prototyping Buttons: Algorithms & CONSOLE
- Based on Song Playing: first 10 seconds, middle, last 20%

Building QUIT Button
- exit()
- double rect()
- hoverover features
- Play Button for Sound Effect, trimmed for effect

Assembling Music Player
- Require DIVs | All prototyped buttons basedon on DIVs, padding, square in DIV
- DIVs built on ratio of CANVAS to auto dimenstion DIVs
- AutoPlay
- Other Buttons

Advanced
- Button as an Image - Second Level of Music Player
- Reading Folder Files, Drag and Drop
- Playlist sorted according to most played song, decreasing in order, able to set in preference

---

# To Include

---

# Stories - Also See HardDrive
- My example demos how I reduce bugs through routine and input habits, may need words to ID, some can simply repeat patterns (data sets in teaching math or abstract ideas)
- Setting up computer station every class, time decreases to less than a minute, balanced with garbage, searing plans
    - Not North American way about computer stations, more youth way on legs, laying on floor, etc. not ergonomic 
    - Story of Hardware Guy trying to learn to buy groceries, outperforming AP Students on CISCO Exam ... we need people like this
- Everyone gets to demonstrating AP-Level coding project, exam and amount of information is separate issue
- Creating GitHub Repos: 100% activity, an exam or quiz is only going to assess who doesn't know,
it needs to be practiced, do it 10 times, then start assessing who knows
- Final Case Studies "Booklet": IDs students able to think in multiple variables mathematically or artistically and demonstrate, 
out is students who download "square" music buttons to be used with tint() (see Drawing Program, MEd student and Artist)
- ID those capable, ID those coachable, ID those who struggle and work with deeper issues (can someone every deal with this level of understanding a student)
- How does the use of remedial cases work guiding students to OOP, encouragement always, as a student I was discouraged ( how I give back ), I now understand
this as a person anxious or avoidant and how they pass on themselves to other generations
- COVID drastically interrupted all remedial work for complicated and complex reasons
- Becomes different class lists in a clipboard, marks transferred to Gradebook when needed
- Math Formulae about Geometry: in math geometry is about shapes and relationships about dimensions
(i.e. collisions and radii searching), geometry is also a computer term about a display (i.e. width and height), these do not match, reminds me the
divide between the Bools, Mary and Her Husband as interpreted by the people after them
- A display is an embodied metaphor, you can touch it. Concrete needs to be explored before abstract Objects in OOP

---

- DIVs, rect(), and parent interview (student apologized in grade 12)
    - What is current state of missed HW, assessment, redo's, and make-up grades
    - How can parents help vs. confronting teachers
    - student is one who knows and has responsibility, send email, help son-daughter send email

--- 

Paper folding basic music buttons - incredible activity
- takes two days
- demonstrates padding and symmetry 
- demonstrates paper folding to 1/4
- abstract to any fraction or percent (100 folds in an axis)

Students need to practice paper folding to know how to compare sides 

Students need to repetition to even learn this style of paper folding 

Visual students are repeating the Google Prorotyping video to visualize what they want to happen

---

