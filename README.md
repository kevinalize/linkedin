# LinkedIn Post 20250404

```
$ git commit -m 'update cv.md for application'
```

Modern job hunt feels like throwing your resume into a **black hole**. Sending out countless applications, often to find yourself met with... silence. I am talking numbers like 10,000+ applications for a single opening, and if you're lucky, you might snag less than 5 interviews after sending out 1,000 applications (that's a <0.5% success rate!).

A combination of high volume and the ever-present ATS. You know, those digital gatekeepers that scan your resume for keywords and often toss it aside if it doesn't perfectly align exactly with the keyword patterns. Which means? Tailoring your CV for each and every role is a **must**.

But here's where the real struggle begins. Managing hundreds (or thousand!) of customised resumes and cover letters in Word or Google Docs? Forget about it. Version control becomes a nightmare, and the sheer volume is overwhelming. Still a mess.

So, I did what developer would do: I created a Git repository.

Yes, you read that right. I now manage my CV and cover letters using Git. Here's the breakdown:

- **VS Code as my editor**: I write my CV in Markdown (.md) format, using extensions to convert it to PDF.
- **Custom CSS**: I've crafted a CSS stylesheet to ensure my PDF CV looks professional and polished.
- **Branching Strategy**: I create branches for different job functions (e.g.: Full-Stack developer, Web Developer, ...). Then, for each specific job opening, I create further branches or tags.
- **GitHub**: I push everything to my private repository on GitHub, and create pull requests to merge generic changes in job-specific branches back into my generic CV branch.

This might sound like overkill, but it's been a game-changer. I can:

- Easily track changes and revert to previous versions.
- Maintain consistency across different job applications.
- Automate the PDF generation process.
- Write cv with vim

<https://www.linkedin.com/posts/kevin-cheung-278a32b4_jobsearch-git-versioncontrol-activity-7313876855516733440-9Cbz>

It's a continuous process of try and error, but I'm finally feeling in control of my job search.
