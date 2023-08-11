# Mini Tank RC with LED Panel
Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Tamim K | HS Of Telecommunication Arts & Technology| Computer Science | Incoming Senior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/FY0wbPKkW5g" title="Tamim K. Milestone 3" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my third milestone, I worked on getting the LED panel to work with the IR remote to display patterns once a button is clicked. I managed to accomplish this challenge by using the LED panel test code given in the documentation and tweaking it for my needs with the RC Tank and I had added more statements alongside new long variables to store the hexadecimal input from the IR remote and another variable to store the pattern with them being used in if statements for when a certain button is clicked. Throughout all this succeeded I have faced challenges and succeeded in which one of these challenges would have to be the ir reciever wire being incorrectly for the solution to be that I had to take it out. flip it and then place it back. Another would have to be the long data type as it was foreign to me as, from my prior experience, there wasn't a huge focus on how huge the number should be and, since these remote IR inputs are in hexadecimal, which are huge numbers, using the regular `int` wouldn't work. Throughout all this I got to learn what it was like to be an engineer assembling with some parts having to be put together in a way I didn't expect, like the tank treads needing more force than I expected on the software side, in which I learned another part of programming was prior to coming to bluestamp the only experience I have is with web development and programming between that and working with the arudino is different as shown from what I had said before with the data type but I am happy that I got to learn that as there might be a time where I'll have to learn C++ and learning the arduino which is based off the C++ syntax helps. For the future, I hope I can apply many of these things to other ventures and I hope to learn more of what I'm passionate about as I am to go outside of what I am familar with and I left off with stuff I enjoyed about it familiar which was the software aspect which I want to further myself in. 



# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/st0iSvO6ZFY" title="Tamim K. Milestone 2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my second milestone, I worked on using the IR remote that the kit came with and having it control where the tank goes. I managed to accomplish this by programming it in which I looked at the examples that were given from the documentation which shows how the motors go and it also provided the hexadecimal for the inputs on the remote. With those inputs, I saved them into a variable and made if statements for if this button was pressed it would go this certain way. What was surprising to me is that there was a data type that I wasn't aware of which I had to use for the inputs which were long as it is for hexadecimal as those are huge numbers to store. Besides that, another challenge I had to deal with was with my motor screw being loose with one of the wheels but I managed to get that fixed just fine as it seemed that I didn't do it correctly while assembling it. For my next milestone, I hope to work with the LED panel and also have that respond to inputs just like the motors.
# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/6IOL5gxTMwA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my first milestone, I worked on assembling the parts and verifying that uploading code works fine for when I do work on modifications later. With the tank being built with motors and boards like the Arduino and keeping them all together with screws and bolts assembling the tank itself was easy but it did take some time. One of the reasons why it took some time would have been like the tank treads which were shown on the assembly video from the company to be easy to put on but for me, it took some force to put it on. Outside of that issue, I managed to assemble it just fine and I verified that I can upload code by testing the example code for the led and motor control project to see if they would work and they did. For my next steps, I hope to use the motors control on my IR remote so I can make it move wherever and have it stop. 

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
