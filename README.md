# DataVersioningViaDVC

DVC — Short Notes
DVC → Large datasets/models ko version control karne ke liye.
dvc add data → dataset ko DVC se track karta hai.
Isse data.dvc file banti hai.
data.dvc mein actual data nahi hota, sirf dataset ka metadata + hash hota hai.
Actual dataset DVC storage mein hota hai.
Dataset change → dvc add data → data.dvc ka hash update.
data.dvc ko Git mein commit karte hain.
Git history se old data.dvc version mil sakta hai.
dvc checkout → corresponding old dataset restore karta hai.
Remember 🔥

Git → Code + data.dvc

DVC → Actual Dataset

data.dvc → Dataset version ka pointer/metadata



git log --oneline
git checkout <hash> - git checkout master
dvc pull