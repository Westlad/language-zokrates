# ZoKrates language support in Atom
 - clone https://github.com/Westlad/language-zokrates then (in the cloned repo root dir)
 - npm install electron-rebuild
 - npm install
 - $(npm bin)/electron-rebuild -v x.y.z
 - apm link

Then restart atom

In step 5 replace x.y.z with the current version of Electron that Atom is using (go to 'about' in the menu then click on 'more details' in the window that pops up to find the current electron version.  You will need to re-run 5 every time Atom moves to a new Electron version.
