install packages:
naviagte to directory and do

pip install -r requirement.txt

Start project :
uvicorn main:app --reload

In order to simulate run:
python3 mois.py 
this will send moisture data. make sure to add same mac on code,you used when signup.

after simulating see response from api, i mean the status.

The concept is there is switch if it is on and pump is in auto mode it will stop the pump otherwise pump keeps running if moisture is low.
