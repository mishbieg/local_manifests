# local_manifests
Local manifests for the android products I maintain

To apply a local_manifest go to the .repo/local manifests folder within your android folder.<br/>
Add a new empty repo: git init<br/>
git remote add origin https://github.com/mishbieg/local_manifests.git<br/>
git fetch origin<br/>
git checkout -b master --track origin/master<br/>
git checkout -b <branch> --track origin/<branch><br/>
e.g. git checkout -b onyx/lineage-16.0 --track origin/lineage-16.0
