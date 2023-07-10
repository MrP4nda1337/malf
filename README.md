![malf](https://github.com/MrP4nda1337/malf/blob/main/banner.png)

# Myopecs Admin Login Finder

The MYopecs project, the main idea of which is to collect all the possible Google dorks search combinations and to find the information about the specific web-site: common admin panels, the widespread file types and path traversal. The 99% automated.

Install


Usage example:
--------------
```
git clone https://github.com/MrP4nda1337/malf.git
cd malf
chmod +x malf.sh
./malf.sh hackerone.com
```
or
```
bash ./malf.sh hackerone.com
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
