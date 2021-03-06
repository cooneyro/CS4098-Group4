# Group Project - Party Planner

## Install

**Dependancies**

NodeJS
```bash
sudo apt-get install -y curl
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install -y nodejs
```
Node Package Manager (npm)
```bash
sudo apt-get install -y build-essential
```
Git
```bash
sudo apt-get install -y git
```
MongoDB
```bash
# Add signing keys
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv EA312927
# Create a list for Mongo repos to live in
echo "deb http://repo.mongodb.org/apt/ubuntu xenial/mongodb-org/3.2 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.2.list
# Update repo listings
sudo apt-get update
# Install mongo 
sudo apt-get install -y mongodb-org
# Start Mongo
sudo systemctl start mongod
# Verify it is running with:
sudo systemctl status mongodb
```

**Installing the App**
```
# Ensure outgoing connections are enabled or switch to hotspot

# Download zip file
curl https://github.com/DylanHobbs/CS4098-Group4/archive/dev.zip
unzip CS4098-Group4.zip
cd CS4098-Group4
# Set enviroment vars

# Run install script
npm install
# Start the server
cd
nodemon server
# Navigate to homepage
```



```bash
git clone https://github.com/DylanHobbs/Rejects.git
cd Rejects
git checkout dev
npm install
```

Navigate the semantic UI interpreter as follows:
```bash
It Looks like you have a semantic.json file already -> select Skip Install 
We dected you are using NPM. Is this your project folder? /home/$USER/Rejects -> select Yes
Where should we put Semantic UI inside your project (semantic/) -> press enter
```

Rename "config.js.example" to "config.js"
```bash
cp config.js.example config.js
nano config.js
```
Add in the database uri to config.js given to you by one of the members

```bash
node app.js 
// allow incomming connections if necessary
```

Divert your browser to http://localhost:5000/


** Testing ** 