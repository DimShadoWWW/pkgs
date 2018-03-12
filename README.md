### npm2PKGBUILD

Transform an npm package into an Arch Linux `PKGBUILD`

    npm2PKGBUILD $NPM_NAME > PKGBUILD
    makepkg
    pacman -U nodejs-$NPM_NAME-$VERSION-any.pkg.tar.xz


### npm2aurball

Transform an npm package into an AUR tarball using `mkaurball`

    npm2aurball $NPM_NAME


### npm2archpkg

Transform an npm package into an Arch Linux package archive

    npm2archpkg $NPM_NAME
    pacman -U nodejs-$NPM_NAME-$VERSION-any.pkg.tar.xz


### npm2archinstall

Install an npm package with pacman

    npm2archinstall $NPM_NAME


