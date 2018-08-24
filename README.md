# s3-browser
Script generates index.html files for s3 bucket which enables browser experience.

## Example how it looks like

Link: [https://ryfeus-storage.s3.amazonaws.com](https://ryfeus-storage.s3.amazonaws.com/index.html)

![image](https://s3.amazonaws.com/ryfeus-blog/images/s3browser.png)

## How to start

- Install AWS CLI and configure your programmatic access
- Set up variables

```python
strBucket = 'ryfeus-storage'
strPrefix = ''
strIndexFile = 'index.html'
strTemplate = 'index_template.html'

recPopulateIndexFiles(strBucket,strPrefix,strTemplate)
```
- Run the code

## Things to keep mind

- index.html files will be publicly available
- script doesn't make files publicly available too