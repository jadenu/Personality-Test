# Personality-Test

This is a project made for my Intro to Psychology class. It is a website that first prompts users with 25 questions that each have slider, and users drag the slider to show the level to which they agree with the prompt. After they submit, it shows them a page with 5 personality traits, and estimates the amount of each trait the user has based on their responses. It will show either a trait or its antonym (i.e. neuroticism or balance) depending on which the user aligned more with, so there will never be one with less than 50% agreeance.

Currently it doesn't work, but a goal before this project is due is to connect to the google api and store responses to the test in a google sheet, so that responses can be compared to each other, perhaps giving users a percentile for their results.

^ yeah about that comment... didn't happen. I spent way too long (~10 hours or so over 2 days) trying to get some method of saving data on a backend of some sort, first I tried using a php server, then the google api to use a google sheet, then a simplified api for google sheets (sheetsu), which worked but to write it was a paid service so no, then I tried a python server, and that seemed the most promising for a while. Of course, because it seemed promising, I poured more time than I probably should've into it, and I ran into issues with 'CORS', and that was a brick wall for a while. I wouldn't say I gave up, but I decided that it was no longer worth my time, because saving results is a fairly unnecessary feature anyways. I will probalby revisit something similar in the future, it was interesting and could prove useful in the future, but for now it stops here. The rest of the site still works beautifully, and I'm proud of Reed's and my work.

This project was a collaboration with Reed.

The site is hosted through netlify.com, and all coding work was done in notepad++.
