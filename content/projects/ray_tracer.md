---
date: '2024-12-21T06:09:31-05:00' # date in which the content is created - defaults to "today"
title: 'GPU Accelerated Real-time Ray Tracer'
draft: false # set to "true" if you want to hide the content 
logo_x: "images/raytracer.jpg" # example: "images/clients/asgardia.png"
logo_2x: "images/raytracer.jpg"  # example: "images/clients/asgardia@2x.png"
link: "https://github.com/SIDD017/GPU-Accelerated-Ray-Tracer" # optional URL to link the logo to

params:
    button:
        icon: "icon-arrow-right"
        btnText: "Project Link"
        URL: "https://github.com/SIDD017/GPU-Accelerated-Ray-Tracer"
    image:  
        x: "images/tracer.jpg"
        _2x: "images/tracer2.jpg"
## The content is used for the description of the project
---
This project follows from the CPU based implemenation of a simple path tracer created using C++. While it served as a great introduction to ray tracing and graphics programming in general, the base implementation was extremely inefficient as core computations were sequential, resulting in extremely long render times (nearly 1 hour to render a single frame).