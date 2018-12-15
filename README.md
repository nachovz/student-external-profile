<p align="center">
  <img src="https://assets.breatheco.de/apis/img/images.php?blob&random&cat=icon&tags=4geeks,128">
</p>

<p align="center">
    <h2 align="center"> Student External Profile </h2>
</p>

![Buddy Works Build](https://app.buddy.works/breathecode/student-external-profile/pipelines/pipeline/162573/badge.svg?token=7fd65f24ee0daa2c60600820880d585a0bf52da8e65b5ef1f886615b58237012)
![Travis Build](https://api.travis-ci.org/4GeeksAcademy/student-external-profile.svg?branch=master)

This application serves like a Student Profile Showcase.

Each student must upload a `<your_github_username>.yml` file inside `/src/students/` with all his information via Pull Request. For example: [rigoberto.yml](https://github.com/4GeeksAcademy/student-external-profile/blob/master/src/students/example.yml).

The `yml` file must be filled with all your personal and professional information, after complating the YML fill the application will automatically generate a student portfolio like the following:

<p align="center">
  <img height="350" src="https://raw.githubusercontent.com/4GeeksAcademy/student-external-profile/master/preview.png">
</p>

<p align="center">
  <a href="http://sep.4geeksacademy.co/sharu725" target="_blank">Wach Live Demo Here</a>
</p>

```
Note: You can test your yaml syntax here: http://www.yamllint.com/
```

## Completing the YML file

The YML file is comprised of 4 fundamental sections:
```yml
theme: You can choose a theme and skin colors.
basic_info: Your personal info
education: Previous studies.
experiences: Previous jobs.
projects: Describe the projects you have build as a developer.
publications: Any articles you have published.
skills: List your skills with percentage of expertise.
```

<p align="center">
  <img height="350" src="https://raw.githubusercontent.com/4GeeksAcademy/student-external-profile/master/static/yml.png">
</p>

You can pick between your template and your skin, for example:
```yml
template: "online-cv"
skin: "orange"
```


