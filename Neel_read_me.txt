http://10.0.0.11/debug/clip.html

url: >> http://10.0.0.11/api
body: >> {"devicetype":"my_hue_app#rasppi Neel"}
meth: >> get
    (NOTE: must press the Hue button on top)


username of rasppi is (on philips hue):
wA09J7Tlvu6myCfifgM5BsF6cuaw0SQOLFnAwoux

in file kp_simple.py:
make sure line has correct id
b = Bridge('10.0.0.11','wA09J7Tlvu6myCfifgM5BsF6cuaw0SQOLFnAwoux')

then go to cmd terminal window and change directory to where the kp_simple.py file is located
then type:
>> python kp_simple.py