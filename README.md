# Helpdesk

This project was generated with [Spring Boot](https://github.com/spring-projects/spring-boot) version 2.1.8.RELEASE.

# Run Your App Locally
Let's run the app locally first to test that it all works. You must have a Postgres database up and running and accessible on the DATABASE_URL you specified above.

    # Build Your App
    > Task :compileJava
    > Task :processResources UP-TO-DATE
    > Task :classes

    > Task :HelpdeskApplication.main()

    .   ____          _            __ _ _
    /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
    ( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
    \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
    '  |____| .__|_| |_|_| |_\__, | / / / /
    =========|_|====s==========|___/=/_/_/_/
    :: Spring Boot ::        (v2.1.8.RELEASE)


# Start Your App
Note: you can also start your app using foreman to execute the Procfile. [Read more about foreman and procfiles](http://devcenter.heroku.com/articles/procfile).

# Test it
Go to http://localhost:8080 and test it out by creating a new record.

# Deploy to Heroku

Note: You must have a Heroku app up and running and accessible on name-app
the you specified above.

    $ heroku login
    $ heroku git:clone -a name-app

    $ cd helpdesk-kunlez-novahub

    $ git add .
    $ git commit -am "make it better"
    $ git push heroku master

# Swagger link
http://localhost:8080/swagger-ui.html?fbclid=IwAR3jCs6oZZwIWYgKH9DA9eDrxZWd8E5aFQTsKvST_fD8s0_1d3J6P5gOCxA#/

# Connect to database PostgreSQL
Go to application.properties change Your `spring.datasource.url`,`spring.datasource.username`, `spring.datasource.password` to connect Your database PostgreSQL





