# compose-artistry
A collection of awesome animations and generative art made with Jetpack Compose!

## Contribution

All I shall seek is your contribution my dear friend! Let the world know about your mystical talent of creating art with JetpackCompose!

To add your contribution, all you should do is follow simple steps...

1. Create a new file in [`_posts/projects`](https://github.com/CuriousNikhil/compose-artistry/tree/main/_posts/projects) directory.  

    a. Name the file with `yyyy-mm-dd-<any name of your choice>`**.md** format (Basically create a markdown file).
    
2. Copy the [**`existing format`**](https://github.com/CuriousNikhil/compose-artistry/blob/main/_posts/projects/2017-04-01-composeart.md) from any other file present in the same folder. It should be something like this 
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/16976114/155303905-7a392ebc-b5a8-4a25-9b24-7cd0aaf1b381.png">

3. Put up all the required details

```markdown
---
permalink: /:title/
category: projects

project:
  title: "<name of the animation/art>"
  video: "https://user-images.githubusercontent.com/blaablaa/blaablaa/blaabla.mov"
  image:
  link: "https://github.com/<your-repository-path-to-code-on-github>/<filename>.kt"
  keywords: "k5-compose" 
---

```

    a. `title` : Your animation title
    
    b. `video` : Just drag and drop the video of your art/animation into the file you are editing on Github and paste the link it has generated as value
    
    c. `image` : Image link for your animation/art (Or you can do the same like video, just drag and drop the image into your Github file while editing and set value as link)
    
    ~~~
        My friend, however, you must only include either a video or an image of your art piece. (Just don't add both)
    ~~~
    
    d. `link` : The link to your code (/gist/repository)
    
    e. `keywords` : You know what is this.

4.  Raise a PR~ !!!!

### License

Licensed under Apache License, Version 2.0 [here](https://github.com/CuriousNikhil/compose-artistry/blob/main/LICENSE)

This Jekyll Theme is taken from [https://github.com/arnolds/pineapple](https://github.com/arnolds/pineapple) and modified.
