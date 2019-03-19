There are several ways to get shortened links. I will explain two of them.

1. Github Pages. Here is how to get it setup for link shortening:
-Create a new Github repo
-Don't add a readme, gitignore,or license
-CLick Create a New File
-Name it "index.html"
-type in:
<!DOCTYPE html>
<html>
<head>
<meta http-equiv="refresh" content="0; URL='your link'" />
</head>
</html>
-Commit the file
-Go to settings
-Go down to the Github Pages section
-Under Source change it to master branch
-Click change theme and choose whatever theme you want
-Go into the _config.yml file and click edit
-Underneath theme type "title:" and put a title that you would like
-Underneath title type "description:" and put a description that you would like
-you should now be able to visit your site from https://<username>.github.io/<reponame>

2. bitly. Here is how to get a shortened link with bitly:
-go to bitly.com
-click on the text box
-paste your link
-copy the shortened link
