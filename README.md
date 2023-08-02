# 4chan-dl
Downloads all images from a 4chan thread. Thread must still exist on 4chan. May add archive support in the future. Planning to rewrite in C eventually. This uses the [4chan API](https://github.com/4chan/4chan-api).

## Dependencies
- curl
- jq

## Usage
```
./dlthread [board] [thread id]
Example: ./dlthread c 4247314
```