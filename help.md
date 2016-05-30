**May 30, 2016 (Ki H. Lee)**

GitHub: An open source version control system. Git is version control
software that runs at the heart of GitHub. GitHub provides two things:
GitHub Desktop (manage the individual version-controlled projects on the
local computer) and GitHub.com (bring the local version-controlled
projects to the Web).

<https://help.github.com/articles/set-up-git/>

1.  ### GitHub Setting Environment

    1.  **Staging**

    <!-- -->

    1.  ### Create a GitHub account

        Create GitHub account: <https://github.com/>.

    <!-- -->

    a.  To make your mail private, in the top right corner of any page,
        click “Settings”. It will open “Personal settings”, then choose
        Emails and click “**Keep my email address private**”.

    <!-- -->

    1.  ### Install GitHub Desktop

        Download and install GitHub Desktop:
        <https://desktop.github.com/>. This will automatically install
        Git and keep it up-to-date for you.

-   Please refer to:
    <https://help.github.com/desktop/guides/getting-started/>.

-   To access GitHub online repository, Git commit identifies with an
    email address: Setting Git to use the private GitHube email address.

a.  On your computer, open the **Git Shell** application.

b.  Tell Git your *name* so your commits will be properly labeled.

    \$ git config --global user.name &lt;name&gt;

c.  Tell Git the *email address* that will be associated with your
    > Git commits. The email you specify should be the same one found in
    > your [email
    > settings](https://help.github.com/articles/adding-an-email-address-to-your-github-account/).
    > To keep your email address hidden, see "[Keeping your email
    > address
    > private](https://help.github.com/articles/keeping-your-email-address-private)".

> \$ git config --global user.email &lt;email&gt;

### GitHub

2-1. Create your online Repository.

### Authenticating with GitHub from Git

1)  In order to connect to a GitHub repository from Git, connecting over
    > HTTPS (recommended) : When you view a repository while signed in
    > to your account, the URLs you can use to clone the project onto
    > your computer are available below the repository details:

> ![](media/image1.png){width="4.21875in" height="2.1979166666666665in"}

### Basic Git Commands

Open the **Git Shell**  from [GitHub
Desktop](https://desktop.github.com/).

1)  git help command

\$ git --help

1)  Setting up a repository

> \$ git init &lt;directory&gt; : Transform the current directory into a
> Git repository. This adds a .git folder to the current directory and
> makes it possible to start recording revisions of the project.

EX) \$ cd path/above/repo

\$ git init --bare my-project.git

> \$ git clone &lt;repo&gt;: Clone the repository located at
> &lt;repo&gt; onto the local machine. &lt;repo&gt; will be copied from
> GitHub repository.

EX) \$ git clone <https://github.com/kihlee/my-project.git>

\$ cd my-project \# Start working on the project

1)  Saving changes

    \$ git add &lt;directory&gt; : Adds a change in the working
    directory to the staging area.

### Using Pandoc to convert a universal document to a html

1)  Install Pandoc : <http://pandoc.org/installing.html>

2)  Convert a Word docx file to markup:

> pandoc -s [example30.docx](http://pandoc.org/demo/example30.docx) -t
> markdown -o [example35.md](http://pandoc.org/demo/example35.md)

### Useful Git Tutorials

> <http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/>
>
> <https://www.atlassian.com/git/tutorials/>
>
> <http://product.hubspot.com/blog/git-and-github-tutorial-for-beginners>
>
> <http://code.tutsplus.com/tutorials/how-to-collaborate-on-github--net-34267>
