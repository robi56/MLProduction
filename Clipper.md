
1. BUG: pip._vendor.urllib3.exceptions.ReadTimeoutError: HTTPSConnectionPool(host='files.pythonhosted.org', port=443): Read timed out.
   Solution: sudo pip install --default-timeout=100 future
   https://stackoverflow.com/questions/43298872/how-to-solve-readtimeouterror-httpsconnectionpoolhost-pypi-python-org-port
  Command: pip install opencv-python 
    When composing a docker image from dockerfile

