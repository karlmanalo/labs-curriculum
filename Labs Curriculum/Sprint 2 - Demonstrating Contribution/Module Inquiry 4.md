# Module Inquiry 4

## Questions

1. Link to the pull request you are most proud of.
   
   https://github.com/Air-BnB-2/BE/commit/3eda9f74d1e30a40b1a2f9d2c42c318c54c9f06f#diff-ac5552fd6a3c08ad22387efbe42d137d

2. Why are you proud of this feature? What was difficult about its implementation?
   
   Perhaps not in the spirit of this question (it's not even from this Labs project), but this pull request represents a lot of work that I put into helping a teammate troubleshoot an issue she was having (rather than a technical difficulty as might be implied by this question). After completing my work building a predictive neural network model for AirBNB pricing, I reached out to a teammate to see if she needed help implementing her portion of work. It turned out she did. I spent literal entire days with her on Zoom, suggesting potential solutions to the technical issues she was running into. I eventually found that TensorFlow's sheer size as a library was causing her deployment to Heroku to crash, so I ended up reworking my predictive model to use a less space-intensive library, which ended up being more accurate than the original neural network model we were going to deploy.

3. How does this feature help the user?
   
   This feature allowed the user (someone renting their property out on AirBNB and trying to optimize pricing) to enter all of the characteristics of their property and outputted a price that they should list their property at to maximize profits.

4. Think about the process of delivering this feature: from ideation, to scoping, to pairing, to testing. Knowing what you know now, what would you change about the way in which you delivered this feature?
   
   I would have communicated more with the front end to brainstorm what we wanted the user experience to look like, and break each user story down into tangible tasks until everyone was on the same page.
