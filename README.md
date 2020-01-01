<h1 align="center">
  <img alt="Gympoint" title="Gympoint" src=".github/logo.png" width="200px" style="border-radius:100px"/>
</h1>

<h3 align="center">
  Gym Management Application made with ReactJS, React Native and Express
</h3>


<p align="center">

  <a href="https://www.linkedin.com/in/laurabeatris/">
    <img alt="Made by Laura Beatris" src="https://img.shields.io/badge/made%20by-laurabeatris-%23EE4D64">
  </a>

  <img alt="License" src="https://img.shields.io/badge/licence-MIT-%23EE4D64">

  <a href="https://github.com/LauraBeatris/projects_store/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/LauraBeatris/gympoint-api?color=%23EE4D64">
  </a>
</p>

<p align="center">
  <a href="#rocket-about-the-project">About the project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#runner-instalattion">Installation</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licence">Licence</a>
</p>

## :rocket: About the project
  As a admin, you're able to see the list of students, registrations and plans, as well edting/creating new ones. Also, answer and see the help orders that're pending.
  <br>
 As a student, you're able to do checkins, help orders and also get to know what the intructors answered. Students're allowed to do only 5 checkins per week. 
  
  
  Future features: 
    <br>
    - Trainings made by the Personal Trainer
    - Students can access some datas that show how they've been improving in their trainings
 
 To see the **mobile repository**, click here: [Gympoint Mobile](https://github.com/LauraBeatris/gympoint-mobile)
 <br>
  To see the **web repository**, click here: [Gympoint Web](https://github.com/LauraBeatris/gympoint-web)
 <br>
  To see the **api repository**, click here: [Gympoint Rest API](https://github.com/LauraBeatris/gympoint-api)
 <br>

## :runner: Installation 

- API 

```   
  // 1 - Git Clone
  
  // 2 - Run the services (Be sure to have docker and docker-compose installed)
  docker-compose up -d 
  
  // 2 - Once the services are running, its time to install the dependencies
  yarn install
  
  // 3 - Run the application 
  yarn dev
  
  // 4 - Run the application queue for the mail job
  yarn queue-dev
  ```
  
- Mobile 
```   
  // 1 - Git Clone
  
  // 2 - Installing the project (Be sure to have installed the react native cli)

   // If you're going to emulate with android - run this command 
   react-native run-android 
   // If you're going to emulate with ios - run this command 
   react-native run-ios 
  
  // 3 - Run the application (Be sure to have the API running locally)
    yarn start
  
  // If usually use have some error, try it 
    yarn start --reset-cache
  
```

- Web 
```   
  // 1 - Git Clone
  
  // 2 - Installing the dependencies
  yarn install
  
  // 3 - Run the application (Be sure to have the API running locally)
  yarn start
  
```


## :memo: Licence

MIT Licence. See the file [LICENSE](LICENSE.md) for more details.

---

Made with ♥ by Laura :wave: [See my linkedin!](https://www.linkedin.com/in/laurabeatris/)
