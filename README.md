# Local Respository

Iniatialise as a git repository with:
git init

add and commit as usual

but push origin won't work as there is no reference repo to push into.
Instead create an online empty repo with same name on GitHub. Then use:
git remote add origin (link)

check using:
git remote -v

Pushing now works, add upstream to set the push path as default, so in future just 'git push' would work. By:
git push -u origin main