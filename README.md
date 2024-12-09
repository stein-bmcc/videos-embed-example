# Embedded Video on a Web Page Example
This is an example template file for how to embed a YouTube on a web page.

1. **index.html** has an example of embedding a YouTube video
    1. For the video element you have to upload your video file to YouTube first.

## Instructions

For this you will edit index.html and upload your video to the media folder.

To use this template you will need to:

1. Upload your video file to YouTube.
2. On your Video Page on YouTube
    1. Click the Share button
    2. Click the Embed icon
    3. Copy the iframe element – All of it.
3. Delete the iframe that is on this page.
4. Paste in the iframe you copied in the same spot.
5. Change the figcaption content to fit your video. If you made it then give yourself credit.
4. Change all of the instances of YOUR_NAME in the header and footer.
5. Change the text in the h1 from Your Project Name to your project's name.
6. Delete these instructions
7. You can also change the CSS to update the styling if you like (not required).

### Different Aspect Ratios

In order to make the embedded video responsive, there is some special CSS that is applied to a div around the iframe. This CSS is different for different aspect ratio videos. Most video is 16:9 aspect ratio and if yours is, you won't have to change anything. If you have a 4:3 video or other ratio then you will have to update the class in the video wrapper. Here are two examples

 #### 16:9 Aspect Ratio
 This is what is already there.
```
<div class="videoWrapper ratio-16-9">

	<!-- iframe below is Copy & Pasted from YouTube replace with your own -->
	<iframe width="853" height="480" src="https://www.youtube.com/embed/IiJzbXzOdHQ" frameborder="0" allowfullscreen></iframe>
  
</div><!-- end .videoWrapper -->
```

 #### 4:3 Aspect Ratio
 For this change the ratio in the class to **ratio-4-3**
```
<div class="videoWrapper ratio-4-3">

	<!-- iframe below is Copy & Pasted from YouTube replace with your own -->
	<iframe width="1280" height="720" src="https://www.youtube.com/embed/tocJ_mKu1GU" frameborder="0" allowfullscreen></iframe>
  
</div><!-- end .videoWrapper -->
```
For more information, see this CodePen: [https://codepen.io/profstein/pen/mrMLRj](https://codepen.io/profstein/pen/mrMLRj)
