Installation
============

I am using this repo to gain firsthand experience developing a website.
I have used a remote Amazon EC2 instance as my development environment so that I can quickly work on this project from any computer and so that I become familiar with the Amazon ecosystem.
To set up an Ubuntu t2 mirco instance do the following steps.

```sh
curl https://github.com/mjwatson6116/custom-setup/blob/master/setup.sh | bash
exit # and then log in again
git clone https://github.com/mjwatson6116/experiement.git
cd website
./setup-ssjs.sh
```

To view the website you need to start the foreman and navigate to port 8080 of the EC2 instance:

```sh
foreman start
```


