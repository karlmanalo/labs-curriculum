# Sprint Challenge: Sprint 2

## Objectives

- Student can articulate their delivery process in contributing to and completing individual tasks.
- Student can demonstrate, in detail, how their solution relates to the specification and architectural standards.
- Student can articulate the challenges and lessons learned from managing their time working on a complex project in a team.

## Prompt 1 - Communicating Individual Contribution

On the job, you will be responsible for shipping features regularly. Engineers are given tickets and are expected to deliver them. Hiring managers want to see that you are capable of delivering a feature.

Here are some examples of hiring manager interview questions:

- "Tell me about a project you've built."
- "What were some technical challenges on that project? How did you overcome them?"

We took these questions and cooked them into your labs experience. This week, you should have shipped at least one feature. Answer the following questions like you would in an interview:

### Questions you need to answer

1. Describe what you built this week. Link any relevant pull requests or paste screenshots of code.
   
   This week, I initiated deployment of the FastAPI to AWS by way of Elastic Beanstalk. This API will be used by the data science team to relay key descriptive statistics of a city as JSON objects to the front end in order to build visualizations for each respective descriptive statistic.

2. How does what you built contribute to the overall product your team is building? What user problems does it help solve?
   This API will allow the front end to communicate and retrieve data for a given city from the data science back end. In terms of user experience, this API enables the user to visualize relevant statistics for a given city.

3. Describe your delivery process for what you built this week from ideation to breakdown to implementation. What challenges occurred during the delivery process that you didn't foresee?
   
   I was tasked with deploying the data science API to AWS. AWS and Elastic Beanstalk are two technologies that I am unfamiliar with, so the first step I took was reading through and understanding the deployment instructions from beginning to end, ensuring that I understood at the most fundamental level every step to be taken and every line of code. Upon reaching a working level of understanding of the process, I took care to follow each instruction to the T and stopping to understand when the instructions did not match up with what I was seeing on my machine. Eventually, I deployed the API to AWS, but not without some troubleshooting along the way.
   One of the challenges that occurred along the way was an instruction to install pipx, and subsequently use pipx to install Elastic Beanstalk. I entered these lines of code as written, but once I reached the point of having to utilize EB in the CLI, "eb" was not recognized as a command. I went back and made sure that the steps I took matched up with the readme, and it did. After some Googling and failed attempts at solutions, I decided to just use pip to install Elastic Beanstalk, bypassing the utilization of pipx. This fixed my problem and I was able to deploy the initial version of the data science API.

## Prompt 2 - Communicating Teamwork

As a software developer, you will almost always be on a team. As a result, engineering hiring managers want to see how you work on a team. As a junior developer, you will often pair with seniors on features. Here are some examples of interview questions you may get asked concerning teamwork:

- "Tell me about a time you worked on a team. What was hard about it?"
- "What is your greatest weakness as a team player? How have you improved?"

This week we taught you how to pair with other team members. You should have worked with at least one other person to deliver a feature. Reflect on that experience and answer the following questions like you would in an interview:

### Questions you need to answer

1. How did you work with another team member to deliver a feature this week? What role did you play?
   
   I pair programmed with a fellow data scientist to deploy an API to AWS. Initially, I played the role of navigator. I joined about halfway through his deployment process. I communicated with the driver and ensured that I understood the steps that he was taking and why he was taking them. When I felt like he was moving too quickly or I didn't fully understand what error he was running into, I asked him to go back and copy-paste the error message into our Slack chat so that I could troubleshoot it on my end. The solutions that we found required multiple uninstalls and reboots, and mutually agreed that, since I hadn't been there to catch any errors in the first half of deployment, we would switch roles (where I was the driver and he was the navigator) and walk through the readme from the beginning together.

2. What did you learn this week from working in a team? How are you going to improve your teamwork in the future?
   
   I learned that, as cliche as it sounds, communication is key. Going a level deeper, making sure that all parties understand the problem in the same way and are visualizing the same solution is vital, and hashing out those issues before any redundant/unneeded work is done is a huge time saver (and can also alleviate any frustrations that might arise from said unneeded work). 
   In order to improve my teamwork in the future, I will work on being available at all needed hours and keeping a line of communication open with the team.

## Prompt 3 - Professional Development Resume Updates

This week you gained more clarity surrounding your individual contributions and what is happening with your project. Use this clarification, along with your understanding of power statements, to update the projects sections of your resume. When adding a project to your resume, you should include power statement bullets describing the project as if it were a job! Without these bullets you're simply sharing the name of a project (and maybe a tech stack) with little to no clarity on what you did on that project.

To ensure you are creating a robust and ready to use job search resume, use this [resume checklist](https://www.notion.so/lambdaschool/Resume-30f5e6add3324891823192487798cb6d) as a way to organize and add content. If you skipped the resume lesson earlier in the curriculum and are starting from scratch, you'll want to review [this assignment worksheet](https://docs.google.com/document/d/1yAvlgwSPTdXxAbtx3mgfWp6dkNnqtzGGLlRy2yQ7fiA/edit) to establish a resume draft (though the resume checklist will help you establish a draft as well).

### To complete the career portion of this challenge:

1. Updated your resume to include your labs project, with power statements articulating your individual tasks.
2. Upload this resume version to CV compiler for feedback:

    1️⃣ Go to the website [https://cvcompiler.com/students/lambda](https://cvcompiler.com/students/lambda)

    2️⃣ Log in (using LinkedIn or GitHub) -> Fill out the form

    3️⃣ Enter the special promo code [LSalumni, ANDresumes, iOSresumes, DSresumes, WEBresumes, UXresumes] during checkout

    4️⃣ Upload your resume and start working on improving it with CV Compiler

3. After making the recommended CV Compiler edits, upload your resume to google drive and drop a link.

4. Update your LinkedIn to include any new content you made for your resume. The experience bullets you created for your resume and projects are great examples of content you should consider bringing over to your profile.

**Your submission for Prompt 3 should be a link to your resume**

## [Sprint Challenge Rubric](https://www.notion.so/1f9fa8ec9c4b4453a3fb21b60cc5352c)

## Additional Resources

- [How to Respond to Interview Questions About Teamwork](https://www.thebalancecareers.com/how-to-respond-to-interview-questions-about-teamwork-2061100)
