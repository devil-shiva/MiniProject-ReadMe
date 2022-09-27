# Fruitenia
An Webiste To Provide the Vast Details Of any Fruit, also to deliver the Fruits to registered users based on their Diet Plan Set on Website.

# Front-End Technology Used
* [HTML 5](https://www.w3schools.com/html/)
* [CSS 3](https://www.w3schools.com/css/)
* [Java Script](https://www.w3schools.com/js/) 
* [Next-Js](https://nextjs.org/) version - 12.3.0
* [WordPress](https://wordpress.com) version - 6.0.1

# Back-End Technology Used
* [NodeJs](https://nodejs.org/)
* [Mongo-DB](https://www.mongodb.com/)
* [NPM](https://www.npmjs.com/)
* [Mongoose](https://mongoosejs.com/) version - 6.6.0

# Graphics Technology Used
* [Adobe Illustrator](https://www.adobe.com/in/products/illustrator.html?gclid=CjwKCAjwvsqZBhAlEiwAqAHElaPziTeshyGe3CnQlztJGhGC7_Em-ElyQT_V-iKnzt9dogNr5dNNCRoCX4IQAvD_BwE&sdid=SBNHMR64&mv=search&ef_id=CjwKCAjwvsqZBhAlEiwAqAHElaPziTeshyGe3CnQlztJGhGC7_Em-ElyQT_V-iKnzt9dogNr5dNNCRoCX4IQAvD_BwE:G:s&s_kwcid=AL!3085!3!248235017693!e!!g!!adobe%20illustrator!221172068!17525759228)

# Code Editor Used
- [Visual Studio Code](https://code.visualstudio.com/)

# Procedure

## 1. Installing a Code Editor
We Need Code Editor To Write all Our Front-End And Back-End Codes. For this Project We Recommend [Visual Studio Code](https://code.visualstudio.com/)

- Download the Code Editor From [Here](https://code.visualstudio.com/)
- And install the Code Editor on Your System.


***


## 2. Installing NodeJs
We need NodeJs To Use the Node Package manager ( NPM ) to install Next-Js and athore modules / dependensies.

- Download Node js from [Here](https://nodejs.org/)
- Install The Nodejs on Your System

You can Verify that node Js is installed or not by running the following line in the command terminal.

```bash
npm --version
```


***


## 3. Creating Next-Js Project
1. First Get into a folder where you want to create an NextJs Project.
2. Open the Command Line In that Folder By Pressing
<kbd>shift</kbd> + <kbd>Right Mouse Click</kbd>

4. To create an Next-Js Project run the following Line in the Command Terminal

```bash
npm create-next-app myapp
```

4. This will Create the Next-Js Project in The current Directory with the name " myapp ".
5. Go Inside The Project Directory .i.e myapp.
6. Open It With VsCode that we Installed
7. To open the Folder With VsCode open the command Terminal in that Folder by pressing
<kbd>shift</kbd> + <kbd>Right Mouse Click</kbd>
8. Now type the Following line in the Command Terminal

```bash
code .
```

9. This will open that Project Folder in VsCode
10. No Press <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>`</kbd>
11. This will open the Terminal in VsCode
12. In that Terminal Run the Following Line To Start The Project in Your Local Host to Preview The Pages.

```bash
npm run dev
```

13. This Will Start Your Project on [http://localhost:3000](http://localhost:3000)
14. Open [http://localhost:3000](http://localhost:3000) With Your Browser to see Your Result.
15. You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file and Save it on VsCode.
16. [API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.
17. The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

#### Learn More
To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

#### Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.


***

## 4. Connecting To Database (MongoDb)

To Connect our Project To the MongoDb Databse we First need To install Mongoose

To install Mongoose Open the Project Disrectory with VsCode and then Open the VsCode Terminal. and Run the following Command

```bash
npm install mongoose
```

Learn More About Mongoose From Here [https://mongoosejs.com/docs/](https://mongoosejs.com/docs/)

Once The Mongoose is installed Now let's Create an account on [MogoDb Atlas](https://www.mongodb.com/cloud/atlas/register)

If You already have an account then Login To it Fom Here [https://account.mongodb.com/account/login](https://account.mongodb.com/account/login)

To create an Databse Refer to the following Documentation : 

Once the Database Collection is Created , Copy the Connection String of Your Databse Collection.

Then Create a folder in the root directory that is `myapp/` , let the project name be `middleware`.
Create a file `middleware/mongo`.
Add The Following Lines in `middleware/mongo` file.

```javascript
const mongoose = require('mongoose');

main().catch(err => console.log(err));

async function main() {
  await mongoose.connect('mongodb://localhost:27017/test');
  
  // use `await mongoose.connect('mongodb://user:password@localhost:27017/test');` if your database has auth enabled
}
```

This Will Connect Your Project With the MongoDb Database.

Learn More About Connecting Your Databse To the Nextjs Project from [Here](https://www.mongodb.com/docs/atlas/tutorial/connect-to-your-cluster/)

Now You can Create API's in `myapp/pages/api/` folder.


***


## 5. Logo Making
To Make the Logo First Download the [Adobe Illustrator](https://www.adobe.com/in/products/illustrator.html?gclid=CjwKCAjwvsqZBhAlEiwAqAHElaPziTeshyGe3CnQlztJGhGC7_Em-ElyQT_V-iKnzt9dogNr5dNNCRoCX4IQAvD_BwE&sdid=SBNHMR64&mv=search&ef_id=CjwKCAjwvsqZBhAlEiwAqAHElaPziTeshyGe3CnQlztJGhGC7_Em-ElyQT_V-iKnzt9dogNr5dNNCRoCX4IQAvD_BwE:G:s&s_kwcid=AL!3085!3!248235017693!e!!g!!adobe%20illustrator!221172068!17525759228)

Install the software.

To Learn How To make Logos on Adobe Illustrattor :
Watch Youtube Videos from [Here](https://www.youtube.com/results?search_query=adobe+illlustrator)


***

## 6. INSTALLING WORDPRESS


![Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/2/20/WordPress_logo.svg/2560px-WordPress_logo.svg.png)






WordPress is a free and open-source content management system written in PHP and paired with a MySQL or MariaDB database with supported HTTPS. Features include a plugin architecture and a template system, referred to within WordPress as Themes.

### Procedure

STEP 1 : Download XAMPP Control Panel from the google or you can directly download it from https://www.apachefriends.org/download.html accroding to your operating system.

STEP 2 : Start installation and when the installation is complete just reboot your device.

STEP 3 : After installation is done then download WORDPRESS file from the google by searching wordpress download or you can download it from https://wordpress.org/download/ 

STEP 4 : After downloading wordpress file which is in the zip format extract it by using your windows extraction tool or you can extract it by using WINRAR.
You can download WINRAR from https://www.win-rar.com/predownload.html?&L=0

STEP 5 : After the extraction is done copy/cut wordpress folder and paste it on C:\xampp\htdocs

STEP 6 : After pasting those files on htdocs folder then open XAMPP Control Panel by searching it on windows search option.

STEP 7 : Once XAMPP Control Panel is opened click on Start [ONLY ON APACHE AND MYSQL SERVER] 

## Screenshots

![App Screenshot](https://upload.wikimedia.org/wikipedia/commons/d/de/XAMPP_Windows_10.PNG)


STEP 8 : Open any browser on your computer,click on search bar and type:-- localhost/wordpress/ then a site will be open on which you just have to create id password and after login is completed then Your site for editing is completed.

### Now you can chose any editing tools inside wordpress editor 
![App Screenshot](https://www.hostinger.com/tutorials/wp-content/uploads/sites/2/2019/10/custom-links-menu-wordpres.png)
