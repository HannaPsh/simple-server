cd ~
cd ws
mkdir edu-backend
cd edu-backend
npm init -y
mv app.js server.js
touch .env
touch app.json
touch Procfile
touch Dockerfile
touch request.rest
mkdir routes
touch routes/healthcheck.js
touch routes/user.js
mkdir **tests**
touch ./**tests**/component.js
touch ./**tests**/unit.js
npm install express --save
npm install healthcheck --save
npm install dotenv --save
npm install cors --save
npm install jsonwebtoken --save
npm install nodemon --save-dev
npm install jest --save-dev
npm install jest-runner-groups --save-dev
code .
