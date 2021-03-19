**Benifits of This Day:[14/12/2020]**

_Bash Commands:_

- ls --> list of files
- ls -a --> list of all files with hidden one
- ls -l --> more details
- mkdir --> create folder
- cd --> go to directory
- cd .. --> go back one level
- pwd --> get working directory
- tree --> whole device directory
- touch --> create file
- clear --> clear logs
- cp -r file path to folder --> cope files to new path
  - man cp --> for help
- mv path path --> for cut
- mv oldFileName newFileName --> to rename without moving
  - man mv --> for help

---

_Git commands:_

- git init --> create git working environment
- git clone --> clone project from repo link
- git status --> show tracked and untracked files
- git commit -a --> commit all files
- git commit -m "message" --> commit with message
- git remote add origin <https://github.com/>....... --> add remote repo
- git remote -v --> see all remotes
- git fetch [remote-name] --> get all new changes from the repo (pull down) Use: [git fetch origin]
- git push [remote-name][branch-name] --> push changing to the repo [git push origin master] || [git push origin main]
- git add . --> add changes and tracking to the staged place
- git pull --> fetch and merge all repo changes
  - git pull origin main
- git checkout -b debug --> create and switch to a new branch
- git checkout original main
  called debug
  - _equal to:_
    - git branch debug
    - git checkout debug
  - git checkout -b iss35 --> create a new branch called 'iss35' and switch to it
  - git checkout main --> switch to main branch
  - git merge iss35 --> merge iss35 with main
  - git branch -d iss35 --> delete 'iss35' branch

---

_Html:_

- _Html Tags:_

  - <html></html>
  - <body></body>
  - <head></head>
      * <title></title>
      * <meta name="description, keywords, robots" http-equiv="author, pragma, expires" content="" /> --> for each name or http-equiv get different content
      * <link rel="stylesheet" href="css/styles.css" type="text/css" />
      * <script src=""></script>
      * <style type="text/css"></style>
  - <p></p>
      * <p lang="en-us"></p> --> if text in english
  - <h1></h1> --> to <h6> gonna smaller
  - <ul></ul>
      * <li></li>
  - <b></b> --> (inline)
  - <i></i>
  - <strong></strong> --> Meaningfull
  - <main></main> --> Meaningfull
  - <article></article> --> Meaningfull
  - <section></section> --> Meaningfull
  - <header></header> --> Meaningfull
  - <footer></footer> --> Meaningfull
      * &copy; --> copy right
  - <select></select>
    - <option></option>
  - <input></input>
  - <img src="" alt=""></img> --> (inline)
  - <aside></aside> --> Meaningfull [side bar]
  - <a href="" target="" class="current" id=""></a> --> (inline)
  - <figure></figure> --> Meaningfull [image with quote or description]
      * <img></img>
      * <figcaption></figcaption>
  - <hgroup></hgroup> --> Meaningfull [headers group h1, h3, ...]
      + <h1></h1>
  - <div></div>
  - <!-- .wrapper --> ==> html comment
  - <em></em> --> emfasize (inline)

  * <span></span> --> group elements (inline)
  * <iframe src="http://maps.google.co.uk/maps?q=moma+new+york&amp;output=embed" width="450" height="350" frameborder="0" scrolling="no"></iframe> --> open a new section in the site like: map or another site, [seamless like scrolling does not allow scroll but for html5]
  * <></>

- _Html Design:_

  - Design the Wireframe for the site first.
  - Draw Site Mape
  - block and inline elements

- _Html older browsers:_

  - header, section, footer, aside, nav, article, figure {display: block;}
  - <!--[if lt IE 9]> <script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script> <![endif]-->

- _Html Escape Characters:_

  - &copy;
  - &reg;
  - &trade;

- _Html Page:_
  [index.html](https://mohammad-nour-rezek.github.io/Reading-Notes/Client/index.html)

---

[Return to Home Page](https://mohammad-nour-rezek.github.io/Reading-Notes/)
