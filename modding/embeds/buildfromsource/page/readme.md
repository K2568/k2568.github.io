## Build a mod from source:
## Windows:
(I don't know anything about linux so idk if theres a difference in how to do this.) <br>
Make sure you have git cli installed. [Install here](https://git-scm.com/install/) <br>

Open a terminal (cmd on windows)

### Template:
"git clone repolink --branch branchname --single-branch" Keep in mind git clone can take a while depending on your internet speed.<br>
"cd reponame" <br>
"gradlew build" Keep in mind gradle can take a while as well.<br>
"cd build/libs" <br>
"explorer ." <br>
And then the jar should be there

### Example:
An example using the create repo <br>
![](https://raw.githubusercontent.com/K2568/k2568.github.io/refs/heads/main/modding/embeds/buildfromsource/createrepo.png) <br>
![](https://raw.githubusercontent.com/K2568/k2568.github.io/refs/heads/main/modding/embeds/buildfromsource/cmd1.png)
Then all the stuff gradle prints <br>
![](https://raw.githubusercontent.com/K2568/k2568.github.io/refs/heads/main/modding/embeds/buildfromsource/cmd2.png)

Text version: <br>
"git clone https://github.com/Creators-of-Create/Create --branch mc1.21.1/dev --single-branch" Keep in mind git clone can take a while depending on your internet speed.<br>
"cd Create" <br>
"gradlew build" Keep in mind gradle can take a while as well.<br>
"cd build/libs" <br>
"explorer ." <br>
And then the jar should be there