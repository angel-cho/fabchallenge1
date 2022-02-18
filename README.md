# Micro Challenge 1: Board Game for Collaboration

## A board game as a tool for collaboratively generating new ideas within and beyond the MDEF classroom.

### Ideation
We wanted to create a practical and fun tool to help designers ideate their next collaboration or project. We also wanted to derive themes and practices from traditional non-western indigenous cultures that are commonly undervalued as 'indigenous', 'mythical', or 'non-scientific'. The objective was to bring them into the design process as tools that enhance creative ideation. We started by sharing different belief systems, mythologies, indigenous practices, and visuals from each of our cultures. Through this exercise, we found many commonalities within our different cultural stories and designs. 

Preliminary sketches of the board game were made, and it was discovered that there were many different directions we could head in. I think we spent a major share of time discussing the concept behind the game and how the game would be played before we moved onto prototyping. We spent the first two days working out the concept and the form on paper. On the third day, after a discussion with Dafni, who encouraged us to start making test prints, we made a test on Illustrator which was transferred into Rhino.

![alt text](https://github.com/angel-cho/fabchallenge1/blob/main/images/alignment.jpg)
![alt text](https://github.com/angel-cho/fabchallenge1/blob/main/images/sketches.jpg)
![alt text](https://github.com/angel-cho/fabchallenge1/blob/main/images/patterns.jpg)
![alt text](https://github.com/angel-cho/fabchallenge1/blob/main/images/Sketch.png)


### Game Description
The game is composed of puzzle pieces with words inscribed on the opposite side. The game can be played by multiple people together. The fun starts with the drawing of the first card. As you pick the card you have to pitch an idea using the word or trigger underneath it in one or two sentences. After the pitch, the piece is docked in the center of the board. The next player that picks the card has to use the word/trigger from the previous card and the new card to pitch an idea. After the pitch, this component is docked onto the previous one. This goes on until the players feel convinced enough to stop the ideation. At the end of every game, you have a unique artifact turned from 2D to 3D built collectively by all players. This form gives rise to an opportunity to form connections, links, ideas and even circularity.

### Game Components
The 26 cards are divided into five categories of Machines, Triggers, Materials, Wisdom, and Crisis. The Machine and Material cards are self-explanatory while the Triggers, Wisdom and Crisis cards are an interesting addition. The Triggers contain keywords that are prominent amongst the MDEF students. The Wisdom cards constitute the cultural design practices that could help in shifting perspectives. The Crisis cards are almost like wild card entries that could change the trajectory of a design solution.

![alt text](https://github.com/angel-cho/fabchallenge1/blob/main/images/CADscreenshot.png)
![alt text](https://github.com/angel-cho/fabchallenge1/blob/main/images/FirstPrototype.jpg)


### Process
First, we prototyped a few of the individual “puzzle” pieces with different lengths and widths for the press and fit divots, since these were the parts that had to fit perfectly into one another. Even though we measured 0.1mm less than the width of the MDF board, we found the joints were still loose. From here, we went on to explore a few more pieces with varying widths, and discovered that the measurement we started with was correct. After introspection it was realized that the machine lens wasn’t focused during our first test.  

![alt text](https://github.com/angel-cho/fabchallenge1/blob/main/images/testpieces2.jpg)
![alt text](https://github.com/angel-cho/fabchallenge1/blob/main/images/testpieces1.jpg)

Using this knowledge, we moved forward to modeling the entire game on Rhino. We did this overnight and arrived early on Friday morning to use the laser cutter. Upon setting up the files to print, we immediately noticed a few issues. First, the length of the longest piece in our design was longer than the length of the laser cutter bed. This meant we had to either redesign the piece so it can exist in two parts, which would take time that we didn’t have, or resize all the components so they would fit on the board. Because of our lack of time, we decided to resize all of the components, which made the press-fit joints useless. The second issue was that the engraving on the MDF board turned out much lighter than we expected and was barely visible.
 
 ![alt text](https://github.com/angel-cho/fabchallenge1/blob/main/images/finalpieces.jpg)
 ![alt text](https://github.com/angel-cho/fabchallenge1/blob/main/images/EmptyBoard.jpg)
 
![alt text](https://github.com/angel-cho/fabchallenge1/blob/main/images/TiedBentoBox.jpg)
![alt text](https://github.com/angel-cho/fabchallenge1/blob/main/images/BentoBoxDetails.jpg)
![alt text](https://github.com/angel-cho/fabchallenge1/blob/main/images/BitAndShadows.jpg)



## Key Learnings: 
- Start prototyping early! Especially when working with machines and materials that are not familiar. 
- Test and leave room for error. The longer the buffer, the better.
- Always create laser cutting files with the size of the cutting bed in mind.
- Build parametric joineries with Grasshopper whenever thickness of material is involved. 
- We printed the text on one side of the MDF, then flipped them over to glue the patterned pieces on the back side. However, we neglected to flip the negative of the shape (the larger piece where the small shapes fit in) when we glued it onto the board and realized too late that the negatives were flipped and the shapes didn't fit into the board. 





