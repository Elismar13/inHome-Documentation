<h1 align="center">
    <img alt="inHome" title="#inHome" src="./assets/inHome_logo.png" width="150px" />
</h1>

<h4 align="center"> 
	:construction: 🚀 inHome - in progress :construction:
</h4>
<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Elismar13/inHome-Documentation?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Elismar13/inHome-Documentation">
	
  <a href="https://www.linkedin.com/in/danielobara/">
    <img alt="Made by Elismar13" src="https://img.shields.io/badge/made%20by-Elismar13-%2304D361">
  </a>

  <a href="https://github.com/DanielObara/SemanaOmnistack11/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Elismar13/inHome-Documentation">
  </a>

  <a href="https://github.com/DanielObara/SemanaOmnistack11/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/Elismar13/inHome-Documentation">
  </a>
<a aria-label="In progress" href="">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
</p>

<p align="center">
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-Technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

<p aligh="center">
	inHome API are available in: <a href="https://inhome-backend.herokuapp.com">https://inhome-backend.herokuapp.com</a>
</p>

## 💻 Project

inHome is a project that allow users to control thermal confort equipaments by Internet of Things.


## :rocket: Technologies

This project was developed with the following technologies:

- [Node.js](https://nodejs.org/en/) 


## :wrench: How to use

The API are divided in two entities: 

#### Client
- List user data:
> - query params: id=USER_NAME<br>
`GET https://inhome-backend.herokuapp.com/users/list?id=USER_NAME`

- Logon in the application: 
> - body: JSON Object with "Username" and "Password" atributes.<br>
> example:

`{
	Username: "USERNAME",
	Password: "123456"
}`<br>
`GET https://inhome-backend.herokuapp.com/users`

- Create new user: 
> - body: JSON Object with "Username", "Password" and "ProfileImage" atributes.<br>
example: 
`{
	Username: "USERNAME",
	Password: "123456",
	ProfileImage: "www.minhafoto.com/minhafoto.png"
}`<br>
`POST https://inhome-backend.herokuapp.com/users`


#### Device
- Show user devices:<br>
> `GET https://inhome-backend.herokuapp.com/devices`

- Create a new device for user:
> - body: JSON Object with "DeviceID", "DeviceName", "ambient", "latitude" and "longitude" atributes.<br>
> `POST https://inhome-backend.herokuapp.com/devices`

-Update device data:<br>
* in development *


## 🤔 How to contribute

- Make a fork;
- Create a branck with your feature: `git checkout -b my-feature`;
- Commit changes: `git commit -m 'feat: My new feature'`;
- Make a push to your branch: `git push origin my-feature`.

After merging your receipt request to done, you can delete a branch from yours.

## :memo: License

This project is under the MIT license. See the [LICENSE](LICENSE.md) for details.

---

Made with ♥ by Elismar Silva :wave: [Get in touch!](https://www.linkedin.com/in/elismar-silva-644272191/)
