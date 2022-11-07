1. install brew
   https://docs.brew.sh/Installation

### Steps for MongoDB installation.

Please follow this link as well: https://www.mongodb.com/docs/v4.4/tutorial/install-mongodb-on-os-x/

1. brew tap mongodb/brew
2. brew update (optional)
3. brew install mongodb-community@4.4

### Check if mongoDB is installed by running DB

4. brew services start mongodb-community@4.4

### check running service list on DB

5. brew services list

### If above check passes, pls stop the server

5. brew services stop mongodb-community@4.4

   // Window setup
   // Accessing mongoDb through terminal in Window
   steps:1 create a hidden file with name .bash_profile using touch command
   step2:open the file using vim command.
   step3: now edit the file and create shortcut for mongod and mongo in the same file using following line of code.
   alias mongod:"/C:/Program\ Files\MongoDB\Server\4.4\bin\mongod.exe"
   alias mongo:"C:\Program\ Files\MongoDB\Server\4.4\bin\mongo.exe"
   step4:save and quit the file
   step5:on terminal just type mongod to start mongoDb database.
   step6:Connect to MongoDB,just type mongo on terminal.
