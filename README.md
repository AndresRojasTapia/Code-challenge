# Code-challenge
Comparator of different delivery services

Quick start

 1- The first step is to read the project documentation.
 
 In the readme you will see that cloning the project is the first thing to do. 
It consists of a base to start your project and a server that will provide a json with the data from different delivery service companies. Each of the json comes with information such as:

> company name, 
> Pickup dates,
> Delivery dates,
> Estimated delivery time
> Extras,
> Etc.

The final instructions that the user must see to develop the project are as follows: 

- To implement a Promoted feature where users can chose between different delivery services options. The services must have a certain order, fulfilling such criteria will be rendered on top of the whole list so its easier for them to select them and therefore we can increase conversion.
- After you have all the data and structure the layout must look like this.

<img width="908" alt="Captura de pantalla 2022-02-15 a las 19 31 58" src="https://user-images.githubusercontent.com/47544166/154126427-a61c450c-fdf9-481c-91fb-a0ba2fe13bee.png">


The server is not much of a mystery. You go to the server folder of the project "cd server" in the terminal and run the command "npm install" and then "npm run server" and voila!!

![Captura de pantalla 2022-02-15 a las 19 04 30](https://user-images.githubusercontent.com/47544166/154123917-73599a77-9e9f-4256-b3fe-7549f1c23e91.png)


The base project where you have to structure the information is more complicated. It comes configured to connect to the server that delivers the json with the data. 

By default it is configured to accept Sass style processor and little else. 

![Captura de pantalla 2022-02-15 a las 19 06 02](https://user-images.githubusercontent.com/47544166/154122353-4e3e72a1-8c0b-4a68-8d6d-eda7ba5893e8.png)


In my case it has taken me several hours just to start the project, since I have implemented React to create the project. I had to run several installation commands to create the necessary dependencies as well as add them in the Babelrc file. The same when implementing Emotion and Typescript. After several hours surfing the internet to solve all the errors shown by the terminal I was able to start the project successfully.

The main problems were:

- The Chrome browser did not accept the api call. Reading comments from users with the same problem giving as a solution "Allow from the configuration to show dangerous pages", "Unblock Adblock", "Browse incognito", etc.. None have worked, however from the Firefox browser I have had no problems.


<img width="1147" alt="Captura de pantalla 2022-02-15 a las 19 12 29" src="https://user-images.githubusercontent.com/47544166/154123747-fa2d8745-b08e-46b0-895a-d7e7fc3c6085.png">

- The second most common problem was configuring Webpack, Babel, Package.json, tsconfig as you can easily forget to implement each new installation within the configuration. Not forgetting that as you go along with the installations the files must also change their extensions.

![Captura de pantalla 2022-02-15 a las 19 19 56](https://user-images.githubusercontent.com/47544166/154124876-0ba17e21-13fa-4420-84ce-ee55747ed16a.png)

![Captura de pantalla 2022-02-15 a las 19 20 13](https://user-images.githubusercontent.com/47544166/154124931-d3562f26-9706-4828-9c66-99a17042c5e6.png)

![Captura de pantalla 2022-02-15 a las 19 20 38](https://user-images.githubusercontent.com/47544166/154124968-16a0992c-38b5-4785-8ab6-1ddae80787e5.png)

![Captura de pantalla 2022-02-15 a las 19 20 57](https://user-images.githubusercontent.com/47544166/154125023-ab34be86-57c0-4245-b1ac-0857dc21ed4f.png)




