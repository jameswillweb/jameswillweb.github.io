---
layout: post
title:  "Learning Github"
date:   2014-03-26
tags: [git, web design, github]
description: When I first started learning Github I kept running into frustrating roadblocks. It seemed like every tutorial I took, or article I read, assumed I was a developer and used terms and terminology that I just wasn't familiar with. Perhaps worse than that, because certain things were assumed it would often halt my learning process because I wouldn't understand how to fill in the blanks between steps.
---

When I first started learning Github I kept running into frustrating roadblocks. It seemed like every tutorial I took, or article I read, assumed I was a developer and used terms and terminology that I just wasn't familiar with. Perhaps worse than that, because certain things were assumed it would often halt my learning process because I wouldn't understand how to fill in the blanks between steps. I decided to jump in headfirst, make lots of mistakes, and research things that as a designer I wasn't really that interested in. I channeled all of those lessons into my Github for Web Designers course, and I decided to pull this blog post from the companion reference site to highlight some of the things I found useful when learning Github. If you want to learn more about the course check it out on [lynda.com](https://www.lynda.com/GitHub-tutorials/GitHub-Web-Designers/162276-2.html "Github for web designers") or check out the companion repository on [Github](https://github.com/jameswillweb/github-for-web-designers "Github for web designers repo").

### Stuff I learned

Whenever I learn something new I have those "aha” moments where I break through the murk into moments of clarity. In addition to the reference and glossary that you’ll find here I wanted to list some of the concepts that I found really important when learning Github.

#### Take some time to learn Git

I'll admit it; when I first started learning Github my hope was that it would provide me an interface to do all the things I needed to do without actually having to learn Git. While most of the basic day to day tasks can be performed without ever going into the command line or even understanding the terminology involved, eventually you'll have a situation that you can't fix. Save yourself the trouble and go ahead and learn at least the basics of Git first. I consider this so important that I changed the structure of my course to reflect this; spending a chapter at the beginning of the course teaching those basics. Although you can certainly muddle along it's almost impossible to use Github to its fullest potential without also knowing Git. The desktop apps are great and very intuitive but they have limited feature sets and don't really try to teach you what's going on behind the scenes.

#### Understand what is meant by "distributed"

Git is a distributed version control system, meaning that all copies of the repositories are local. Here are some highligts that you should take away.

No central repository 

: All copies of it are local and can update other copies

Doesn’t create multiple copies of files

: Git maintains a single directory structure. "Snapshots" are taken of projects as they progress to save history states.

You can branch snapshots to create infinite project variations. 

: Branching is incredibly powerful and allows you to create several different versions of your project without disturbing the history of the main project.

#### The concept of staged files

This one was tricky for me at first. I assumed that most version control systems automatically tracked and versioned files. That's not how Git works, in Git you have to first stage a file in order to include it in the next snapshot, referred to as a commit.

Files aren’t added to commits automatically 

: You have to add files manually in order for them to be committed in the next snapshot. This adds a little bit more manual labor to the process, but also gives you much more control over how and when things are recorded.

Staged files are ‘frozen’ once staged 

: If you update a file once it's been staged, the staged version of it doesn't record this. In order to make sure that the most recent changes are committed you'll need to restage the file.

You can un-stage files 

: If you decide that you've made a mistake, it's very easy to un-stage a file so that it's not included in the next commit.

#### How important Branching is

As a designer the ability to branch off from your main project, experiment or refine, and then return back to your main project and merge in those changes is fantastic. No more will I create 15 versions of the same file, or multiple directories of the same project nested inside each other. With branching I can simply create a new branch do what I need to do and then decide whether or not I want to keep or get rid of the changes I've made. It's an incredibly liberating way to work and I would encourage you to learn as much as you can about how branching and merging work.

Branches give you flexibility 

: Branches allow for simultaneous development, experimentation, and error fixing without disturbing the stable version.

You can keep them private

: Branches are private, meaning they’re not uploaded to Github unless you want them to be.

Understanding merging is key 

: You need to spend time learning how merging works, I mean **really** understanding it so that you know what to expect when merging branches.

Develop a workflow pattern for branching 

: If you don’t things can get messy fast. This is even more important in a team environment where you're working with multiple collaborators.

#### Github is a publishing platform

I kind of already knew this when I started learning Github since this was one of the reasons I really wanted to learn it. However, it's important to point out how evolved Github has become as a publishing platform.

Sharing projects publicly 

: Projects can be shared and distributed with the public without having to buy hosting or register a domain.

Collaborators from around the world can/may offer assistance 

: This is one of the coolest aspects. If you have a really great idea but lack skills in a certain area you can put the project up on Github and ask for assistance. The open source nature of the Github community means that you may get dozens or even hundreds of collaborators helping you with your project. Just keep in mind that open source means just that. You'll need to carefully research the licensing options and understand that you are releasing your project to the world.

Github Pages add polish 

: Github Pages allow you to host a basic site for your project. You can create your own or use their Jekyll template to generate pages. This blog, for example is hosted on Github Pages.

#### Clarity is important

There are many places in the Github workflow where you have to compose messages or descriptions for actions. I've learned the hard way that it's really important to be as descriptive as possible. Whether it’s writing the project’s readme file or making commit messages it’s critical that you write clearly and concisely. Not only for others but so that future-you understands it as well. 



