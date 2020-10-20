# Playlister

Playlister is a YouTube Video Playlist app for users to keep track of their favorite songs and videos and share them with friends. 

## Installation

1.  Clone this repo 

        $ cd <location where you would like repo stored>
        $ git clone https://github.com/ellojess/playlister.git


2. Make sure it is setup correctly 

        $ git remote -v
        
You should see: 

          origin    https://github.com/ellojess/playlister.git (fetch)
          origin    https://github.com/ellojess/playlister.git (push)

3. Create your own branch to make edits on 

        $ git checkout -b <your name AND/OR feature>
        
4. Set upstream 

        $  git push --set-upstream origin <branch name you setup in step 3 above>


After you setup upstream you should be able to push as you normally would through terminal or Xcode.

After you push, go to this repo and submit a pull request when you're ready


### User Stories 

1. Users can view all playlists (index)
2. Users can create a playlist (new/create)
3. Users can view one playlist (show)
4. Users can delete a playlist (destroy)
5. Users can edit a playlist (edit/update)
6. Users can comment on playlists (comments#create)
7. Users can delete comments (comments#destroy)
