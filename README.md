# Travel Memory

`.env` file to work with the backend after creating a database in mongodb: 

```
MONGO_URI='ENTER_YOUR_URL'
PORT=3001
```

Data format to be added: 

```json
{
    "tripName": "Incredible India",
    "startDateOfJourney": "19-03-2022",
    "endDateOfJourney": "27-03-2022",
    "nameOfHotels":"Hotel Namaste, Backpackers Club",
    "placesVisited":"Delhi, Kolkata, Chennai, Mumbai",
    "totalCost": 800000,
    "tripType": "leisure",
    "experience": "Lorem Ipsum, Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum, ",
    "image": "https://t3.ftcdn.net/jpg/03/04/85/26/360_F_304852693_nSOn9KvUgafgvZ6wM0CNaULYUa7xXBkA.jpg",
    "shortDescription":"India is a wonderful country with rich culture and good people.",
    "featured": true
}
```


For frontend, you need to create `.env` file and put the following content (remember to change it based on your requirements):
```bash
REACT_APP_BACKEND_URL=http://localhost:3001



Node Hello World
Simple node.js app that servers "A Monk in Cloud"

Great for testing simple deployments on Cloud

Step 1: Install NodeJS and NPM using nvm
Install node version manager (nvm) by typing the following at the command line.

sudo su -
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
Activate nvm by typing the following at the command line.

. ~/.nvm/nvm.sh
Use nvm to install the latest version of Node.js by typing the following at the command line.

nvm install node
Test that node and npm are installed and running correctly by typing the following at the terminal:

node -v
npm -v
Step 2: Install Git and clone repository from GitHub
To install git, run below commands in the terminal window:

sudo apt-get update -y
sudo apt-get install git -y
Just to verify if system has git installed or not, please run below command in terminal:

git — version
This command will print the git version in the terminal.

Run below command to clone the code repository from Github:

git clone https://github.com/kritikauma2012/HeroVired-assignment-1.git
Get inside the directory and Install Packages

cd TravelMemory
cd Frontend
npm install
Start the application To start the application, run the below command in the terminal:

npm start
```
cd backend
npm start
