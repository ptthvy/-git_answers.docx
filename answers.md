jupyter-24100439@st.phenik-12c28@jupyter-virtual-machine:~$ mkdir git-lab
jupyter-24100439@st.phenik-12c28@jupyter-virtual-machine:~$ cd git-lab
jupyter-24100439@st.phenik-12c28@jupyter-virtual-machine:~/git-lab$ git --version
git version 2.34.1
jupyter-24100439@st.phenik-12c28@jupyter-virtual-machine:~/git-lab$ git config --global user.name "Pham Thao Hien Vy"
jupyter-24100439@st.phenik-12c28@jupyter-virtual-machine:~/git-lab$ git config --global user.email "24100439@st.phenikaa-uni.edu.vn"
jupyter-24100439@st.phenik-12c28@jupyter-virtual-machine:~/git-lab$ git config --list
user.name=Pham Thao Hien Vy
user.email=24100439@st.phenikaa-uni.edu.vn
use.name=Pham Thao Hien Vy
use.email=24100439@st.phenikaa-uni.edu.vn
credential.helper=cache
GIT-ADD(1)                                               Git Manual                                               GIT-ADD(1)

NAME
       git-add - Add file contents to the index

SYNOPSIS
       git add [--verbose | -v] [--dry-run | -n] [--force | -f] [--interactive | -i] [--patch | -p]
                 [--edit | -e] [--[no-]all | --[no-]ignore-removal | [--update | -u]] [--sparse]
                 [--intent-to-add | -N] [--refresh] [--ignore-errors] [--ignore-missing] [--renormalize]
                 [--chmod=(+|-)x] [--pathspec-from-file=<file> [--pathspec-file-nul]]
                 [--] [<pathspec>...]
                 jupyter-24100439@st.phenik-12c28@jupyter-virtual-machine:~/git-lab/git-lab/README.md$ vi README.md
jupyter-24100439@st.phenik-12c28@jupyter-virtual-machine:~/git-lab/git-lab/README.md$ git status

On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ./

nothing added to commit but untracked files present (use "git add" to track)
