## Redis with JavaScript

This is an example of how to use cache with redis in a javascript application measuring the fetching time.

For this, the following libs were used:

- axios
- express
- redis
- performance-now

### Instalation

Clone the project to your machine and run:

```shell
npm install #install all the dependencies in your project

node server.js # Start the application
```

Now, access localhost:3000/.

Considering the cache expiration is set to 5 seconds, reload the page every few seconds so you can see interesting information.

You will have something like this:

```
Server is running on port 3000!
Fetching time: [__API] 691.20 ms
Fetching time: [Redis] 2.74 ms
Fetching time: [__API] 433.89 ms
Fetching time: [Redis] 2.38 ms
Fetching time: [Redis] 3.12 ms
Fetching time: [__API] 474.19 ms
Fetching time: [Redis] 2.80 ms
Fetching time: [__API] 658.59 ms
Fetching time: [Redis] 2.29 ms
Fetching time: [__API] 451.36 ms
```

### Free PDF Course
If you want to learn about Redis, I took a free Redis introductory course present in this repository, inside course/redis-course.pdf.