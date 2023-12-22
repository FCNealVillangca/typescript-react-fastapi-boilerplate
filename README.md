`cd backend && pip install -r requirements.txt`
install all packages for fast api 

`cd frontend && yarn install`
install react modules

`cd frontend && yarn build`
build the typescript to js enabling fast api to access index.html

`cd backend && uvicorn main:app --reload`
start the backend and react can be access in "/" or localhost:8000