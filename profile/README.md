---

<p align="center">
  <a href="https://codersforearth.com">
    <img src="https://user-images.githubusercontent.com/19341857/177896292-0837342f-120b-430b-a9bf-d4147f86f896.svg" width="350">
  </a>
</p>

---

<p align="center">
  <a href="https://github.com/CodersForEarth/codersforearth.com">
    <img alt="codersforearth.com" src="https://img.shields.io/badge/GitHub-codersforearth.com-brightgreen">
  </a>
  <a href="https://github.com/CodersForEarth/codersforearth.com/blob/main/LICENSE">
    <img src="https://badgen.net/github/license/CodersForEarth/codersforearth.com">
  </a>
</p>

---

<br>
<br>
<br>

<p align="center">
  <b>
    CODERS FOR EARTH
    <a href="https://github.com/CodersForEarth/codersforearth.com">
      [GitHub]
    </a>
  </b>
</p>

An open-source website, where ...
Why we are working so hard on
this website. Why we believe in this,
and why we believe this will help you, too.

<br>

<p align="center">
  <b>HOW OUR WEBSITE WAS MADE</b>
</p>

Here are the exact steps we took to
make [CodersForEarth.com](https://codersforearth.com)

We documented each step from ground-up,
so that you can replicate it 
relatively easily if you'd like to
make another website based on our website
or become a contributor to our project.

<br>
<br>

<!--
By the way, the white space in front of [1.1] and [1.2]
is the unicode em space: (  )
-->
## Steps
[1.](#1-designing-the-website) Designing the website<br>
  [1.1](#back-end) Back-end<br>
  [1.2](#front-end) Front-end<br>
[2.](#2-containerizing-the-website) Containerizing the website<br>
[3.](#3-deploying-a-container-orchestration-system) Deploying a container orchestration system<br>
[4.](#4-getting-a-domain-name) Getting a domain name<br>
[5.](#5-getting-a-server) Getting a server

<br>
<br>

# 1. Designing the website

**Writing codes on a version-control system**<br>
Techs used:
`git`
`GitHub`

## Back-end

**Building the website's database**<br>
Techs used:
`SQLite`
`IBM Databases for etcd`

Blabla ...

## Front-end

Create a `GitHub` repository because
version control ...

**Building the front-end**<br>
Techs used:
`javascript`
`react.js`
`next.js`

Create the website ...

<br>
<br>

# 2. Containerizing the website
Techs used:
`Docker`

Make our website into a Docker image.
Why containerize and why not else.

<!--- Installing docker
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-22-04

Using docker compose
https://www.digitalocean.com/community/tutorials/how-to-install-wordpress-with-docker-compose
-->

<br>
<br>

# 3. Deploying a container orchestration system
Techs used:
`Kubernetes`
`K3s`

Explanation on high availability.
Why K3s and not else, showing
the how and why behind 
our design & architecture choices.

Install K3s.

Configure the K3s to pull our website
in the form of a Docker image.

Note: The reason why we use Kubernetes.
When our website gains more popularity,
server capability can be upscaled by
getting another VPS and then adding it
on our K3s as a worker node.

Even when we deploy a new node or when
we update our website, our website never
goes offline thanks to Kubernetes.

<br>
<br>

# 4. Getting a domain name
Techs used:
`Google Domains`

Our domain name CodersForEarth.com
costs $12 per year.

**(Optional) Setting up a custom-domain email forwarding service**<br>
[[Original article by Forward Email](https://forwardemail.net/en/faq#how-do-i-get-started-and-set-up-email-forwarding)]<br>
Techs used:
`ForwardEmail.net`

One way of doing this would be setting up an
email server on the VPS we just got, but
we didn't need such complexity. We didn't
need to have multiple email accounts.
We could just use one email account.
All our email needs were such that just using an email
forwarding service would solve all of them. 

**Setting up remote caching and DDoS protection**<br>
[[Original article by Prutser Rutger](https://blog.prutser.net/2021/01/20/how-to-securely-self-host-a-website-or-web-app/)]<br>
Techs used:
`Cloudflare`

https://blog.prutser.net/2021/01/20/how-to-securely-self-host-a-website-or-web-app/
It also takes care of issuing SSL certificates.

The traffic between the user and Cloudflare
is automatically SSL encrypted, but the traffic
between Cloudflare and our server needs one
extra step to be SSL encrypted -- i.e.
download the "Cloudflare-issued SSL certificate"
on their settings and install it in our server.

<br>
<br>

# 5. Getting a server
Techs used:
`DigitalOcean`
`Ubuntu Server`

Get a VPS. Around $6 per month.

**Hosting a Virtual Private Server**<br>
[[Original article by Joe Morgan](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-react-application-with-nginx-on-ubuntu-20-04)]<br>
Techs used:
`nginx`

Blabla ...

<br>
<br>

<p align="center">
  <b>WHAT NEXT?</b>
</p>

You could go to 
[our website](https://codersforearth.com)
and see if there's any project
you'd love to invest your time in,
or you could even become a contributor
of this website itself.
[[GitHub](https://github.com/CodersForEarth/codersforearth.com)]

Plus, if you like our logo,
you could download various versions of
[our logo](https://github.com/CodersForEarth/.github/blob/main/README.md),
whose base illustration was painted by `@realvjy` at
[illlustrations.co](https://illlustrations.co)








