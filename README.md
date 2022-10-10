# Result
## Original
<img alt="original pic" src="./pics/bigs/1.jpeg" width="200" height="200" />

## Mosaicked (using photos shot by myself)
<img alt="mosaicked pic chunkSide=4" src="chunkSide4.jpeg" width="200" height="200" />
<img alt="mosaicked pic chunkSide=24" src="chunkSide24.jpeg" width="200" height="200" />
<img alt="mosaicked pic chunkSide=44" src="chunkSide44.jpeg" width="200" height="200" />
# Method
1. Prepare many small images 
    * e.g. photos from phone album
2. Chooose A big target image 
    * e.g. 丁真
3. Split big image into chunks of pixels (COP)
4. Use the small image which has **the closest average color** to the COP to **replace** it.

***details in main.ipynb***


