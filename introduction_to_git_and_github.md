#Introduction to Git and GitHub

##Presented by UC CompSoc


NB: This is designed to be a self directed learning experience. Below are topics to get you started.


<hr>

####What is Source Control and Why should I use it?

Source control is an important software engineering process whereby code is stored in many incremental changes. This allows for back ups, rollbacks, patches, branching, forking and sharing code. 

These features give you incredible power as a team of developer or even as a solo developer. The tools give you power over your code base like you've never had before.


[Git](http://git-scm.com/), is a [distributed version control system](http://en.wikipedia.org/wiki/Distributed_revision_control) and is probaly the most polular implementations to date. The other most well known and well used one is [Mercurial](http://mercurial.selenic.com/).


Git and Mercurial are known as distributed (we'll cover what this means later on) compared to centralised systems, such as SVN, which you may have heard of. 



####Concepts of Git


The concepts of Git are similar to those of Mercurial and SVN. The first concept to learn is that of a *repository*. *Repositories* are simply folders on your computer with a bit of extra information added to them. In these reposistories, goes your code, assets, or whatever you like! The second is that of *server*. The server maintains its own copy of the reposistory, and you can send or get back code from the server.


Moving code back and to a server is important, but first I'll explain how you get your code in the repository. Once your code is added, you can make what is called a *commit*. A *commit* is a change in code. Each commit has an author, a time, a unique identifier, and what code it changed. This may also include file deletions or additions. What is neat about a commit, is that it doesn't make a copy of the new file (as you might if you were doing your own system by making many files called CODE-OLD, CODE-OLD-2, CODE-OLD-3), instead it stores only the changes. At any point in time, you can go back to a commit and the system itself will create the file at that point by doing the reverse of the commits before it to that file. Neato!

So that's repositories and commits. Now, how do we get out code to the server? After a commit, we can do what is called a push. Pushes allow us to put the changes from our repository to the server. Pulls, do the opposite, they bring code from the server to your computer. Question: What happens if the code on the server changes since the last time you pulled before you push? 

Other concepts in git include branching, basing, tagging, etc. You'll learn more [in the git tutorial hosted by GitHub](https://try.github.io/levels/1/challenges/1). This should take you about 15-20 minutes, come back here once you're done

<hr> 

####What is GitHub?

By now you should be familiar with the fact that Git  requires a server to share code between people. Where do I get a server? Well, GitHub is that server (and much more!!!).


####Getting started on GitHub. 


Go to [here](https://education.github.com/discount_requests/new) to sign up for an account. Select student, Individual account. Sign up with your `abc123@uclive.ac.nz` or `first.last@canterbury.ac.nz` account, which CompSoc has [organised to be whitelisted for you](https://github.com/leereilly/swot/pull/50). 

At this point, come tell us your Github username and we'll give you a free GitHub sticker of your choosing.

After that, go [here](https://guides.github.com/) to start learning more! 


Tonight we'd like to see you do the following

    * Create a repository
    * Comit a small project, in any language (This could be simple as hello world in Python)
    * Share the repository
    * Accept a pull request from the person sitting next to you, or a friend
    * Find an open source project to try contribute to.
    
    
GitHub is all about social coding. Sharing and caring for code. If anything, we'd like to you 'get' that tonight. 
   
   
CompSoc would also like to start a list of projects worked on or started by CompSoc members. Please submit your project and username [here](https://docs.google.com/forms/d/1NBLaxEsGvsLP6691tKV5YnswwU6w8XDuT5F7rjNBmLQ/viewform)
    
Any questions, red flag up and we might be able to help! There will be Pizza around 6-6.30. 

Good luck! </br>
CompSoc




