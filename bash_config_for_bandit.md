```sshconfig
Host *
    ServerAliveInterval 60

Host *.overthewire.org
    Cipher aes128-ctr
    Ciphers aes128-ctr
    RequestTTY yes
```

`ServerAliveInterval 60` is go maintain connection when you're afk (and to avoid freezes).\
`Host *.overthewire.org` part is to stop random freezes during the overthewire's output or during waiting for your response.


