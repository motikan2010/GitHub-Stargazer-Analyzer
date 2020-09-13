# GitHub Stargazer Analyzer

Create word_cloud image for analyzed star user.

## Using

### 1. Requirement

- Install library. (`requests`, `wordcloud`)
```
pip install -r requirements.txt
```
- Get GitHub **Oauth token**.

### 2. Run command

```
$ python main.py 'Repository Name' 'OAuth Token'
```

- Example command
```
$ python main.py 'nomi-sec/PoC-in-GitHub' 'XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX'
```

### 3. Output image

![word cloud image](./image/word_cloud_20200913_070014.png)

