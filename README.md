m    	- message
e    	- random number generated to each message
p, k	- two parts of private key
r	- radius * radius
C	- encrypted message

a = (e - k) / (m - p)
b = e - ma
x = (b^2 - r) / ((a^2 + 1)m)
y = ax - b
C = (x, y)