<html>

  <h2> Credential problems on swop from paswswords to keys </h2>
  to fix it so you can login to fit from command line, use:
  <pre>git config --global credential.helper store</pre>
  <br>Best is to ask to use it via browser...
  
  <br>
<h2>Since I use git only very rarely, I will add this to refresh my memory</h2>
<ol>
<li>Run <i>D:\Programs\PortableGit\zmlsetup</i> in your freshly created folder.
<li>Now do <i>git add <filename></i> , or git add *</i> to add files in the folder to the project
<li>Do a <i>git commit -m "Commit message"</i> every now and then
<li>Do a <i>git remote add origin https://github.com/faaktap/PROJECTNAME.git</i> once you see it's viable
<li>Do a <i>git push -u origin master</i> to get the files on the server..
</ol>

<ul>
<li>When all is gone, you can fetch a clean set by doing <i>git pull</i>
<li>or create a new folder and do <i>git clone faaktap@https://github.com/faaktap/startgit-setup</i>
</ul>


<pre> 2nd try - Jun 2020 
https://git-scm.com/book/en/v2/Getting-Started-Getting-Help

git config --global user.name "Fakie Tap"
git config --global user.email faaktap@gmail.com
git config --global core.editor "C:\Program Files\Notepad++\notepad++.exe"
git config --list

//store your username and password locally faaktap, ******
git config --global credential.helper store
<b>****
Easier is to </b>download gh (github CLI) and then type gh auth login on the command line


git help <verb>
git <verb> --help
like : git add -h

md testgit
cd testgit
git clone https://github.com/faaktap/sandbox.git

git status

echo 'My Project' > newfile.txt
git add newfile.txt

git status -s  (short explaination)

git commit 
or
git commit -m "Story 182: fix benchmarks for speed"
or
git commit -m "Test a quick commit"

git rm newfile.txt  (will delete the file from repository)

git log  (show activity)

create a file called .gitignore, and add stuff in to ignore.
Here is another example .gitignore file:
# ignore all .a files
*.a
# but do track lib.a, even though you're ignoring .a files above
!lib.a
# only ignore the TODO file in the current directory, not subdir/TODO
/TODO
# ignore all files in any directory named build
build/
# ignore doc/notes.txt, but not doc/server/arch.txt
doc/*.txt
# ignore all .pdf files in the doc/ directory and any of its subdirectories
doc/**/*.pdf



# New local repository
git init
git add .
git commit -m "Initial commit"

# New remote repository
# Create remote repository (likely on github), then:
git remote add origin https://github.com/username/new_repo #https
git remote add origin https://github.com/faaktap/dkhs.git
git remote add origin git@github.com:username/new_repo #ssh
# Now push
git push -u origin master



git add .
git commit -m "message for the commit"
git remote add origin https://github.com/faaktap/zmlShop
git push origin master

