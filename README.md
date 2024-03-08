# Resume

This is a personal resume project hosted on GitHub Pages using the al-folio Jekyll theme. This document will provide instruction on how to host a resume with the exact same format.

## Getting Started

These instructions will give you a copy of the project up and running on
GitHub Pages, user site. To learn how to set up the project locally for setting purpose, please see [More Resources](#resources).

As mentioned Etter's book on modern technical writing, this is a way to host a document on a static page. Which is your resume in this case. By hosting it online, you do not have to worry about having to resend it to potential reader whenever you update.

## Prerequisites

To get started, the following are required:

- A working computer with Internet connection
- A pupolar browser, Chrome is recommended
- A GitHub account
- A bit of technical vocabulary about Git
- A Markdown resume

## Instruction

1) ### Log in to GitHub account
2) ### Go to the [repository](https://github.com/MinhPhan23/MinhPhan23.github.io)
   Preferably you are reading this document on the repository. 
3) ### Fork the repository
- Scroll to the top of your screen ![](InstrImg/ScrollUp.gif)
- Create a new repository name with the format `<github-username>.github.io` ![](InstrImg/fork.png)
- Click `Create fork`
- If the repository already exist, delete it and repeat step 3.
  
  This is what Etter meant by in the "Help Others Write" section in the book. GitHub or other version control is very powerful in collaboration in a project. When I make a project public on GitHub, every user can see it, and they can request to make changes through a procedure set up by me. With this everyone can contribute if they want, and this has been proven useful through a lot of other open-source project (public project).

4) ### Give `workflow permissions`
- Go to `Setting`
- Click on `Action` on the left panel
- Choose `General`
- Select `Allow all actions and reusable workflows` in `Actions permissions`
- Select `Read and write permissions` in `Workflow permissions` ![](InstrImg/ActionPerm.gif)
 
5) ### Modify the `_config.yml` file
- Click on the `_config.yml` file
- Click on the pen icon on the top right of the text
- Use the find command `command-F` and type in `baseurl`
- Find the text `baseurl`, make sure that it is empty
- Change the text at `url` to the format `https://<github-username>.github.io`
- Click on `Commit changes`
- Click on `Commit changes` again ![](InstrImg/changeConfig.gif) 

   `_config.yml` is the main file for `Jekyll`, one of the static site generators mentioned by Etters. Jekyll can have a large learning curve but easy to start and use nonetheless. Jekyll is popular for GitHub Pages because they have Jekyll built-in. Jekyll also have a big community and a variety of templates/themes you can choose like this one.

6) ### Build and deploy
   Wait 1-2 minutes for GitHub Pages to build and deploy

7) ### Go to Deployments
   ![](InstrImg/Deployment1.png)

8) ### Visit the site 
   ![](InstrImg/Deployment2.png)  
- Or goto `https://<github-username>.github.io`

## Customization

To replace the template with the content of your resume, goto `_pages -> about.md`, edit and paste in the content of your resume in Markdown.
![](InstrImg/customize.png)

<a id="resources"></a>
## More resources

- [Markdown tutorial](https://www.markdowntutorial.com/)
- [Jekyll tutorial](https://www.taniarascia.com/make-a-static-website-with-jekyll/)
- [GitHub tutorial](https://docs.github.com/en/get-started/start-your-journey/hello-world)
- [GitHub Pages tutorial](https://docs.github.com/en/pages/quickstart)
- The [README](https://github.com/alshedivat/al-folio/blob/master/README.md) from the author of this theme.

## Authors and Acknowledgements

- **Maruan** - *Provided Jekyll Theme* - [alshedivat](https://github.com/alshedivat)

See also the list of
[contributors](https://github.com/alshedivat/al-folio/graphs/contributors)
who participated in this project.

Dhairyah and Huzaifa for proof reading and suggestions for this README.

## FAQs

### Q: How to tell if my webpage is deploying?

A: By switching the branch to gh-pages, you can see the deploying process. It will be oranage when it is deploying, and like in picture when it is done.
![](InstrImg/deploy.png)


### Q: Why my page is not loading properly?

A: Make sure you are following step 5 in the instruction, the `baseurl` and `url` is where the browser getting all the resources it needs to render the page.

### Q: Why my GitHub Pages is not deploying?

A: Make sure you give the action permission mentioned in step 4.

## License

The theme is available as open source under the terms of the [MIT License](https://github.com/alshedivat/al-folio/blob/master/LICENSE).

Originally, **al-folio** was based on the [\*folio theme](https://github.com/bogoli/-folio) (published by [Lia Bogoev](https://liabogoev.com) and under the MIT license). Since then, it got a full re-write of the styles and many additional cool features.