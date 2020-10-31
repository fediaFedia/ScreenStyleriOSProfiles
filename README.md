# ScreenStyleriOSProfiles
<img src="https://i.imgur.com/bv7jpd4.png" align="right"
     alt="Logo" width="180" height="180">
For https://screenstyler.com

<p>So as nobody else made such a repo, I decided to showcase how we create the icon Profiles on ScreenStyler.com</p>
<p>Really basic stuff, but stick around there's something more.</p>
<p>Also, if you'd like to get involved in this project, don't hessitate to reach out :)</p>


     
## What is ScreenStyler.com?
It's a cool new utility to style your iPhone (and soon iPad) homescreens. We thought it's cooler and easier to do that with a mouse and keyboard, and then apply it on your Device so you don't spend hours trying to get it right.
We also offer a way to install the custom icons easily using Profiles.

<img src="https://i.imgur.com/0TdjcFH.gifg">
     
     
## Are Profiles unsafe? 
If used correctly, they're perfectly safe
That's why this repo exists, you can dive into it and see that it's actually quite simple, here's how they're made:

1. Create the start and end parts of the mobileconfig file
2. Add the middle part, which also includes the image base64 data, launch scheme, etc.
3. Combine start, middle, and end, then generate a text blob.
4. BONUS: Digitally sign it!

## What else is in this repo?

As a bonus, I've included a little iTunes Store API parser with gets bundleIds.
Additionaly, there's a launch scheme JSON.

I hope someone can help us expand the launch scheme :)
Happy coding!
