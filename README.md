#READ ME

## Registering a Domain Name

1. Visit [NameCheap](https://nc.me/). (A .me domain is free for one year if you have a university email account.)

2. Go to CaneLink and find your umail.miami.edu address (it is what you receive before an alias is created).

   Under 'Personal Information' click 'Update Email Address'.

   Take note of the 'preferred email address' -- it should end with umail.miami.edu. Use this email address when registering with NameCheap.

3. When you reach a step during NameCheap registration where it asks for either GitHub Pages or About.me, select GitHub Pages.

  The page may 'hang' and not seem like it is advancing to the next step. If this happens, visit your GitHub account. You should see a new repo which was created by NameCheap. If so, disregard the hanging page and move on to step 4.

4. Visit NameCheap.com and log in.

5. Under 'Account Information' select view next to 'Number of domains in your account'.

6. Click on your domain name.

7. On the left side, under 'Host Management', select 'All Host Records'.

8. The settings should be as follows (username is *your* username):

<table>
  <tr>
    <td>@</td>
    <td>192.30.252.153</td>
    <td>A</td>
  </tr>
  <tr>
    <td>@</td>
    <td>192.30.252.154</td>
    <td>A</td>
  </tr>
  <tr>
    <td>www</td>
    <td>username.github.io</td>
    <td>CNAME</td>
  </tr>
</table>

9. Open Atom (or Brackets) and type your domain name (do not start it with www) in a plain text file. Save this as "CNAME" (not CNAME.txt or CNAME.html -- just CNAME).

10. Add the CNAME file to the username.github.io repo on your computer, commit it and push it to GitHub.


## If you registered a domain name elsewhere

You may have a domain name registered elsewhere. Since it is impossible to know the details of every registrar's setup, you will need to read documentation to get your domain set up between your registrar and GitHub.

Ultimately, you need to provide two 'A Name' records and a 'CNAME' record, which should be as follows (where username is *your* username).

<table>
  <tr>
    <td>@</td>
    <td>192.30.252.153</td>
    <td>A</td>
  </tr>
  <tr>
    <td>@</td>
    <td>192.30.252.154</td>
    <td>A</td>
  </tr>
  <tr>
    <td>www</td>
    <td>username.github.io</td>
    <td>CNAME</td>
  </tr>
</table>

Once you have done this, open ATOM and type your domain name (do not start it with www) in a plain text file. Save this as "CNAME" (not CNAME.txt or CNAME.html -- just CNAME). Add the CNAME file to your username.github.io repo, commit it and push it to GitHub.


## Testing your domain

**DO NOT** visit the domain name you just registered. (There is a long explanation as to why you do not want to do this. Fixing the problem involves deleting hidden files on your computer ... and you don't want to do this.)

When you have completed the steps above, visit username.github.io (where username is *your* username). If all has been set up correctly, when the domain is working, the URL bar will automatically change to your domain name!
