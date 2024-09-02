Github group test used. The procedure for resolving github conflict in group test was referenced from [codingnoona](https://www.youtube.com/@user-yu8so2ck1z).
--------------------------------------------------------------------------------

## Group project with Github

#### Git conflict feature A and B
step 1. Get the latest code in the develop branch<br/>
```git checkout develop``` ```git pull origin develop```<br/><br/>
step 2. Go back to the feature A branch<br/>
```git checkout -```<br/><br/>
step 3. Merge the feature A branch with the develop branch<br/>
```git merge develop``` and after discussing, Accept Both Changes<br/><br/>
step 4. Resolve the code conflict and repost the completed code<br/>
```git add .``` ```git commit -m "resolve conflict"``` ```git push```<br/><br/>
step 5. Receive code review again and merge (pull request merge)<br/>