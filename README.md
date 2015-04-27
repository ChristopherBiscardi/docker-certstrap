# Initialize a new certificate authority

As seen in the [certstrap examples](https://github.com/square/certstrap#initialize-a-new-certificate-authority)

```bash
docker run -itv `pwd`:/opt/certstrap/out biscarch/certstrap init --common-name "CertAuth"
```
