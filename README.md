# led-python
LED FLASH using python

## Usage
python lchika.py

## Installation
git clone https://github.com/Teriyaki-0901/led-python.git

## setting

### setmode
#### BOARD
- The GPIO.BOARD option specifies that you are referring to the pins by the number of the pin the the plug

```
GPIO.setmode(GPIO.BOARD)
```

#### BCM
- The GPIO.BCM option means that you are referring to the pins by the "Broadcom SOC channel" number

```
GPIO.setmode(GPIO.CM)
```

### pin number
ex) connect GPIO2

```
GPIO.setup(2,GPIO.OUT)
```

