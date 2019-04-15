# Installation
You need node js installed on your local machine, with node version not less than 9

Execute to clone the git repository:
```bash
git clone https://github.com/dimaq12/github_jobs.git
```

Run `yarn install` in `front` directory
Run `npm install` in `proxy` directory


## Playing locally

Execute `npm run start` in the `proxy` directory, then `npm start` in the `front` directory

Go to the browser `url: http://localhost:3000/`

## Remarks

Didn't find a way to make cross-origin requests to github jobs api.
As a workaround was created a simple proxy server

Didn't find a way to get the quantity of all jobs, pagination works not properly correct