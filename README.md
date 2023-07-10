![banner](https://github.com/MrP4nda1337/malf/blob/main/banner.png)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)
![google](https://img.shields.io/badge/Google%20Analytics-E37400?style=for-the-badge&logo=google%20analytics&logoColor=white)
[![OS](https://img.shields.io/badge/Tested%20On-Linux%20%7C%20Android-yellowgreen.svg)](https://termux.com/)
</center>

# Myopecs Admin Login Finder

The MYopecs project, the main idea of which is to collect all the possible Google dorks search combinations and to find the information about the specific web-site: common admin panels, the widespread file types and path traversal. The 99% automated.

Usage example:
--------------
```
git clone https://github.com/MrP4nda1337/malf.git
cd malf
chmod +x malf.sh
./malf.sh health.gov.il
```
or
```
bash ./malf.sh health.gov.il
```

This will work beatifully on Kali but an ultimately universal way is through Docker. Just run 

```
docker build -t FOO .
```

and then run it with your argument for the URL such as this:

```
docker run -it --rm FOO mysite.com
```

Screenshots:
------------
![screenshot](https://github.com/MrP4nda1337/malf/blob/main/sshot.jpg)
