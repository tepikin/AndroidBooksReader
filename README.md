![Logo](https://raw.githubusercontent.com/foobnix/LirbiReader/master/logo.jpg)

# Android Studio Project for build "Librera Reader"

For build project
1) Checkout project **with git submodules**.  (git clone <b>*`--recursive`*</b>)
2) Execute `gradlew installRelease`
3) That's all :)

Console commands:

> `> git clone`**`--recursive`**`"https://github.com/tepikin/AndroidBooksReader.git"`<br>
> `> cd AndroidBooksReader`<br>
> `> gradlew assemble`<br>


# How to update the version of "Librera Reader" for build

##### Method 1 
Just copy the new version of the "Librera Reader" repository in the **"submodule_LibreraReader"** folder. That's all :)

##### Method 2
Update the link of the git submodule to another repository or version.<br>
For that edit the `.gitmodules` file to update the URL and then run `git submodule sync` to reflect that change to the superproject and your working copy. Now you can switch to any version of the selected repository as usual using "git checkout".
