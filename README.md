# Gitmob
In-repository bug tracking and code review for individual projects with a p2p backend.

Gitmob is in the planning stages and will need lots of help. Please contact me
if you would like to be brought onboard.

## Issues
* git is distributed, but everyone has to rely on a central server point to
  really get anything done.
    * no offline bug tracking standard
* need complex web based GUI's for internal and user facing bug tracking
* code review and user hierarchy isn't a focus in many of the major tracking/server software
  options

## Planned Features
* in-repository bug tracking
    * probably will use "separate branch" strategy
    * integrated bug fix with commit
    * tagging
    * robust data fields
    * flat text for everything
* secure transmission between peers
* per-project web-of-trust, user auth with gpg signoff?
* tor hidden service style web interface
    * member of the project? you route to the projectname address
        * OAuth and other flexible methods of web-based auth.
    * not member of project? you see the project web-page for site info/bug
      reporting
    * allow for anonymous "push request" style contributing
* auto adding of trusted peers as remote repositories
    * yet a virtual "origin" that is distributed throughout
* future ideas
    * export plugins
        * to other task managers? (RTM, trello, github, bitbucket)
        * gitmob repositories don't have to be unique or separate from say a github repository, it could just be a
        way for a focused team to make changes in solutude and then push back to a
        Github type site.
    * p2p chat interfaces
        * website and/or commandline
        * want the feel of joining a chat room
        * live notifications? design modularly (server/client format like tmux)
          for terminal multiplexors?
    * collaborative programming interface?
    * Code access rules for individuals

## Workflow

## Other
This could potentially be everything [gitchain](https://github.com/gitchain/gitchain) is but minus the "global storage" goal
they have. This just needs to be for individual projects.

## Lisence
Probably GNU v2, not sure yet.
