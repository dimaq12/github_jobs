# Installation
You need node js installed on your local machine, with node version not less than 9
Use 
```bash
git clone https://github.com/dimaq12/github_jobs.git
```
to download the git repository

Run `yarn install` in `front` directory
Run `npm install` in `proxy` directory


## Playing locally

Execute `npm run start` in the `proxy` directory, then `npm start` in the `front` directory

Go to the browser `url: http://localhost:3000/`

## Remarks

Don't find a way to make cross-origin requests to github jobs api.
As a workaround was created a simple proxy server

Don't find a way to get the quantity of all jobs, pagination works not properly correct