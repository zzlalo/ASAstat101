# Setting up a course web site

As statistics instructors start using data in their classes, they find that they need to make data files available to students. An excellent way to do that is to put the files on a web site, so that the students can access them with a URL, for instance, `https://dtkaplan.github.io/stat101/test.csv`.

Many instructors don't have a web server available to them and aren't sure how to set up a web site. The point of this repository is to help you set up your own course web site on which you can place data files, etc. so that your students can easily get to them.

You don't need to know even what a "repository" is. You'll be able to add files to your web site and edit documents from an ordinary brower.

The main resource we'll use is called *GitHub*. This is a free service that's very widely used by software engineers. We won't have to do any engineering, but you'll have to follow a few instructors.

## Setting up your web site

Right now you are looking at a tab in your browser. For the sake of clarity, let's call this "Danny's Github Tab." You're going to need to open another tab in your browser, which we'll call the "Second Tab." You will want to have both tabs available to you so that you can go back and forth.

1. You will need a GitHub account. You just have to set this up once, and it's the same kind of thing as you do all the time when you set up a new account on some service.
    - Point the "Second Tab" to `github.com`. You'll get a page like the following. 
    
    ![](make-account.png)
    
    Go ahead and make an account. Some tips:
        * GitHub is very popular, so your first choice of account name may not be available. Whatever you choose, make it short and professional. For instance, **don't** use an account name like `party_guy`. If you do, you will find your students having to refer to URLs like `party_guy.github.io/stat101/exam_data.csv`, which they might not take very seriously.
        * Make sure to keep track of your account name. You're going to be needing it often.
        
    Now that you have a GitHub account ...
2. Go back to Danny's GitHub Tab, that is, the tab where you are reading this text. Near the top of this page, you'll see buttons etc that look like this:
![](fork.png)

    - Press the "Fork" button. When you do this, you will likely be asked to login to GitHub. Fortunately, you just made your account ID and password, so it will be easy to remember them.
    - After you've signed in, you'll likely be put back on the page with the "fork" button. Press it again. You'll get a message saying that your copy of the repository is being created. After that, you'll probably be looking at a page that looks just like Danny's GitHub Tab, but which has your account name instead of `dtkaplan`.
    
    What you've now accomplished is to set up your own "repository" which contains your new web site. But the site is not yet activated, so we'll need to do that first.
    
3. Notice some things about the web page you are looking at. First, the URL of that page will be `github.com/`*your_user_ID*`/stat101`. Second the top of the page will look like this (except it won't say `dtkaplan`, it will have your own GitHub ID):

    ![](settings.png)
    
    * One of the tabs *within* the page is called "Settings." Go there.
    
4. Right near the top of the Settings tab is a label "Repository Name." The box will contain `stat101`. Change this to something that's suitable for your own course. Keep the name short and don't put any spaces in the name. If your course is actually called "Stat101", then you can keep the name. Otherwise change it to "Math2330" or "Stat10" or whatever is appropriate. Press the "Rename" button.
5. Stay on the "Settings" tab, but scroll down until you see a section that looks like this:

    ![](gh-pages.png)
    
Yours will be a little different. In particular, in the place where the image above says "Master Branch /docs folder," your page will say "None." Change the "None" to "Master Branch /docs folder" and press save.

Congratulations! Your web site is now created! The address of your new web site will be displayed just above the "Master Branch /docs folder" button. It will be something like `https://dtkaplan.github.io/stat101`, but with your own user ID and course name.

## How things work

