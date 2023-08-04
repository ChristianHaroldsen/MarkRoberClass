# MarkRoberClass
In July of 2022, a friend and I took Mark Rober's Creative Engineering class. These are the projects I produced during the four week class.

The class was a lot of fun. One of the most interesting challenges for me was the time constraint. I had to complete each assignment in a limited amount of time, while I was keeping my daily job and routine, leaving me very littile time. This constraint actually gave me more focus and from that came a shocking amount of creativity.

This class really showed the Pareto Principle (80/20 Rule) in effect. I was able to brainstorm a huge list of ideas in a short period of time, pare them down to the do-able and intereseting ones, foresee problems, and creating a working prototype within less than a week. I normally work over 10x that timeline, if I even find the motivation to do so with life being what it is. This opened my eyes to how much more potential I have if I just dedicate to a project with a timeframe.

I'm putting these here so I can remind myself how much fun it is to be creative and just get something out there. Most of these ideas are by no means viable products to go to market or accomplish some grand goal, or even work moving past the first prototype stage. But they were all made with minimal money, a little bit of time, and a whole lot of fun.

# Part 1: Mechanical Engineering
This challenge's criteria were to make something involving food, using only mechanical components.

*Result: Snack Mag*  | TODO: Add video link

The Snack Mag is for when you're out shooting on the range and need a convenient place to store snackies. In this case a container with the same dimensions of a STANAG magazine fits into any existing gear you own to store your other magazines, allowing convenient storage and access alongside all your other gear.

For the prototype I cut some scrap wood I had lying around. It was a ruler themed coat hanger before so it looked kind of strange afterwards, but the wood held and I was able to make it in only an hour or two for three different versions. One split in the middle and returned with a spring, the second split in the middle but only had magnets to hold it back in place, and the third had a small lever at the top that was thumb operated to open and close.

Prototyping worked as intended! I originally though I would go with the magnet version but the spring version was much easier to work with. I also found that splitting it in the center of the magazine made it very difficult to use, so I planned to just have a small portion of the top come off. I essentially took the best of two prototypes and removed the worst, so I'm really glad I did it! Plus it took almost no time at all.

For my final product I thought about cutting an existing magazine in half and modifying it but that seemed like it could have a lot of issues in the limited time I had. Instead I used some acrylic sheets that I cut and glued together. Of course my cuts weren't very straight so it was a bit off, but it worked.I glued a hinge to the back and a small spring to close the lid.

In my final video I used the only conveient small bits of food I had in large quantities handy: dog food. Some got in my mouth 🤢.

# Part 2: Electrical Engineering 
The Electrical Engineering challenge was to use Arduinos, Raspberry Pi's, and other electronics in a way that involves art. I chose to create a device that seemed magical that could sit on a desk with no visible parts. It's even set up on a trio of spooky books to give it the evil scientist theme!

*Result: Science Bubbler* | TODO: Add video link

This started with the idead to have something that would be pleasing to put in an office. I used to work in a building that had a wall with bubbling water that changed colors and I always thought that was really cool and also relaxing. Since I work in Research and Development, something science-y seemed appropriate.

The basic idea was really simple: Have a container that filled and emptied with water with all the mechanisms hidden so it would look nice on a desk or wall. We had more than 10 extra plastic graduated cylinders in the lab so I thought "hey, why not 3?". From there I had a huge brainstorm of the potential variations I could do on the project. I could vary the time, add a speaker, add lights, make it Wifi connected, etc. etc. Because of the time constraints I settled on a program that would fill, hold, and drain at random intervals.

The prototype was as simple as ordering the components and making sure they worked. I drilled a hole in the bottom of the graduated cylinders and glued some tubing to them and hooked it up to a reservoir of water. I used a potentiometer to run the motor and sure enough, it pumped and held the water in the cylinder.

Assembling the device was easy. I happened to be throwing out some old books that week and there were three different spooky books so I saved them for this and hollowed out the pages. I ran the tubing through them and through a hole in my desk down below where the reservoir and electronics were kept. This wouldn't be wall mountable in it's current state but most office desks come with these holes drilled out for cables so it wouldn't be noticed if they were placed on top of one.

At this point it had taken me only an hour or two to prototype and then assemble everything. I spent less than 30 minutes coding a small program and then put everything together. I then spent the next two hours tweaking my code to death to try and get the darn thing to work. 🤦🏻‍♂️

It turns out each of the three motors performed slightly differently. This meant that the code I intented to hold the water would sometimes drain, hold, or continue filling the cylinders. The drain and raising had the same issues. To make it worse even the same motor would perform slightly differently over time and between tests, making it almost impossible to predict how it would work. I quickly decided I didn't care about perfection. What I ended up doing was taking the strongest motor and finding out how fast it could fill up the cylinder (minus some safety buffer at the top), and how much was needed to hold the water level. I set these at the maximum so that it would never overflow. Then I did the same with the weakest motor and the lowest fill so there would always be some water that made it into the cylinder. Finally to solve the drain time I just increased it to a really long time so it was sure to drain even the fullest graduated cylinder.

Whew! I knew that this project would need tweaks but I didn't realize how long it would take. I spent probably 80% of the project just getting the final bits of code to work. Part of what took so long was I had to disconnect the microcontroller, move it to another room with my computer, connect it, recode and recompile, return to the project, and connect the microcontroller every time. The smallest of tweaks took a minimum of 90 seconds.

In the end this project spawned an idea for something else I could create in the future. During the testing I thought it would be really convenient to have a set of potentiometers to change variables and a readout to record the values when I tweak them where I want them, but I figured it would take way too long to set that up. It gave me the idea to make a testing platform with lights, pots, switches, buttons, and a readout so I can quickly connect future projects to it when I need to tweak variables. This could potentially work for a sellable product too! Quite the unintended learning experience from this project.

# Part 3: Advanced Engineering & Storytelling

*Result: Hubby Rubby* | https://youtube.com/shorts/ICPdAG2f00A?feature=share
