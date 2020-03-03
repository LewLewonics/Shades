# Shades
<a href='https://lewlewonics.github.io/Shades/'>Live Version</a>
A minimal and colorful Touhou Project start page theme.
<img src="Thumbnail.jpg" width="100%">

How to use
-------------------------------
<ol>
  <li>Download or Clone this repository. You can find the button on the top right</li>
  <li>Go to wherever you downloaded it right click "index.html" select open-with your browser of choice</li>
</ol>

Customize
-------------------------------
Open up the script.js in a text editor and begin messing with the links on the top of the document. It should be
fairly straight forward from here.

You can customize:
<ul>
  <li>Categories</li>
  <li>Links</li>
  <li>Color palette</li>
  <li>Background and Welcome Message</li>
  </ul>
  
### For Links and Colors
```javascript
/////////////////////////////////////////////////////////////////////////////////////////////////
//                                      FOR USER 
// LEFT ----> RIGHT [] [] [] [] []
//Social    
const category1_titles = ['Youtube', 'Twitter', 'Gmail'];
const category1_links = [`https://www.youtube.com`, `https://twitter.com`, `https://mail.google.com/mail/u/0/#inbox`];
//Anime
const category2_titles = ['Twist.moe', 'Anilist', 'Konachan', 'Wall Haven'];
const category2_links = [`https://twist.moe`, ,`https://anilist.co`, `https://konachan.net`, 'https://wallhaven.cc/search?q=id:5&ref=fp'];
//Favorites
const category3_titles = ['Online-Go', 'Reddit'];
const category3_links = [`https://online-go.com`, `https://www.reddit.com`];
//Programming
const category4_titles = ['Github', 'W3 Schools', 'Stack Overflow'];
const category4_links = [`https://github.com`, `https://www.w3schools.com`, `https://stackoverflow.com`];
//Music
const category5_titles = ['Listen.moe', 'Spotify', 'Sound Cloud'];
const category5_links = [`https://listen.moe`, `https://www.spotify.com/us/`, `https://soundcloud.com`];
//In order of left -> right
const categories = ['ソーシャル','アニメ','お気に入り','プログラミング','音楽'];
                                                                          //Background Color
const card_colors = ['#28796B','#693273','#410E1A', '#7A94AB', '#D79052', '#2B2F3D']
//////////////////////////////////////////////////////////////////////////////////////////////
```

### For background and welcome message
<img src="settings.jpg" width="100%">

