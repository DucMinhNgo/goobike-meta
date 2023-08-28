git submodule add https://github.com/DucMinhNgo/goobike-mobile.git goobike-mobile
git submodule add https://github.com/DucMinhNgo/goobike-backend.git goobike-backend
git submodule add https://github.com/DucMinhNgo/goobike-admin.git goobike-admin

# Remove
git rm -rf goobike-admin 
rm -rf .git/modules/goobike-admin

git rm -rf goobike-mobile 
rm -rf .git/modules/goobike-mobile

git rm -rf goobike-backend 
rm -rf .git/modules/goobike-backend

# Pull child repo
git submodule update --init --recursive git submodule update --recursive --remote
git submodule update --init --recursive --remote
