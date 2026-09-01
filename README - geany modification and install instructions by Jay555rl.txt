README - geany modification and install instructions by Jay555rl
1:02 PM 9/1/2026


EXCLAMATION::: I do not own geany. For creative freedom, and primarily for learning purposes, I have modified geany and submitted a copy of modified geany with upgrades to the go-to-line() function requested by willbprog.

This repository here is the entire geany program that I have entirely upgraded. Both my wits, and with the help of ai assisted tools.

What it features is a upgrade, requested by willbprog on the official geany github forum, requesting for; 

]]] Some kind of feature that would automatically clear the search input bar within the go-to-line() function. request number #4628

WillbProg's request was met and responded on; some time around july 17 2026 at midnight.

WillbProg wanted a feature like this, as exclaimed, he needed a feature that would automatically clear the inputs that he types into the search bar of the go-to-line(). And I was willing to build this feature for him, out of gaining experience in realworld programming, development and networking. 

---

Before building this add-on feature, my initial and confirmed design would be that; Will willbprog opens the go-to-line feature, not only will there be a pop up, but, between the search engine bar, and the 2 "cancel" and the "ok" buttons, I would insert a check box between the search bar and the buttons.

For when the user opens the go-to-line() function, checkbox would remain checked to TRUE for remembering the input number from the previous number entry. 

However, if the user, unchecks the checkbox to false, for every time the box is reopened within the next function session, the entire entry bar would be entirely cleared.

 - This was my idea.

And so on, moving onto my ai assistants, I have built and implemented the requested feature to the function, assembling it with notepad++, cygwin terminal before porting the display of our modified geany program to geany x. For me, it was very successful. I was able to generate the geany.exe.manifest, and run it through a sepparate window with a simple geany keyword command in cygwin.

The only issue that I had was that, my first attempt at editing it, I tried to STANDARDIZINGLY append the toggle true/false value variable into the preferences settings window of geany, and implement the true/false checkbox to the go-to-line() function pop-up. And then mirror them together in sync. But that was incredibly complicated.  So, instead, I implemented the checkbox and the static variable literally only within the go-to-line() window.

Because of not following the standardized way, I am not going to publish this geany version to the official geany improvement page. But I will publish it right here, on my account for willbprog, and anyone else to download and use. Maybe in the future, I'll make another update that would also include the checkbox deeply inside of preferences.

I want to thank willbprog for providing me a request for a fix that is not too big for me, but easy enough to successfully implement, and learn from it. This is my very first project, and my very first contribution after 2 years and almost 9 months of studying and practicing programming, and acquiring some ai assistants.




HOW TO INSTALL ONTO A LINUX BASED SYSTEM (Debian / Ubuntu / POSIX):

To install and run this modified version of Geany on your Linux distribution, follow these straightforward steps in your terminal:

1. Clone this repository to your local machine:
   git clone https://github.com/jay555rl/geanyWorks-buildingGeany.git

2. Navigate into the repository directory:
   cd geanyWorks-buildingGeany

3. Configure the build environment for your system:
   ./configure

4. Compile the source code:
   make

5. Install the executable to your system:
   sudo make install

6. Launch your newly built Geany IDE!
   geany &












