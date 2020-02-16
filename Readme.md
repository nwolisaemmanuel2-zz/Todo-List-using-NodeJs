## Project setup

This app contains both the backend and the frontend in a single repository.
```	
├── Readme.md
├── backend
├── docker-compose.yml
└── frontend
```

### Clone Repository

```bash
git clone git@github.com:nwolisaemmanuel2/Todo-list-using-NodeJs.git

```

Navigate to the root directory.

```bash
$ cd Todo-list-using-NodeJs
```
### Start app containers

Start the `frontend`, `backend` and `db` containers using docker-compose

```	bash
$ docker-compose up -d 
```
Access the app from your browser at http://localhost:8080
