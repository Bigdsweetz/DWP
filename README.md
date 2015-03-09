*Douglas Jay Sweeting II*

*DWP*

*Portfolio Deployment Plan*



**This is the portfolio of Douglas J. Sweeting II. Any and all changes should following the below listed guidelines.** 


## The plan for Deployment
1. Making any changes
2. Check for errors
3. Updating and committing
4. Merging changes 
5. Version control
5. Pushing to the test server



# 1.  Making Changes #
1. Changes can be done with any editor of your choosing.
2. Changes can **NOT** be saved unless properly documented as to avoid confusion

# 2.  Check For Conflicts #
1.  Type **git checkout master** and the press *Enter* 
2.  Next, type **git pull** *remoteRepo* **master** and then press *Enter*
3. In the even of any errors ~~because there are never errors~~ Fix what you broke, commit accordingly and pull again

# 3.Updating and committing#
1.  Type **git add -A** and *Enter*
2.  Type **git commit -am ' _Something helpful_ '** and press *Enter*
3.  Type **git pull _remoteRepo_ master** and then press *Enter*

# 4. Merging #
1.  Type **git merge** *changeName*
a. If there are any errors, please make the neccessary changes to remedy any issues.   
2.  Type **git push _remoteRepo_ master** and *Enter*	

# 5. Version control #
1.  Type **git tag -a v** *Ma.Mi.R* **-m** *'name of code* and press *Enter*'
- Version numbering system: Major Version.Minor Version.Revision
2.  Type **git push** *remoteRepo* **--tags**

# 6.  Test Server  #
1.  Notify the team via agreed upon messeging service of projected upload to server.
2.  Type **git push** *staging server* **master**
3.  Iron out **ANY** issues we ran into.
4.  Test again.

    a. In the event that we continue to run into issues. There currently 2 COA (courses of Action) to take
        I.  In the event of a major issue. We will go back to step 2 in the process and work accordingly
        II. In the event of a minor issue. We will attempt this a total of 3 times (Baseball rules here)

5.  Promote to Production