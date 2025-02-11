# Welcome! You are on the landing page for the SalSoul Website editor!

If you are seeing this, you are on the editing/coding screen of your website. To change your homepage, you need to click into the file called 'index.md'

### Background/Specifics:
This website is built using GitHub's internally managed Jekyll software. It requires strict file and folder formatting to be rendered into a website. New images need to be added to the _assets/images/ folder.
To edit the background image, or the navbar image, you need to go to assets/css/style.css file, and then change the 'body' or '.navbar' url images. Just look for 'background-image' tags.

Based on it's formatting, and this GitHub accounts name, the current website is rendered to https://salsouldelmad.github.io/salsouldelmad/ for free. 
To change this, you'll need to talk with whoever you bought your URL from, and hook it up there to use https://salsouldelmad.github.io/salsouldelmad/ as the source code.

This initial website was made by Davud Porter 2025. Questions/Comments should be sent to davudp354@gmail.com and include 'SalSoul' in the subject line.

### Music/Video Embeds:
A couple problems can arise when changing links. All the embeded links are in index.md

# Soundcloud:
For soundcloud links, make sure you are changing the section that starts with, 'src=', and you grab the link from Soundcloud -> Share -> Embed. Alternatively, you can copy-paste the given code line in Soundcloud (it should start with "<iframe width=...>") and paste it over the iframe code in index.md.

# YouTube
Make sure in the songs settings on YouTube (if you are the owner of the YouTube channel), you have enabled Embeded linking for the song. Additionally, after 'www.youtube' add '-nocookie.com/embed/' so that the URL looks like, "https://www.youtube-nocookie.com/embed/" This is needed for most websites to not be flagged as a virus/shady site. **If you don't do this, Google will knock you down on the algorithm and make you a lot harder to find.**
