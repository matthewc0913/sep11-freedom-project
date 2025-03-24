# Tool Learning Log

## Tool: **Vidcode**

## Project: **Freedom Project**

---

### 9/30/2024
* I used a picture that I downloaded last year to get a picture and used multiple ways to change it.
* For Example I used Blur, pixelate, black and white, grayscale, and many more.

```
movie = image();
movie.source = "loki.jpeg";
blur(5);
noise(5);
exposure(90);
grayscale();
pixelate(1);
color_invert();
black_and_white(1);
```

### 10/21/2024:
* Trying to download a video to see how well I could use it

### 11/4/2024
* I added graphics, text, and emoji's to change to the image that I used . 
* For Example I change the text color, font, size, postition, and the emoji's size, and postition.

```
movie = video();
movie.source = "lavalamp.mp4";
var emoji = text('😈')
emoji.x = 510;
emoji.y= 350;
var my_graphic2 = graphic("rainbow.png");
emoji.size= 100;
var my_text = text("I'm an AMAZING coder!")
my_text.x = 20;
my_text.y= 200;
my_text.color= "#00E1FF"
my_text.size = 50
my_text.font = "Comic Sans MS"
```


### 11/18/2024
* I was looking up how to have a video using Javascrpt
* Now I an learning how to convert Vidcode to an IDE using the code below

```
let vid = document.getElementById("myVideo");

function playVid() {
    vid.play();
}

function pauseVid() {
    vid.pause();
}
```

### 12/2/2024
* I was looking up how to loop a video using Javascrpt and Vidcode.
* My next steps is to research how to convert Vidcode to an link that people outside of Vidcode can use.


```
var myVideo = document.write('input');
if ( myVideo.loop == 'input') { 
  myVideo.loop = true;
} else { 
  myVideo.write('ended', function () {
    this.currentTime = 0;
    this.play();
  }, false);
}
myVideo.play();
```

### 12/16/2024
* What I did is I downloading the code from vidcode to connect it to an IDE/Github and naming that file videcode.js to try and have it work in a repo on my Ide.
*  My next steps is to work on a mini project during my Christmas break.

```
var videcode = videcode.js;
if ( videcode.loop == 'input') { 
  myVideo.loop = true;
} else { 
  videcode.write('end', function () {
}
videcode.play();
```

### 1/6/2025
* What I did is I learned that you cannot export videos or code from vidcode to an IDE/Github. I have decided to screen record the code that I have and add the code as commit to not interfere with other code.
* My next steps is to screen record from my computer

[Test Vid](SeanManeana.webm)

### 2/24/2025
* What I did is I learned that you cannot export music to an IDE/Github. I have decided to screen record the music and the video at the same time so I can have both of them together playing at the same time.
* My next steps is to have the music and video work together to make one video

### 3/3/2025
* I have downloaded the music i want to use and the video I want to use
* My next steps is to have the music and video work together to make one video and somehow add that to the website.

### 3/17/2025
* I have created a video with the og vid and the music for the website
* My next steps is to put that video on Github and have video playable on the website

### 3/24/2025
* I have the video on the website but it is not playing correctly sadly. 
* My next steps is to have the video to work in the website.
