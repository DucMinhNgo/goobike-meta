git submodule add https://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@github.com/DucMinhNgo/goobike-mobile.git goobikebackend
git submodule add https://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@github.com/DucMinhNgo/goobike-backend.git goobike-backend
git submodule add https://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@github.com/DucMinhNgo/goobike-admin.git goobike-admin

# Remove
git rm -rf goobike-admin rm -rf .git/modules/goobike-admin

# Pull child repo
git submodule update --init --recursive git submodule update --recursive --remote