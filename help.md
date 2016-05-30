GitHub: an open source version control system. Git is responsible for
the everything GitHub-related that happens local computer.

<https://help.github.com/articles/set-up-git/>

### Setting up Git

1.  Download and install the latest version of [GitHub
    Desktop](https://desktop.github.com/). This will automatically
    install Git and keep it up-to-date for you.

2.  On your computer, open the **Git Shell** application.

3.  Tell Git your *name* so your commits will be properly labeled. Type
    everything after the \$ here:

\$ git config --global user.name "*YOUR NAME*"

1.  Tell Git the *email address* that will be associated with your
    Git commits. The email you specify should be the same one found in
    your [email
    settings](https://help.github.com/articles/adding-an-email-address-to-your-github-account/).
    To keep your email address hidden, see "[Keeping your email address
    private](https://help.github.com/articles/keeping-your-email-address-private)".

\$ git config --global user.email "*YOUR EMAIL ADDRESS*"

### Next steps: Authenticating with GitHub from Git

Connect to a GitHub repository from Git :

#### Connecting over HTTPS (recommended)

When you view a repository while signed in to your account, the URLs you
can use to clone the project onto your computer are available below the
repository details:

> ![](media/image1.png){width="4.21875in" height="2.1979166666666665in"}

Using Git on the command line (Git Shell): git clone, git fetch, git
pull, or git push
