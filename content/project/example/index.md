---
title: Memory errors in behavior, brains, and machines
summary: Our memories are not perfect recordings of the past. But instead are prone to error, misinformation, and bias. As part of my PhD, I have been identifying what memories are most susceptible to such errors. By combining behavioral experiments, fMRI, and neural networks, we show that <strong>similar memory errors exist in both humans and machines.</strong> We also find that these biases are not random mistakes, but are a product of an optimal learning system.



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
 - name: Poster (2024)
  url: 'project/example/tandoc_CNS_2024.pdf'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: = ""
---
<strong> My Role</strong>: As part of my PhD work I designed and programmed the experiments, helped secure grant funding, created the stimuli, collected online data online, wrangled/analyzed data in R, and developed neuroimaging analysis pipelines.

<strong> Summary</strong>: Information differs in how generalizable or specific it is across experiences. For example, as we encounter birds we can learn that there are shared features that link them together (birds can fly and lay eggs). But we can also learn that there are unique features that set them apart (flamingos are pink and have long legs). We tested whether or not people misremember information differently depending on whether or not it is shared or unique.

In short, to do this, we developed online memory games where participants memorized the colors of cartoon satellite categories. We then tested how people's memory for colors were distorted based on whether or not that satellite part was shared or unique across satellites. We used color because it gives us a tightly-controlled and accessible way to measure how memories are being distorted. We hypothesized that if a part was shared across satellites people might misremember its color as being more similar to the color of the other satellites, a kind of with this blending of colors reflecting a memory error.
![Memory game visualization](memorygame.png)

In humans, we find that memory biases are strongest for information that is shared across experiences (shared features). In a neural network model trained on the same satellites, we find a strikingly similar effect where the model's internal hidden layer representations are also distorting shared features the most.
![Main finding](finding.png)

This shows that both humans and neural network models—both of which are remarkable at learning patterns—show memory errors that emerge from learning these patterns. This makes sense! <strong> If we learn that certain things in the world are related, in our mind we might represent those things similarly, making it more likely we will mix up the details </strong>. I have recently run research to look at these errors but in human brain by having people play the same memory games, but while lying inside an MRI scanner.

I was fortunate to have the opportunity to present this work as a {{< staticref "project/example/tandoc_sfn_2022_website.pdf" "newtab" >}}talk{{< /staticref >}} at {{< staticref "https://www.sfn.org/meetings/neuroscience-2022" "newtab" >}}Neuroscience '22 in San Diego,{{< /staticref >}} one of the biggest science conferences in the world.
![SfN 2022 Talk](sfntalk.jpg)

I also presented a neuroimaging (fMRI) version of this research at an international conference, Cognitive Neuroscience Society, in Toronto, Canada.
![CNS 2024 poster](cns_poster.jpg)


