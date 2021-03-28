alert tcp any any -> any 3399 (pcre: "/login|Initial/"; flowbits: noalert; flowbits: set, www; sid: 1000000;)
alert tcp any any -> any 3399 (msg: "bot founded"; pcre:"/((\d|[1-9]\d|1\d{2}|2[0-4]\d|25[0-5])\.){3}(\d|[1-9]\d|1\d{2}|2[0-4]\d|25[0-5]):[0-9]{1,5}/"; flowbits: isset, www; sid:1000001;)
