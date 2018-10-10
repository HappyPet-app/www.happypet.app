# HappyPet website

Source code of the HappyPet website.

Built with [Pelican](https://github.com/getpelican/pelican).

## Requirements

- Python3

##  Contributing

### Setup

Install [virtualenv](https://pythontips.com/2013/07/30/what-is-virtualenv/).

```
pip install virtualenv
```

In the project folder, create a a virtualenv.

```
virtualenv -p python3 .venv
```

Activate the virtualenv.

```
source .venv/bin/activate
```

Install dependencies.

```
pip install -r requirements.txt
```

### Develop

Create your branch (or fork the project if you're not part of the organization).

```
git checkout -b 'feature/reworkFooter'
```

Edit the website regarding to the official [Pelican documentation](http://docs.getpelican.com/en/stable/).

You can start a local server with hot reloading to see your changes in realtime at [http://localhost:8080](http://localhost:8080).

```
bash develop_server.sh 8080
```

When you finish working, don't forget to get out of the virtualenv.
You can reactivate it the next time you will work on this project.

```
deactivate
```

When your new feature is finished, just open a [pull request](https://github.com/HappyPet-app/www.happypet.app/compare) against the master branch on GitHub.
