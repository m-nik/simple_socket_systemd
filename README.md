
# simple systemd socket service


- add service 
`ln -sf $(pwd)/simple_socket.service /etc/systemd/system`

- check status and start it
`systemctl start simple_socket.service`
`systemctl status simple_socket.service`

`nc -u localhost 12345`

