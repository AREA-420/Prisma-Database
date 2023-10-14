<h1> SETTING UP DATABASE </h1>

<h2> First step </h2>
<span>Install Prisma with the following command : npm install prisma --save-dev </span>
<h2> Second Step</h2>
<span>Start a prisma project using the following command : npx prisma init</span>
<h2> Third Step</h2>
<span>replace the schema.prisma and .env files with our own files.
add the docker-compose.yml file</span>
<h2> Fourth Step</h2>
<h3>RUN the following commands</h3>
<span>docker-compose up -d</span>
<span>npx prisma migrate dev</span>

<h2> Now the data base should be up and running</h2>
