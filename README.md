# ACSA Website 2024

For reasons of Git repository performance, we use separate repositories for text content and images. The image repo should be cloned separately.

```shell
git clone https://github.com/ACSAlab/acsa-web-data.git static
```

**Do not add images or other large binary files to this repository.**

## Deployment

See [documentations](https://docs.acsalab.com/web/) for more details.

## Test

```shell
# on icarus1
hugo server --themesDir ../.. -t topdown --bind=222.195.72.221 --baseURL=http://222.195.72.221 -p 1314 -D -d ../../../public_2
hugo server --buildFuture --themesDir /staff/shaojiemike/github/acsa-web-test/themes -t topdown --bind=222.195.72.221 --baseURL=http://222.195.72.221 -p 1316 -D -d ./public

# on snode6 
hugo server --buildFuture --themesDir /staff/shaojiemike/github/acsa-web-test/themes -t topdown --bind=snode6.acsalab.com --baseURL=http://snode6.acsalab.com -p 1316 -D -d ./public
```

## Questionnaire

[问卷星](https://www.wjx.top/vm/tUtw8Q3.aspx) 

## tools

[people img remove background](https://www.remove.bg/zh/upload)

[choice 2](https://www.photoroom.com/tools/background-remover)

