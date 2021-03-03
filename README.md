## ImagineThis System

This repository contains information about how to run the entire ImagineThis system.

### Deployment

1. Clone 3 repositories into the current directory: [ImagineThis Frontend](https://github.com/ImagineThisUCL/ImagineThisWeb), [ImagineThis Backend](https://github.com/ImagineThisUCL/ImagineThisServer) and [ImagineThis Database](https://github.com/ImagineThisUCL/ImagineThisDatabase). E.g.
```sh
git clone git@github.com:ImagineThisUCL/ImagineThisWeb.git
git clone git@github.com:ImagineThisUCL/ImagineThisServer.git
git clone git@github.com:ImagineThisUCL/ImagineThisDatabase.git
git clone git@github.com:ImagineThisUCL/ImagineThisExpo.git
```

2. Build images `docker-compose build`

3. Run functional containers `docker-compose up -d`
