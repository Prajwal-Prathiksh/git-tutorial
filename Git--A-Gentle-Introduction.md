---
marp: true
theme: gaia
class: invert
# paginate: true
math: mathjax
---

![bg left:40% 80%](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2b/Git-logo-white.svg/1024px-Git-logo-white.svg.png)

# **The Heck Is That? :thinking:**

*Expect only the most midwitted answers :)*

---


# It's a version control system!
![bg right:40% 80%](https://img.devrant.com/devrant/rant/r_2329045_c5v7p.jpg)

* **The heck is that now!**
* <span style="color:#80d9f3">Put simply: *It's a time-machine for your code!*</span>
* **Okay now give me a real answer!**
* <span style="color:#80d9f3">Hmmmmmm........</span>

---

# Okay here's the real answer
![bg left:40% 80%](https://www.nobledesktop.com/image/gitresources/git-branches-merge.png)

* *Git is a <span style="color:yellow">distributed</span> <span style="color:orange">version control system</span>*
* <span style="color:yellow">Distributed</span> $\Rightarrow$ Everyone has a full copy of the repo
* <span style="color:orange">Version control system</span> $\Rightarrow$ Keeps track of changes in code

---

# Why should I care?
*(Part 1: I wanna go back in time)*

* Damn I think I broke something by adding some code...
  * **No problem!** Just `revert` back to the last working version
  
* `git revert HEAD` $\Rightarrow$ Revert to the last commit
* `git revert HEAD~2` $\Rightarrow$ Revert two commits back
* `git diff HEAD HEAD~2` $\Rightarrow$ See the changes between the last two commits

---

# Why should I care?
*(Part 2: I wanna try something new)*

* I want to experiment with some new features but don't want to mess up the main code...
  * **No problem!** Just create a new branch and work on that

* `git branch feat-new` $\Rightarrow$ Create a new branch called `feat-new`
* `git checkout feat-new` $\Rightarrow$ Switch to the `feat-new` branch
* `git checkout main` $\Rightarrow$ Switch back to the main branch
* `git merge feat-new` $\Rightarrow$ Merge `feat-new` branch into `main`


---

# Why should I care?
*(Part 3: I wanna make my own changes)*

* Hey I see this cool project on GitHub, but I need to make some changes for my own use...
  * **No problem!** Just fork the repo and make your changes
  