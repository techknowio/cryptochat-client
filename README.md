# cryptochat-client
A different way to think about instant messaging

Crypto Chat Requires you to physically trade keys with someone, this allows you to encrypt all messages with AES 256
There is a middle server for message relay (https://github.com/techknowio/cryptochat-server), these message will use at least SSL 4096, to generate AES Keys, then after that only the AES keys will be used to communicate with the server (planned implementation)

