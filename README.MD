# .NET Templates

This repository is full of templates with several types of project, such as Console, WebAPI, Testing, etc, and using a bunch of tools like Dapper, EF, connections with NoSQL.

## Installation
You can clone the whole repository with all projects, or go to the specific that you want and clone by it.

After you choose the template, you have to install the template config in your .NET environment. To do it just execute the command bellow:

```bash
dotnet new install . # if you are in the root of the template

# OR

dotnet new install <project_full_path>
```

## Usage
To use you new template, just run the follow command:

```bash
dotnet new <project_shortName> -o <your_project>
```
[INFO] - You can fin the project's shortName in the JSON file called **template.json** inside template.config folder.

Now enjoy your new project without doing everything from scratch! 😉
## License

[MIT](https://choosealicense.com/licenses/mit/)