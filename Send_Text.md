      from twilio.rest import Client

**#Your Account SID from twilio.com/console**
    ```account_sid = "AC3cfa789abd27a01d8f80e07a1074fea0"```

**#Your Auth Token from twilio.com/console**

    auth_token  = "f62f984e3504117e34926f08931ef5c2"
    
    client = Client(account_sid, auth_token)

    message = client.messages.create(
    to="+8618817870108", 
    from_="+15399990355",
    body="你们快点减肥啊，哈哈哈哈哈哈")


    print message.sid
