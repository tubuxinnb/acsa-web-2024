# ACSA Website 2024

For reasons of Git performance, we use separate repositories for text content and images. The image repo should be cloned separately.

```
git clone https://github.com/ACSAlab/acsa-web-data.git static
```

**Do not add images to this repository.**

## Test

```bash
# hugo server --themesDir ../.. -t topdown --bind=222.195.72.221 --baseURL=http://222.195.72.221 -p 1314 -D -d ../../../public_2
hugo server --buildFuture --themesDir /staff/shaojiemike/github/acsa-web-test/themes -t topdown --bind=222.195.72.221 --baseURL=http://222.195.72.221 -p 1316 -D -d ./public
```