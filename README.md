# Danbooru Viewer


![Monogatari Sample](/images/sample2.png)


A single page website that scrapes pages from https://danbooru.donmai.us/ according to a tag and allows you to view the full-sized images one by one with simple controls

Meant to be used for various ( ͡° ͜ʖ ͡°) purposes

## Usage-

Download the index.html from the Release Page and open it in your favourite browser
OR
Go to https://sin3point14.github.io/danbooru-viewer/

__NOTE__: Avoid using second method as it gives a lot of 403 errors and the images won't load, but let's say that you don't have any other option then set the Page No to Last Page and it should work.

While typing the tag into the textbox saying `Enter tag here` select the most relevant one from the autocomplete dropdown(IMPORTANT).

### Desktop- 
Left/Right arrow keys to go to previous/next image

### Touch Devices- 
Left/Right swipe to go to next/previous image

Page number(of the corresponding page on danbooru of the image, format- https://danbooru.donmai.us/posts?page=PAGENO&tags=CURRENTTAG) and Image number(0 indexed image number of the current image on the correspoinding page on danbooru) can be directly controlled from the interface provided in the navbar so you don't have to start from the same image everytime.

__Tip__: Try putting some random numbers in the PageNo(within limits please, as I have not implemented proper error-checking) for a brand new ( ͡° ͜ʖ ͡°) experiences everytime

__NOTE__: `Current Image no` will reset evrytime you press `Search`, it's a bug, I will fix that soon
__NOTE__: Last Page will diaplay incorrect for tags with hell lot of images, again a bug, will look for a workaround soon

Screenshots-


Autocomplete-

![Monogatari Autocomplete Sample](/images/sample1.png)


Mobile View-

![Mobile Monogatari Sample](/images/sample3.png)


Mobile Navbar-

![Mobile Navbar Sample](/images/sample4.png)