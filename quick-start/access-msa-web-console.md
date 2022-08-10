# Access MSA Web Console

### Access Mini Lab env from Browser

access [https://localhost](https://localhost)

![](<../.gitbook/assets/スクリーンショット 2022-08-10 21.45.22.png>)

{% hint style="info" %}
**user:**ncroot\
**password:**ubiqube
{% endhint %}

{% hint style="warning" %}
Ignore SSL Cert Error

Google Chrome does not allow to access site has invalid SSL Cert file.

Warning Screen appears when you access localhost

Click Detail,and Type "**thisisunsafe**".
{% endhint %}

### Inject Sample Data

After installed. docker containers related MSA up.

execute docker-compose on **msa\_dev** container to inject sample data.

```
docker-compose exec msa_dev /usr/bin/create_mini_lab.sh
```
