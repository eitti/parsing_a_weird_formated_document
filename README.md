# parsing_a_weird_formated_document
Since I want to get a fising license, I want to create a small app to ask me all the current questions that exist. I found a pdf containing them, but due to the format, it's quite a challange for me to extract the text. Here I will try to solve this problem...

## 30.07.2024 I might just use the README as a diary
So I did a quick search to find a suitable library to achieve my goal. Actually that meant I just asked openAI's GPT for hints in the right direction. 
### Apache PDFBox
Easy choice. Of all programming languages I worked with, I am most familiar with Java. 
After just one or two minutes I read somethin about the  class

```DrawPrintTextLocation This is an example on how to get some x/y coordinates of text and to show them in a rendered image.```

Looks like it might be capable of solving my issue. 

The other recommendations were: 
- PyMuPDF
- pdfplumber
- PDFMiner
- OCR: Tesseract

I haven't actually looked at them at all, mostly because I am not familiar with Python and I am not here to learn, but to just solve a personal problem. If I'll strugle with PDFBox, I will give those other options a shot.
For now though the Apache PDFBox looks promising enough to try.

## 04.08.2024 Another day working on the problem

I found this:
https://github.com/BobLd/DocumentLayoutAnalysis/blob/master/README.md

This really looks very interesting at first glance. 
