# impact-api-deploy
Contains the build and deploy components of the api server

In its current state, this project contains an 'ansible' folder that should reside in root of the impact-api project. To get started you must first clone the impact api project:

## Usage:

	pip install ansible-container

### then clone the repos and create the directory structures needed

	git clone https://github.com/masschallenge/impact-api.git
	git clone https://github.com/masschallenge/impact-api-deploy
	mv impact-api-deploy/ansible impact-api
	cd impact-api

### then execute a build

	ansible-container build
