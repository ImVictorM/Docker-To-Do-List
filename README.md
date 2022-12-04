# Docker To-Do List ✔️

## Project Context 💡
We have a full-stack application in this repository: a task application! This application needs to be containerized to work properly. My job in this project was to develop the configuration files for each specific front: Front-end, Back-end, and for a test application that validates if the applications are communicating. <br/>
The application is located in the path `docker/todo-app`.
The developed docker commands are in the path `docker/docker-commands`, each file within this directory has only one command that performs a specific task.

### Acquired Knowledge 📖

In this project, I was able to:
- Write Docker commands;
- Containerize applications;
- Create a connection between containers;
- Orchestrate containers.

## Used Technologies 🧰
<table>
    <thead>
        <tr>
            <th>Docker</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">
                <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> 
                    <img 
                        src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" 
                        alt="docker" 
                        width="40" 
                        height="40"
                    /> 
                </a>
            </td>
        </tr>
    </tbody>
</table>

## Running the application ⚙️

1. Clone and enter this repository
```
git clone git@github.com:ImVictorM/Docker-To-Do-List.git && cd Docker-To-Do-List
```
2. Install the dependencies
```
npm install 
```
3. Start the project
```
npm start
```

## Testing 🛠️
Running all tests:
```
npm test
```
Running a specific test:
```
npm test {test_file_name}
```

