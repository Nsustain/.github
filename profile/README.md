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

**July 8, 2022** We haven't yet finished
our website yet, so our website is not online
obviously, but we wrote this page
in the past tense to document the process.
Anyway, please come back in a few months!
This project will remain in the development
phase until at least the end of October.

<br>
<br>
<br>

<p align="center">
  <a href="https://codersforearth.com">
    <b>CODERS FOR EARTH</b>
  </a>
</p>

<!---

An open-source website, where ...

-->

<p align="center">
  <b>HOW OUR WEBSITE WAS MADE</b>
</p>

Here are the exact steps we took to
make [our website](https://codersforearth.com).
We documented each step from ground-up,
hoping that you can replicate it if you need to. 

...

## 1. Designing the web
`git`
`GitHub`

Create a `GitHub` repository because
version control ...



`javascript`
`react.js`
`next.js`

Create the website.

...

#### Building the website's database
`SQLite`
`IBM Databases for etcd`

...

## 2. Web Server
`nginx` <br>
[[Original article by Joe Morgan](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-react-application-with-nginx-on-ubuntu-20-04)]

...

## 3. Containerization
`Docker`

Make our website into a `Docket` image.

## 4. Virtual Private Server
`DigitalOcean`
`Ubuntu Server`

Get a VPS. Around $6 per month.

## 5. Container Orchestration System
`Kubernetes`
`K3s`

Explanation on high availability.

Install `K3s`.

Configure the `K3s` to pull our website
in the form of a `Docker` image.

Note: The reason why we use `Kubernetes`.
When our website gains more popularity,
server capability can be upscaled by
getting another VPS and then adding it
on our `K3s` as a worker node.

Even when we deploy a new node or when
we update our website, our website never
goes offline thanks to `Kubernetes`.
