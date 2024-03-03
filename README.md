# New Posters for FsInf

This repository contains posters that will be printed and used to redecorate
the wall the the FsInf rooms (@TUWien).

## Structure

The structure in the projects is as followed:

```
.
├── poster1/
│   ├── README.md
│   ├── poster.pdf
│   ├── poster.kra
│   └── something.ink
├── poster2/
│   ├── README.md
│   ├── poster.pdf
│   └── poster.ink
├── how_to_be_a_cat/
│   ├── README.md
│   ├── poster.pdf
│   ├── main_cat.gimp
│   └── cat.png
└── ...
```

The top level folder eg `how_to_be_a_cat` should be the name of the poster.
This folder must contain the following required files:

- README.md
- poster.pdf

The `README.md` should explain what program needs to be used to open the posters raw files. An image of the finished poster. Additional info that could be helpful would also be highly appriciated. The readme can also contain information about the author and when it was created, but this is optional.

The `poster.pdf` should be in A2 format with the colorspace CMYK (needed by the printshop). If possible the pdf standard should be `PDF/X-3:2002`. Make sure the resolutionn is high enough, but no so high that it takes 2 hours to open the image. If for some reason PDF-export is not an option then TIF (`poster.tif`) or JPG (`poster.jpg`) can also be used (both in CMYK).

All other files in this folder should be the raw files that are needed to edit or reexport the poster.

For examples you may look at existing folders.

## Rules for Poster

Some no-goes for posters:

- Keep it SFW (safe for work)
- No-discrimination

If you are unsure if your poster idea breaks the rules you can ask someone at mattermost [poster-creation-channel](https://mattermost.fsinf.at/fsinf/channels/poster-creation). (You can only post there if you are a student at TUWien)

## Communication

The main communication channel besides GitHub is on Mattermost in the [poster-creation-channel](https://mattermost.fsinf.at/fsinf/channels/poster-creation) (You can only post there if you are a student at TUWien)

In this channel one can ask questions on how poster are created, discuss questions or share knowledge.

## Contribute

If you want to contribute then you can do so in the following ways:

### Submit new poster ideas

If you want to submit a new poster idea you can do so by creating a new issue for this repository. The issue should have an short and informative name that makes it clear what the poster is about. Each issue should also contain a description with more details that can be used by others to design the poster. For examples look below or at the already existing issues. The issue should also have the label `poster idea`.

```
Title: How to use git

Description:
This poster should contain the most used git command and what they do:
* git add
* git commit
* git push
* git pull
* git clone

If there is still some space left it could contain examples or reasons why git should be used.
```

### Create a poster

If you want to create a new poster you can do so by first forking the repository to your own account. Make sure that an issue exists for the poster idea, if not just create one (see above). After that, create the poster and commit it to your forked repository. If you are finished make sure that all the required files exists and then you can create a pull request on the fsinf repository to get your changes back into the main repository. The pull request should mention the poster issue for which the poster was created. It would also be nice to attach some images of the created poster inside the pull request.

Here is an example pull request:

#TODO (insert image)

If you don't know how to fork a repository and create a pull request you can watch this video: [GitHub Pull Request in 100 Seconds](https://www.youtube.com/watch?v=8lGpZkjnkt4)

## I have no idea what git is and how to use it.

This section is for all those who have never used it and have no idea on how any of this works. If you think git is overly complicated and you don't need to use it the first consider the following:

- You will need to use it in multiple project at the university.
- If you learn it know it will make the subject where you need to use it somewhat easier.
- It prevents you from losing code due to overwriting it.
- You can always go back to a previous version.
- It makes collaberating easier.
- Almost all open source projects use it.

There are two main ways to use git. You can either use it via the CLI or via a GUI application. The GUI application has an easier onboarding process and most of the times you can start using git right away. The CLI version is a bit harder to learn but gives you more fine grained control over what happens. Another point to consider is that it is more likely to have the git CLI version on system then a specific GUI application.

Git CLI Tutorials

- [Git + Github Tutorial (Youtube 12min)](https://www.youtube.com/watch?v=HkdAHXoRtos)
- [Git Tutorial (Youtube 1h)](https://youtu.be/8JJ101D3knE)
- [Git Book](https://git-scm.com/book/en/v2)

Git GUIs

- [GitButler (Linux & Mac)](https://gitbutler.com/)
- [Git in VsCode (Linux & Mac & Windows)](https://code.visualstudio.com/docs/sourcecontrol/overview)
- [GitHub Desktop (Linux & Mac & Windows)](https://desktop.github.com/)

## Authors

<a href="https://github.com/fsinf/poster/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=fsinf/poster" />
</a>
