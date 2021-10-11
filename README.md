# frontend-boilerplate

Boilerplate for own front-end projects

When boiler downloaded some of the package.json dependencies probably need to be upgraded to the latest versions.
To do it follow the steps below:

1. Installation

   a) Install globally:

   ##### $ npm install -g npm-check-updates

   b) Or you can run with npx:

   ##### $ npx npm-check-updates

2. Usage

   a) Show any new dependencies for the project in the current directory:

   ##### $ ncu

   b) Upgrade a project's package file:

   ##### $ ncu -u

3. Run npm install to install new versions:

   a) Update installed (or install latest versions) packages and package-lock.json

   ##### $ npm install
