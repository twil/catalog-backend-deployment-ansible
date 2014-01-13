How To Deploy
=============

All you need is single Debian 7 VM.

Replace 192.168.1.146 with IP (or hostname) of VM in `dev` inventory file.

Run `ansible-playbook -i dev site.yml [--ask-pass]` to deploy app.

If everything is OK then direct browser to

`http://IPofVM:5000/db?api_key=yoarmoitOxEvhacsIamorhactOoheeckvoorgyixnoFraggOnidBafphufIfnoyt`

and you should see

    {
        "categories": {}, 
        "collections": [
            "categories", 
            "dishes"
        ], 
        "dishes": {}
    }

Well... that'all.
