# Blastmanager API

This consists of pull API implemented by VIMMS and the push api (webhook handler) implemented by Infobric Blastmanager.

The pull API allows historic data to be fetched to blastmanager and also for webhooks to get configured.

The push API is the api to be implemented by webhook handler.

Pull api is publicly available at: [https://blastmanager.alarms.vimms.no/](https://blastmanager.alarms.vimms.no/)

We try to keep the api spec simple enough to be compatible with rest api generators from here: [https://openapi-generator.tech/](https://openapi-generator.tech/)
