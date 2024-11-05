📺 Vertical Fullscreen YouTube Video Hack
I made this for myself to watch YouTube in vertical fullscreen while multitasking or code editing, but figured it might help others too! This simple HTML file lets you keep a video front and center while you work (or pretend to)😁.

🚀 How to Use
Download or clone this repo.
Open the index.html file in any text editor or code editor.
✏️ Swap in Your Own Video
To use your own YouTube video, just update this part of the HTML:
by Replacing **YOUR_VIDEO_ID_HERE**
```html
<iframe width="100%" height="100%" src="https://www.youtube.com/embed/YOUR_VIDEO_ID_HERE" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
```
How to Find Your Video ID
The video ID is the unique part of a YouTube link that comes right after ?v= in the URL. Here’s how to find it:

For example, in this URL:

```arduino
https://www.youtube.com/watch?v=KLuTLF3x9sA&t=113s&ab_channel=RelaxationFilm
```
The video ID is KLuTLF3x9sA. It’s always right after ?v= and typically stops before any additional parameters (like &t=113s or &ab_channel=RelaxationFilm).

So, replace YOUR_VIDEO_ID_HERE with this video ID to embed it in the HTML:
```html
<iframe width="100%" height="100%" src="https://www.youtube.com/embed/KLuTLF3x9sA" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
```

📐 What This Does
This HTML file:

Makes your video fill the screen vertically, perfect for a multi-window view.
Keeps video controls within easy reach.

🖼️ Before and After
Here’s how the layout looks in action:

Before:

After:

🎉 Enjoy!
Just open the HTML file in your browser, and you’re all set for smooth, vertical YouTube playback. Enjoy and happy multitasking!
