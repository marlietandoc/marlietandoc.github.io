---
title: Memory errors in behavior, brains, and machines
summary: Our memories are not perfect recordings of the past. But instead are prone to error, misinformation, and bias. As part of my PhD, I have been identifying what memories are most susceptible to such errors. By combining behavioral experiments, fMRI, and neural networks, we show that remarkably similar memory errors exist in humans and machines. We also find that these biases are not random mistakes, but are a product of an optimal learning system.



tags:
  - Research
date: '2022-12-10T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Figures from my talk at Neuroscience '22
  focal_point: Smart

links:
 - name: Slides (2022)
   url: 'project/example/tandoc_sfn_2022_website.pdf'
 - name: Video (2021)
   url: 'https://youtu.be/l6UkD4C12bA'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: = ""
---
Information differs in how generalizable or specific it is across experiences. For example, as we encounter birds we can learn that there are shared features that link these experiences together (birds can fly and lay eggs). But at the same time, we can also learn that there are unique features that set experiences apart (flamingos are pink and have long legs). We tested whether or not people misremember things differently depending on whether or not it is shared or unique.

In short we created online memory games where participants memorized the colors of cartoon satellite categories. We then tested how people's memory for colors were distorted based on whether or not that satellite part was shared or unique across satellites (like in the bird example above). We used color because it gives us an tightly-controlled and accessible way to measure how memories are being distorted.
![Memory game visualization](memorygame.png)

We hypothesized that if a part was shared across satellites then you might misremember its color as being more similar to those other satellites, a kind of memory error or false memory. We also trained a biologically-plausible neural network model on the same satellites to see if it would also show this memory error.

In humans, we find that memory biases are strongest for information that is shared across experiences (shared features). In the neural network model, we find a strikingly similar effect where the model's internal hidden layer representations are also distorting shared features the most.

![Main finding](finding.png)

This shows that both humans and neural network models—both of which are remarkable at learning patterns—show memory errors that emerge from learning these patterns.This makes sense! If we learn that certain things in the world are related, in our mind we might represent those things similarily, and thus it is more likely we will mix up the details. We are now collecting neuroimaging data (fMRI) where we will examine how these memory biases manifest from human brain activity. 

<strong> My Role: </strong> As part of my PhD work I led experimental design, programmed the experiments, assisted in securing grant funding, created the stimuli, collected data online, wrangled/analyzed data in R. I also recently presented this work as a talk at {{< staticref "https://www.sfn.org/meetings/neuroscience-2022" "newtab" >}}Neuroscience '22 in San Diego{{< /staticref >}}, one of the biggest science conferences in the world.
![SfN 2022 Talk](sfntalk.jpg)


