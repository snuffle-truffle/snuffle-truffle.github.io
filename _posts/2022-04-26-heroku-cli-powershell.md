---
title: "Heroku CLI on Windows cmd"
author: DTOSNER
date: 2022-04-26 19:00:00 -0000
categories: [Heroku]
tags: [rails, postgres, heroku, cmd]
---

## Download and Heroku click installer

- visit https://devcenter.heroku.com/articles/heroku-cli
- select 64 or 32 bit version

![image](assets/2022-04-26-heroku-cli-powershell/1.png)

- next -> next -> ... -> done

## Test if heroku is installed

- open cmd (or powershell)

```console
heroku --version
```

- possible output:  ![image](assets/2022-04-26-heroku-cli-powershell/2.png)

## Login to heroku

```console
heroku login
```

- redirect to web adress for login

![image](assets/2022-04-26-heroku-cli-powershell/3.png){: width="300" }
![image](assets/2022-04-26-heroku-cli-powershell/4.png){: width="300" }
![image](assets/2022-04-26-heroku-cli-powershell/5.png){: width="300" }

- heroku CLI is logged now

## Enjoy heroku CLI commands

- https://devcenter.heroku.com/articles/heroku-cli-commands

> Use "--app name_of_the_app" to select specific app
{: .prompt-tip }







