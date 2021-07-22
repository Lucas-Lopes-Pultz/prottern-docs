# Commands
***

## init

The **init** command creates a template repository if it does not exist.

```command
$ prottern init
```
***

## save

The **save** command saves a template in the repository. 

It takes two parameters:

The 1st parameter receives the path of the project's root directory that will be used as a reference for generating the template.

The 2nd parameter receives the name of the template.

```command
$ prottern save <directory-path> <template-name>
```
***

## templates

The **templates** command lists all the templates in your local repository.

For example:

- I have three templates saved in my repository, with the names of: project-web, project-mobile, project-desktop.

- When typing the templates command, the three templates will appear in my terminal.

```command
$ prottern templates
```

output:

```
>> Local templates
   | project-site
   | project-mobile
   | desktop-project

>> Remote templates
```
***

## delete

The command **delete** deletes a template from the repository.

It receives the name of the template to be removed as a parameter.

```command
$ prottern delete <template-name>
```

***

## create

The **create** command generates a project from a saved template. It takes two parameters:

- The 1st parameter receives the name of an existing template on the repository

- The 2nd parameter receives the path of the output directory where the template will be generated.

```command
$ prottern create <template-name> <directory-path>
```
***

## describe

The **describe** command shows information about the template passed as a parameter.


```command
$ prottern describe <template-name>
```

output example:

```
>> name
   | project-web

>> type
   | Local

>> owner
   | user1

>> created at
   | 2021-07-10 14:02:55.657383900 UTC

>> paths
   | index.html
   | src
   | src\script.js
   | src\style.css.css
```
***

## signup

This command is used for signup an user account.

You need to have an user account because you will need one before save templates or publish templates.

To create an user account type:

```command
$ prottern signup
``` 

A signup form will appear requesting your username, password and email.
***

## login

This command is used for authenticate your user account.

To authenticate your account type:

```command
$ prottern login
```

A login form will appear requesting your username and password.
***

## profile

This command returns the public info of the current user account logged.

```command
$ prottern profile
```

output example:

```
Name: username
Email: username@email.com
```
***

## discover
***

## get

This command is used to get public third party templates.

```command
$ prottern get <template-name>
```
***

## pub
This command is used to publish a template.

```command
$ prottern pub <template-name>
```
***

## unpub
This command is used to unpublish a remote template.

```command
$ prottern unpub <template-name>
```