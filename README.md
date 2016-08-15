aftic-conf-app
=========

aftic-conf-app is built on top of [Pinax Symposion](https://github.com/pinax/symposion) and [PinaxCon](https://github.com/pinax/PinaxCon). With our changes, your mileage may vary.

Here is the original [PinaxCon README](README_PinaxCon.md) for this repo.


Getting Started
----------------

Make sure you are using a virtual environment of some sort (e.g. `virtualenv` or
`pyenv`).

```
createdb pinaxcon
pip install -r requirements.txt
./manage.py migrate
./manage.py loaddata sites conference proposal_base sitetree sponsor_benefits sponsor_levels
./manage.py runserver
```

Documentation
--------------

### aftic-conf-app
Adding a page to main menu:
* Go to https://enigmatic-depths-30457.herokuapp.com/admin/sitetree/tree/1/change/
* Click "Add Site Tree Item +"
* Enter a Title.
* In "URL:" enter something like this: pages_page "MY_NEW_PAGE/"
* Under "Additional Settings" click "Show".
* Check the "URL as Pattern" box.
* Click "Save"
* Go to homepage ( https://enigmatic-depths-30457.herokuapp.com/ ) and click on page to add content to it.

### PinaxCon
Read the docs: https://symposion.readthedocs.io/en/latest/index.html

Contribute
----------------
### aftic-conf-app
TBD

### PinaxCon
In case of any questions we recommend you [join our Pinax Slack team](http://slack.pinaxproject.com) and ping us there instead of creating an issue on GitHub. Creating issues on GitHub is of course also valid but we are usually able to help you faster if you ping us in Slack.

We also highly recommend reading our [Open Source and Self-Care blog post](http://blog.pinaxproject.com/2016/01/19/open-source-and-self-care/).  
