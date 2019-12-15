# Danbooru Viewer


![Monogatari Sample](/images/sample2.PNG)


A single page website that scrapes pages from [Danbooru](https://danbooru.donmai.us/) according to a tag and allows you to view the full-sized images one by one with simple controls that I built on a ( ͡° ͜ʖ ͡°) impulse

Meant to be used for various ( ͡° ͜ʖ ͡°) purposes

## What is Danbooru?

An image board consisting of pretty muchh all anime/manga/light novels related artwork present on the internet, from sites like Pixiv, Twitter, DeviantArt etc and also consists of a lot of Original Content. The artwork is both SFW and (mostly) NSFW ( ͡° ͜ʖ ͡°).

## Usage-

Download the latest release- [index.html](https://github.com/sin3point14/danbooru-viewer/releases/download/v1.0/index.html) and open it in your favourite browser  
OR  
Go to https://sin3point14.github.io/danbooru-viewer/  

__NOTE__: Avoid using second method as it gives a lot of 403 errors and the images won't load, but let's say that you don't have any other option then set the Page No to Last Page and it should work.

While typing the tag into the textbox saying `Enter tag here` select the __most relevant one from the autocomplete dropdown__.

![Monogatari Autocomplete Sample](/images/sample1.PNG)

#### Desktop- 
Left/Right arrow keys to go to previous/next image

#### Touch Devices- 
Left/Right swipe to go to next/previous image

Control `Current Image No` and `Current Page No` using the UI  
They correspond to-

![Monogatari variables explaination](/images/usage1.png)

__Tip__: Try putting some random numbers in the `Current Page no`(within limits please, as I have not implemented proper error-checking) for a brand new ( ͡° ͜ʖ ͡°) experiences everytime

__NOTE__: `Current Image no` will reset evrytime you press `Search`, it's a bug, I will fix that soon
__NOTE__: Last Page will diaplay incorrect for tags with hell lot of images, again a bug, will look for a workaround soon

## Wanna Contribute?

Don't.  
The codebase is a nightmare of CSS, JS, Bootstrap currently with snippets from all over the internet bound by very fragile code.  
I had a ( ͡° ͜ʖ ͡°) impulse and then built it, what else could you expect?  
Though I do have plans to clean up this project and implement Vue.js while learning it  
Unless, you are a masochist, then feel free to make my life easier by opening up a pull request  

## Milestones

- [ ] add support for other booru based sites like [Gelbooru](https://gelbooru.com/)

- [ ] Load multiple low res images at once(somewhat like google images) using-

![Danbooru inspect element](/images/goal1.PNG)
(^ source for an image preview on Danbooru home page)

- [ ] shift to Vue.js to escape vanilla hell

## Mobile Screenshots-


Mobile View-

![Mobile Monogatari Sample](/images/sample3.PNG)


Mobile Navbar-

![Mobile Navbar Sample](/images/sample4.PNG)