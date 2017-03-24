# YoutubeResponsive MODx
MODx Responsive Youtube snippet

YouTube video to re-size depending on the browser size or device width. However, when I added the embed code, the video had a fixed height and width. (uggh!) This looked fine on desktop computers, but pretty much broke the design when viewing on a mobile device. I wanted to know how to make a youtube video mobile. Therefore, we needed a responsive YouTube embed code. One would think that videos that with 100% width would automatically resize to the surrounding container. Well, that is not the case. Surprisingly, Youtube does not automatically have a responsive embed code.

The fix was actually quite simple. Here’s how to make a youtube video mobile:

1.Install via Package Management.
2.Create TV with your desired name, and assign to template that you want to appear.
3. Call it in your template like this

  [[!Youtube? &link=`[[*your_tv_name]`]]
  
4. Thats it, enjoy :)
