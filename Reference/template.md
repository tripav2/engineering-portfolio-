---
layout: post
title: 
description:  
skills: 
  - 
  -


main-image: project-image.webp
---


# Header 1 
Used for the title (already generated automatically at the top)
## Header 2  
Use this for the header of each section
### Header 3 
Use this to have subsection if needed



## Embedding images 
{% include image-gallery.html images="images/project1.png, images/project2.webp" height="300" %}



## Embedding youtube video
The second video has the autoplay on. copy and paste the 11-digit id found in the url link. Example: https://www.youtube.com/watch?v={**MhVw-MHGv4s**}&ab_channel=engineerguy
{% include youtube-video.html id="MhVw-MHGv4s" autoplay= "false"%}
{% include youtube-video.html id="XGC31lmdS6s" autoplay = "true" %}

you can also set up custom size by specifying the width (the aspect ratio has been set to 16/9). The default size is 560 x 315.
{% include youtube-video.html id="tGCdLEQzde0" autoplay = "false" width= "800px" %}



## this is you add a hozontal line
---


## Adding bold text
this is how you input **bold text**

## Adding italic text
Italicized text is the *cat's meow*.

## Adding ordered list
1. First item
2. Second item
3. Third item
4. Fourth item

## Adding unordered list
- First item
- Second item
- Third item
- Fourth item

## Adding code block
```ruby
def hello_world
  puts "Hello, World!"
end
```

```python
def start()
  print("time to start!")
```

```javascript
let x = 1;
if (x === 1) {
  let x = 2;
  console.log(x);
}
console.log(x);

```

## Adding external links
[Wikipedia](https://en.wikipedia.org)


## Adding block quote
> A blockquote would look great if you need to highlight something


## Adding table 

| Header 1 | Header 2 |
|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 |
| Row 2, Col 1 | Row 2, Col 2 |

make sure to leave aline betwen the table and the header


