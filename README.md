# Ineuron-Project
# Installing things(Setting Environment)
->First Initialise the "package.json" using Command(npm init -y)-->in privious, -y is used so that we don't need to press yes again & again.
->Now write Command(npm i express)
->Now write Command(npm i mongoose)
->Now install Templete Engine(Handle Bars) Command(npm i hbs)
->Now Create some folder or file like(src, models, db, app.js(file)) (app.js is our main file)
->Now we have to run "app.js" file by Command(node src/app.js)
->Now to avoid writting above command again & again just use nodemon
->write Command(npm i nodemon)
->Now i have create a new Script as ("dev": "nodemon src/app.js")
->Now whenever we have to run a Script then we write Command(npm run dev(script's name))
->Now after Creating login & registration do hashing by writting Command(npm i bcryptjs)
'''
"""
->Basically app.js is our express part
->Now we have created conn.js in db folder to connect database to our express part(app.js).
"""
"""
Run "npm run dev" in console to make it run
"""
