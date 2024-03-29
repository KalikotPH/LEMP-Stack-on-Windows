# LEMP Stack on Windows

You can easily run this after you download this on your windows machine, tested on Windows 10 version 1909. 

## Getting Started

Before you click the .bat file, please do the INSTALLING PART from this READ.MD. Servers that will run is Nginx, PHP, and MySQL. Please do RUN the .bat file with Administrator priviledge to prevent permission error.

- all_start.bat - Will START all server that is enumerated previously.
- all_stop.bat - Will STOP all server that is enumerated previously.
- all_check.bat - Will CHECK all server that is enumerated previously if it is running.

### Credential

#### MYSQL DEFAULT: phpMyAdmin
- USER: root
- PASS: root

### Installing

First you need to manually update the root directory to where you extracted this LEMP Stack. What you need to do is open the "mysql/bin/my.ini" and "php/config.inc.php" with your favorite code editor or I prefer VS Code.

OPTIONAL! If your having trouble running the mysql server, kindly do this steps. First, you need to navigate into "mysql/data/" then delete "ibdata1" and ib_logfile#.

## Deployment

This is preferably to be deployed on windows machine. Just download or clone this repository to your local machine and follow steps from Installing then continue to Getting Started.

## Built With

* [Nginx 1.16.1](https://www.nginx.com/) - Improve the performance, reliability, and security of your applications.
* [MySQL 10.1.30 MDB](https://www.mysql.com/) - MySQL is an open-source relational database management system.
* [PHP 7.3.10](https://www.php.net/) - Fast, flexible and pragmatic, PHP powers everything from your blog to the most popular websites in the world.
* [phpMyAdmin 5.0.2](https://www.phpmyadmin.net/) - phpMyAdmin is a free software tool written in PHP, intended to handle the administration of MySQL over the Web.

## Contributing

Please read [CONTRIBUTING](CONTRIBUTING) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/BytesCrafter/LEMP-Stack-on-Windows/releases). 

## Authors

* **Bytes Crafter** - *Initial work* - [GitHub](https://github.com/BytesCrafter)

See also the list of [contributors](https://github.com/BytesCrafter/LEMP-Stack-on-Windows/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## About Us

* [Email Address](mailto:support@bytescrafter.net)
* [Visit Website](https://bytescrafter.net)
* [Visit YouTube](https://www.youtube.com/channel/UCHXZUImmr9aSKmYpKXqN9vQ)
* [Visit Facebook](https://www.facebook.com/BytesCrafterPH)
* [Visit Twitter](https://twitter.com/BytesCrafter)