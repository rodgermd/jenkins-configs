Jenkins configs for SF2
=================

* Copy `config.xml` to jenkins `jobs` folder, probably in `/var/lib/jenkins`. Change **projectUrl** to match your project
* Copy `build.xml` to **project root folder**. Change project name
* Copy `phpunit.xml` to `app/Resources` folder
* Copy `jenkins` folder to `app/Resources` folder. Change project name in `jenkins/phpdox.xml`
