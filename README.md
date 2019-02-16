# chat-ndlug-org
Documentation on chat.ndlug.org

## Services we offer
- [Mattermost](mattermost.com)
- [matterircd](https://github.com/42wim/matterircd/)
- [irslackd](https://github.com/adsr/irslackd)
- [ZNC](https://wiki.znc.in/ZNC)

### How to connect to...

#### Mattermost

```
Navigate your web browser to https://chat.ndlug.org and follow the on screen prompts for
making a new account
```

#### matterircd

```
Use these credentials for your IRC connection:
server: chat.ndlug.org
port: 6667
SSL: no
password: N/A

Once connected, you need to "/msg mattermost login <nickname> <password>"

Alternatively, ask @pbui on mattermost for the ability to use account tokens and do this:

/msg mattermost login <nickname> token=<token>
```

#### irslackd

```
First, you need to obtain a login-token by following the irslackd configuration instructions. 

As for connecting, use these server credentials
server: chat.ndlug.org
port: 6687
SSL: yes
Password: xoxp token obtained

More detailed instructions for each client provided here:
https://github.com/adsr/irslackd/wiki/IRC-Client-Config

```

#### ZNC

```
To obtain a ZNC account, message @AndroidKitKat on Mattermost or Slack. He will then 
set you up with the proper account and provide help if needed. 

NOTE: this ZNC can be used with any existing IRC connection, so feel free to consolidate 
your IRC connections onto chat
```
