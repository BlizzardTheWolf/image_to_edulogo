# image_to_edulogo
converts an image file into executable code in edulogo

# dependencies:
pip:
    PILLOW
s:

setRGB :c :param
setpencolor :c
make "c :c + 1
fd -1

e:

pu
rt 90
fd 1
rt 90
fd :param * -1
rt 180
pd

n:

fd -1

r:

setcolor :param
fd -1
