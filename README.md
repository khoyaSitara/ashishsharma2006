### Hi there 👋

<!--
**AshishSharma2006/ashishsharma2006** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}

body {
  height: 100vh;
  overflow: scroll;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol";
  font-size: 1.7em;
}

header {
  background: #202529;
  color: white;
  height: 10vh;
  min-height: 100px;
  display: flex;
  align-items: center;
  width: 100%;
}

.github-logo {
  fill: white;
  margin: 0 0.5em 0 0.5em;
}

header nav:nth-of-type(1) {
  width: 45%;
}

header ul {
  display: flex;
  justify-content: space-between;
  width: 100%;
}

header ul li {
  display: inline-block;
  cursor: pointer;
}

header ul li:hover {
  color: #C7C8C9;
}

header form {
  display: flex;
  width: 30%;
  justify-content: flex-end;
}

header input {
  font-size: 0.9em;
  padding: 0.5em;
  border: none;
  background: #3C4044;
  border-radius: 7px;
}

header nav:nth-of-type(2) {
  width: 20%;
}

.login-signup-nav ul {
  justify-content: flex-end;
}

.login-signup-nav ul li:nth-of-type(2) {
  margin: 0 0.5em 0 0.5em;
  color: #C7C8C9;
}

main {
  display: flex;
}

main aside {
  width: 30%;
  display: inline-block;
  padding: 1em;
}

aside img {
  width: 100%;
  padding: 0.23em;
  border-radius: 22px;
  /* margin: 0.5em; */
}

main section {
  width: 70%;
  display: inline-block;
}

.grey-text {
  color: #655F5C;
}

.username {
  font-weight: normal;
}

.bio {
  padding-top: 2em;
  padding-bottom: 2em;
}

.repo-nav {
  display: flex;
  /* justify-content: space-between; */
  width: 100%;
}

.repo-nav li {
  cursor: pointer;
  display: inline-block;
  padding: 1em;
  border-bottom: 2px solid #CBCFD5;
}

.repo-nav li:hover {
  border-bottom-width: 3px;
}

.repo-nav li:nth-of-type(1) {
  border-bottom: 3px solid #DF570C;
  margin-left: 1em;
}

.repos-title {
  font-weight: normal;
  margin: 1em;
}

.repositories {
  display: flex;
  flex-wrap: wrap;
  margin: 1em;
  width: 100%;
  height: 100%;
}

.repositories .pinned-repo-wrapper:nth-of-type(1n) {
  margin-right: 0.5em;
}

.repositories .pinned-repo-wrapper:nth-of-type(2n) {
  margin-left: 0.5em;
}

.pinned-repo-wrapper {
  width: 45%;
  margin-bottom: 0.5em;
  height: 30%;
}

.pinned-repo {
  border: 2px solid #CBCFD5;
  padding: 1em;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.pinned-repo h3 {
  color: #035CD0;
}

.pinned-repo p {
  margin-top: 1em;
  margin-bottom: 1em;
  overflow-wrap: break-word;
}

.stats {
  display: flex;
  align-self: baseline;
}

.stats li {
  display: flex;
  align-items: center;
}

.icon {
  display: inline-block;
  margin: 0.5em;
}

.seperator {
  margin: 1em 0;
}

a {
  color: #035CD0;
  text-decoration: none;
}
