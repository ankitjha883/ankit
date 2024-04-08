

#### Install on Kali/Debian

First we need to install pip3 for python3 dependencies:

```$ sudo apt-get install python3-pip```

Then we can run through dependency checks:

```$ pip3 install -r requirements.txt```

If this fails because of missing setuptools, do this:

```sudo apt-get install python3-setuptools```

#### Usage

To run a scan against a target:

```python3 cloudfail.py --target seo.com```

To run a scan against a target using Tor:

```service tor start```

(or if you are using Windows or Mac install vidalia or just run the Tor browser)

```python3 cloudfail.py --target seo.com --tor```

> Please make sure you are running with Python3 and not Python2.*.


#### Dependencies
Thank YOU!
ANKIT KUMAR JHA
ANKIT RAJ
ABHISHEK 
contect +918051050252
