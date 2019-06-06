+++
    #this is the "front matter" of the template of a project. It's the variables associated with the file
    #this portion is written in TOML (Tom's Obvious Minimal Language)
    
    title = "The Running Man"
    #replace takes the filename and replaces all hyphens with spaces so that when it appears on your page, it's using spaces. The filename is used in the URL and URLs can't have spaces so use hyphen in the filename.
    #title converts to title-case (using capital letters for principal words only)
    
    date = 2019-05-28T11:22:12-07:00 #the date the file was created

    
    shortDescription = "3D Animated Dance Cycle (Director, 3D Animator)"
    projectVideo = "338936046"
    #Project video is just the unique part of the URL  
    # For example, if the link is https://vimeo.com/285189099 then the unique part is  285189099
    projectVideoType = "vimeo"
    #Enter "youtube" or "vimeo". You can add other video types as well by editing single.html 
    projectImage = "theRunningMan_cover_image.jpg"
    #Enter the filename only. For example, "metropolis_album.jpg" 
    #This image should be saved in the project folder with the name of your project 
    projectImageAltText = ""
    #Alt text is the text that gets read by screenreaders for accessibility (typically for the visually impaired) 

+++
\
A 3D Animated clip based of the famous dance moved called “The Running Man”. The goal of this clip was to demonstrate a cycle animation that is made up of a few keyframes, and then repeated across the duration of a song. When it's played on repeat, the end and the beginning are seamless.

Software – Maya  
\
