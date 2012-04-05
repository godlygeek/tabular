tabular.vim
===========
Intro
-----
Remember the good old days when indenting things which 
started beyond the beginning of a line needed to be done 
one line at a time?  Welcome to the future where entire 
block are now able to have indentations applied with a single
command!

    title : Jekyll Bootstrap
    tagline: Site Tagline
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username
      feedburner : feedname

Now can be cleaned up simply by calling `Tabularize/:` formating to:

    title        : Jekyll Bootstrap
    tagline      : Site Tagline
    author       :
      name       : Name Lastname
      email      : blah@email.test
      github     : username
      twitter    : username
      feedburner : feedname

Installation
------------
If you don't have a preferred installation method, I recommend
installing [pathogen.vim](https://github.com/tpope/vim-pathogen), and
then simply copy and paste:

    cd ~/.vim/bundle
    git clone git://github.com/rudolph9/vim-tabularize.git

Once help tags have been generated, you can view the manual with
`:help tabularize`.