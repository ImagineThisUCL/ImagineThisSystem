## ImagineThis System

This repository contains information about how to run the entire ImagineThis system.

### Deployment
1. Clone this repository and move inside:
```sh
git clone git@github.com:ImagineThisUCL/ImagineThisSystem.git
cd ImagineThisSystem
```

2. Clone 4 repositories into the current directory: [ImagineThis Frontend](https://github.com/ImagineThisUCL/ImagineThisWeb), [ImagineThis Backend](https://github.com/ImagineThisUCL/ImagineThisServer), [ImagineThis Database](https://github.com/ImagineThisUCL/ImagineThisDatabase) and [ImagineThis Expo](https://github.com/ImagineThisUCL/ImagineThisExpo). Run:
```sh
git clone git@github.com:ImagineThisUCL/ImagineThisWeb.git
git clone git@github.com:ImagineThisUCL/ImagineThisServer.git
git clone git@github.com:ImagineThisUCL/ImagineThisDatabase.git
git clone git@github.com:ImagineThisUCL/ImagineThisExpo.git
```

3. Setup `docker-compose.yml` configuration file with proper environment variables.

4. Build images with `docker-compose build`

5. Run the whole system with `docker-compose up -d imaginethis-frontend`
